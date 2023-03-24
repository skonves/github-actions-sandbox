### If you merge this PR

- The package version will be updated on the target branch
- A tag will be created for the new version
- The new version will be published on NPM
- ⚠️ The published package will contain all changes on the target branch at the time this PR is merged _even if they were merge after this PR was created_. ⚠️

NOTE: If the new version is a pre-release, then the package will be published under the same distibution tag. For example, if the version is `1.2.3-alpha.4`, then the package will be published under the `alpha` distibution tag and can be installed with `package-name@alpha`.

[Learn more about NPM dist-tags](https://docs.npmjs.com/cli/commands/npm-dist-tag)

### If you close this PR

- No code will change and no new packages will be published.
- Future attempts to create the same version will fail until this branch is delete.
