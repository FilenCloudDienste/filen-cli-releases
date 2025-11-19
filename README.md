<!-- v0.2.0 -->

# Filen CLI

This is a Rust rewrite of [FilenCloudDienste/filen-cli](https://github.com/FilenCloudDienste/filen-cli).

> [!Warning]
> This project is in active development and still missing most functionality. **Don't use it.**

<!-- (ORIGIN ONLY) -->

<!-- this section will be shown in the releases repo -->

> [!note]
> Find the source for this project at [FilenCloudDienste/filen-rs](https://github.com/FilenCloudDienste/filen-rs/tree/main/filen-cli).


This rewrite aims to improve the Filen CLI in multiple ways:
- Significantly reduced download size from up to 130MB to ~5MB.
- Significantly improved performance, especially startup performance, which is critical for CLI applications (because we're using Rust instead of TypeScript).

<!-- ### Changes from the TypeScript CLI:
- only prompts for authentication when needed, not directly on startup -->
