## Attributes

`io.github.mcgradleconventions.loader`: the loader a variant is compatible with, with regards to both artifacts and transitive dependencies. Valid values include:
- `fabric`
- `neoforge`
- `forge`
- `common`

Multi-loader modding tooling should provide this value on `apiElements` and `runtimeElements` or equivalents and should consume it on `compileClasspath` and `runtimeClasspath` or equivalents.
