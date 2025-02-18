# Crossplane Provider Workflows
Repository for commonly shared GitHub CI workflows that can be used by Crossplane providers.

> [!CAUTION]
> This repo is under active development. Not recommended for non-development use yet.

## Available workflows

Find these workflow files in the [.github/workflows](https://github.com/crossplane-contrib/provider-workflows/tree/main/.github/workflows) directory.

| Workflow                      | Description                                                                                                                                      |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| `backport`                    | Backport merged pull requests to the specified branch using `backport xxx` labels. E.g. `backport release-3.4`                                   |
| `backport-comment-trigger`    | Trigger the backport of a merged pull request with a `/backport` comment after it has already been merged.                                       |
| `ci`                          | Collection of continuous integration steps to verify, test, build and publish a provider.                                                        |
| `uptest-comment-trigger`      | Allows for running Uptest against an example MR manifest using the `/test-examples="xxx"` comment.                                               |
| `publish-provider-family`     | A callable workflow that can publish provider packages with family structure to xpkg.crossplane.io/crossplane-contrib registry/organization.     |
| `publish-provider-non-family` | A callable workflow that can publish provider packages with non-family structure to xpkg.crossplane.io/crossplane-contrib registry/organization. |
