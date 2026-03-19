# CalVer Test

Test repository for CalVer release automation via GitHub Actions.

## How it works

When a PR is merged to `main`, GitHub Actions will:
1. Calculate the next CalVer version (`YYYY.0M.MICRO`)
2. Bump version in `package.json`
3. Update `CHANGELOG.md` with the PR title
4. Create a git tag and GitHub Release

Test change
