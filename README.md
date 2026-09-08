# Retrac SDK 14.60

<p align="center">
  <img src="https://img.shields.io/badge/Retrac-14.60-5865F2?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/pilottX11/Retrac-SDK-14.60?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/pilottX11/Retrac-SDK-14.60?style=for-the-badge">
  <img src="https://img.shields.io/github/last-commit/pilottX11/Retrac-SDK-14.60?style=for-the-badge">
</p>

<p align="center">
  <a href="#contents">Contents</a> •
  <a href="#sdk">SDK</a> •
  <a href="#offsets">Offsets</a> •
  <a href="#structure">Structure</a>
</p>

## About

Retrac SDK 14.60 is a collection of the SDK definitions, structures, classes, functions, and offset information for the Retrac 14.60 build. The repository is intended to provide the available 14.60 data in an organized format, with the SDK contained separately from the offset reference for easier access and integration.

## Contents

| Component                  | Description                            |
| -------------------------- | -------------------------------------- |
| `SDK/`                     | C++ SDK definitions and generated data |
| `Retrac_offsets_14.60.txt` | Offset and address reference           |
| `README.md`                | Repository documentation               |

## SDK

The `SDK/` directory contains the C++ definitions included with the 14.60 build, including available classes, structures, enums, functions, and related definitions.

```cpp
#include "SDK/SDK.hpp"
```

## Offsets

The `Retrac_offsets_14.60.txt` file contains the available offsets and addresses associated with Retrac 14.60. The offsets are provided separately from the SDK to make them easier to reference and maintain.

## Structure

```text
Retrac-SDK-14.60/
├── SDK/
│   ├── Classes
│   ├── Structs
│   ├── Enums
│   ├── Functions
│   └── SDK.hpp
│
├── Retrac_offsets_14.60.txt
└── README.md
```

## Build

```text
Target       Retrac
Version      14.60
Language     C++
SDK          Included
Offsets      Included
```

## Compatibility

This repository is specifically for Retrac 14.60. SDK definitions and offsets can differ between builds, so the included data should be used with the corresponding 14.60 build.

<p align="center">
  <a href="https://github.com/pilottX11/Retrac-SDK-14.60">
    <img src="https://img.shields.io/badge/View%20Repository-GitHub-181717?style=for-the-badge&logo=github">
  </a>
</p>

<p align="center">
  <sub>Retrac 14.60 SDK and offsets</sub>
</p>
