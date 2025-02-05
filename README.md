# :coffee: mason-registry

![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)
![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)

This project includes personal relevant libraries, runtimes, ... , which are (still) not available in the main mason-registry.

## How to Install

- You can add the new registry before the default mason-registry as follows
- Run `Mason` and wait for mason to update the new registry

```lua
{
  'williamboman/mason.nvim',
  opts = {
    registries = {
      'github:indika-dev/personal-mason-registry',
      'github:mason-org/mason-registry',
    },
  },
}
```
