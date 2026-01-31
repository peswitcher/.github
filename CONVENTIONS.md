# Conventions for PESwitcher

This document outlines all the conventions throughout the projects. This document is split up into 3 parts.

- [Icon Conventions](#icon-conventions)
- [Git/GitHub Conventions](#git-conventions)
- [Code Conventions](#code-conventions)

## Icon Conventions
Icons should be 16px by 16px in the SVG.
When exporting, 64x64 is good enough for most cases, but lower resolutions are also accepted.
The exception to this is the github logo, which is 256x256 to preserve detail.
Lines should be snapped to the nearest pixel to keep the detail at lower resolutions

## Git Conventions

The central branch should be named `master`.
(TODO: add more lol)

## Code Conventions

Below is a table with the naming scheme for different types. See the [clang-format file](https://github.com/peswitcher/.github/blob/main/.clang-format) as well

| Type | Convention |
| --- | --- |
| Public Variable or Function | snake_case |
| Private Variable or Function | _snake_case |
| Class, Struct, or Enum | PascalCase |
| Namespaces | snake_case |

All public api functions must have a meaningful comment detailing what the function does, what it returns, and what all of the arguments are.
Variables should have an explination if their name isn't 100% clear as to what they do.

All comments must be [C Style Comments](https://en.cppreference.com/w/c/comment.html), and documentation should be using [Javadoc Markup](https://en.wikipedia.org/wiki/Javadoc) to work with Doxygen.
