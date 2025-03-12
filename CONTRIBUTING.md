# For Contributors

When exporting, make sure to…
- bump the version in <pack/pack.toml> and <pack/config/bbc-common.toml>
- run `packwiz refresh --build`
- temporarely remove the fabric field in <pack/pack.toml>, before exporting

> **Note**: All commits making changes to the index shall not use the `--build` flag as the <pack/index.toml> file should not contain any hashes for an easier workflow.
