## Attributes

`io.github.mcgradleconventions.loader`: the loader a variant is compatible with, with regards to both artifacts and transitive dependencies. Valid values include:
- `fabric`
- `neoforge`
- `forge`
- `common`

Multi-loader modding tooling should provide this value on `apiElements`, `runtimeElements`, and other loader-specific outgoing variants and should consume it on `compileClasspath` and `runtimeClasspath` or equivalents.
