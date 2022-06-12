# ts-react-memo

[![npm](https://img.shields.io/npm/v/ts-react-memo)](https://npm.im/ts-react-memo)
[![build](https://github.com/iyegoroff/ts-react-memo/workflows/build/badge.svg)](https://github.com/iyegoroff/ts-react-memo/actions/workflows/build.yml)
[![publish](https://github.com/iyegoroff/ts-react-memo/workflows/publish/badge.svg)](https://github.com/iyegoroff/ts-react-memo/actions/workflows/publish.yml)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/ts-react-memo)
[![Bundlephobia](https://img.shields.io/bundlephobia/minzip/ts-react-memo?label=min+gzip)](https://bundlephobia.com/package/ts-react-memo)
[![npm](https://img.shields.io/npm/l/ts-react-memo.svg?t=1495378566925)](https://www.npmjs.com/package/ts-react-memo)

React.memo type fix

## Getting started

`$ npm i ts-react-memo`

## Overview

```ts
import React from 'react'

export const memo: <T>(c: T) => T = React.memo
```
