## Attributes

`io.github.mcgradleconventions.loader`: the loader a variant is compatible with, with regards to both artifacts and transitive dependencies. Valid values include:
- `fabric`
- `neoforge`
- `forge`
- `common`

Multi-loader modding tooling should provide this value on `apiElements`, `runtimeElements`, and other loader-specific outgoing variants and should consume it on `compileClasspath` and `runtimeClasspath` or equivalents.

## Tooling

The following setups for multiloader modding are known to support these conventions:
- MultiLoader Template, as of https://github.com/jaredlll08/MultiLoader-Template/pull/108
- [Cloche](https://github.com/terrarium-earth/cloche), as of 0.16.12([70eb29e](https://github.com/terrarium-earth/cloche/commit/70eb29ecb7aee85e117060409d0eb68aa2e91b64))
