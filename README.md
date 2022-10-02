# 🥞 Opensale UIkit

[![Version](https://img.shields.io/npm/v/@opensale/uikit)](https://www.npmjs.com/package/@opensale/uikit) [![Size](https://img.shields.io/bundlephobia/min/@opensale/uikit)](https://www.npmjs.com/package/@opensale/uikit)

Opensale UIkit is a set of React components and hooks used to build pages on Opensale's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @opensale/uikit`

## Setup

### Theme

Before using Opensale UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@opensale/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@opensale/uikit'
...
<ResetCSS />
```
