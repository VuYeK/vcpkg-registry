# vcpkg-registry

Custom vcpkg registry.

Currently included packages:
- sciter

# usage
add the following to your `vcpkg-configuration.json`. For a more detailed explanation see https://github.com/microsoft/vcpkg/blob/master/docs/specifications/registries-2.md#consuming-registries
```
{
    "registries": [
        {
            "kind": "git",
            "repository": "https://github.com/VuYeK/vcpkg-registry.git",
            "packages": [] <-- !add the used ports here! eg: "sciter"
        }
    ]
}
