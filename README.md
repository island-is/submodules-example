# Demo for adding git submodules

Short demo on how paths from other repos can be used as git submodules.

```bash
git submodule add git@github.com:island-is/island.is.git libs/shared
cd shared
git sparse-checkout init --cone
git sparse-checkout set libs/shared
```
