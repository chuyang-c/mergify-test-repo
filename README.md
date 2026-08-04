# mergify-test-repo
1
# test
# test2
pull_request_rules:
  - name: auto-merge-anything
    conditions:
      - base=main
    actions:
      merge:
        method: squash
