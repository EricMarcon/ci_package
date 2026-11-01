# multiple

A dummy R package to test CI on Gitub.

The target files are the YAML scripts in `.github/workflows`:

- `check.yml` roxygenizes the package, checks it, tests its code
  coverage and publishes its documentation to Github pages.
- `pr.yml` checks the package on pull requests to detect possible
  errors.

See [Working with R, chapter
6](https://ericmarcon.github.io/WorkingWithR/chap-ci.html) for details.
