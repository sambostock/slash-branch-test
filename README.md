# slash-branch-test

This repo has two branches

- `a/b`
- `c`

This prevents the following branches from being created

- `a` (since `a/b` exists)
- `c/d` (since `c` exists)
