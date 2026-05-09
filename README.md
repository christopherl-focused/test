# release-please test

Test repo for verifying release-please integration with Fusion Frontend.

## Test steps

1. Push this repo to GitHub
2. Make a conventional commit: `git commit --allow-empty -m "feat: add new feature"`
3. Push to main → release-please opens a Release PR
4. Merge the Release PR → creates `fusion-frontend-v0.1.1` tag
5. Check Actions → `Fusion Frontend Release` workflow triggers on the tag
