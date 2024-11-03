<p align="center">
    <a href="https://github.com/TechlauncherFireApp/mobile" rel="noopener">
        <img width=150px src="https://raw.githubusercontent.com/ComposeComponents/.github/main/logo_transparent.png" ></img>
    </a>
    <h1 align="center">Units (for Compose Multiplatform)</h1>
    <p align="center">
        A helper library for defining spacing and textsizes as a multiple of some base unit (default 16dp/16sp).
    </p>
</p>

<div align="center">
    
[![Build](https://github.com/ComposeComponents/units-kmp/actions/workflows/build.yml/badge.svg)](https://github.com/ComposeComponents/units-kmp/actions/workflows/build.yml)
[![Lint](https://github.com/ComposeComponents/units-kmp/actions/workflows/lint.yml/badge.svg)](https://github.com/ComposeComponents/units-kmp/actions/workflows/lint.yml)

</div>

## Installation
![Stable](https://img.shields.io/github/v/release/ComposeComponents/Units?label=Stable)
![Preview](https://img.shields.io/github/v/release/ComposeComponents/Units?label=Preview&include_prereleases)

```
implementation "cl.emilym.kmp:units:<latest>"
```

## Usage
```kotlin
CompositionLocalProvider(
    LocalBaseDp provides 8.dp
) {
    // Box is sized to 16dp by 16dp
    Box(Modifier.size(2.rdp))
}
```
