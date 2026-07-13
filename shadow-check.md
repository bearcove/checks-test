# Shadow check

This pull request is the production-path test driver for `checks.vixen.rs`.
Its expected result is the policy-defined successful no-checks aggregate: no
job is dispatched, but the authenticated webhook, immutable policy binding,
durable publication intent, and GitHub Check Run all execute normally.
