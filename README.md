# Introduction

The source code for the official guide to build a complete Elixir application, with its own supervision tree, configuration, tests and more at: [Elixir Docs](https://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html)

- [Modules](#modules)
    - [KV](#kv)
    -[KV Umbrella](#kv_umbrella)
- [Why?](#why)

## Modules

### KV: 

This repository translates the instructions from Chapter 1-6 of the official guide, You can browse any of the below commits to the position where that chapter ends:

1. Chapter 1-3: [Agent & GenServer Implementation](https://github.com/SlapBot/kv/tree/d6b801759488e939c32243a81dcc23495f726106)
2. Chapter 4: [Supervisor & Applications Implementation](https://github.com/SlapBot/kv/tree/e47e7d2d758ee202bcb56a29a9790e4bf00cb221)
3. Chapter 5: [Dynamic Supervisors Implementation](https://github.com/SlapBot/kv/tree/4867cbeb44201cb3fe4769f1f08175b4b0a8ce83)
4. Chapter 6: [ETS Implementation](https://github.com/SlapBot/kv/tree/23e31b8e02aa9e6e19a36c47778c8ccf628e576a)

Chapter 6-11 covers the new structure of the application that can be found at [Elixir-Mix-Otp-Guide](https://github.com/SlapBot/elixir-mix-otp-guide), the KV module changes following after each iteration of the chapter:

5. Chapter 7: [Managing Dependencies & Umbrella Project Structure](https://github.com/SlapBot/kv/tree/4534e218e12b52237fe7070bb35818198eebb01a)
6. Chapter 8: No Changes needed.
7. Chapter 9: [Writing Doctests, Patterns & with keyword](https://github.com/SlapBot/kv/tree/24a3b75768ea1367128bf8cd0525b1fbd59f2353)
8. Chapter 10: [Distributed Tasks & Tags Implemented](https://github.com/SlapBot/kv/tree/2e662592a6bca37eb52f5dbf92f01ae3a2c51113)
9. Chapter 11: [Configurations & Releases Deployment](https://github.com/SlapBot/kv/tree/1a436f9a3d149efc388a9dd6f2c608b3f7abe881)

### KV Umbrella:

This repository can be found at: [Elixir-Mix-Otp-Guide](https://github.com/SlapBot/elixir-mix-otp-guide)

## Why?

While working throughout the guide - there were multiple positions where the ideolog seemed overwhelming resulting to various logical bugs because of shorthand syntax mismatch. There is no repository available to cross-check your results either to fix your bugs. Hence - I thought it would be nice to have this as a reference guide to how you need to implement your project.
