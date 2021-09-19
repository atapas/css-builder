<div align="center">
   <p>
    <h1>css-builder</h1>
  </p>
  <p>
     When we say <i>"CSS for everyone"</i>
  </p>
  <p>
     Learn | Build | Code | Test
  </p>
  <p>A UI based CSS code generator for all expert level</p>

  <p>

  </p>
</div>

---

![GitHub watchers](https://img.shields.io/github/watchers/koustov/css-builder.svg?logo=github&label=Watch) ![GitHub watchers](https://img.shields.io/github/issues/koustov/css-builder?logo=github&label=Issues) ![GitHub watchers](https://img.shields.io/github/stars/koustov/css-builder?logo=github&label=Stars) ![GitHub watchers](https://img.shields.io/npm/dt/css-builder.svg?logo=npm&label=downloads)

This is a **fully flexible** css builder based on [`React`](https://facebook.github.io/react/)

**Note**: The basic infrastructure is created and currently all attributes starting with **"a" been incorporated**. You are welcome to inject more and make it "full-fledged
Currently its a preview build. 0.1.0 will be the first fully fledged version to use.

**Table of Contents**

- [Demo](#demo)
- [Features](#features)
- [When do you need it?](#when-do-you-need-it)
- [Usage](#usage)
  - [Install](#install)
- [Highlight](#highlight)
- [Supported Elements](#supported-elements)
- [How to use](#how-to-use)
- [Playground](#playground)
- [Items in queue](#items-in-queue)
- [Contribution](#contribution)
- [License](#license)

## Demo

Visit https://css-builder.vercel.app/

## Features

- React based
- Completely UI based
- All CSS attributes supported
- Customizable
- Quick and easy.
- Search attribute
- Categorized attributes

## When do you need it

- You want to learn CSS while playing?
- You want to allow n'th level customization on your web app?
- You want to code CSS rapidly?
- Not sure which attribute to chose?

## Usage

- Form customization
- Tutorial
- Learning
- Rapid building

### Install 🐙

```bash
npm install css-builder
```

or

```bash
yarn add css-builder
```

## Highlight 🔥

It was frustrating for me when iI was looking for some easy tool to build CSS using UI and couldn't find anything that helps me in the context. So built my own.

## Supported Elements

Its a HUUUUUUGE list. Will list down in sometime.

### How to use

Import css-builder component

```jsx
import { CSSBuilder } from 'css-builder'
```

Just drop it to desired place

```jsx
<CSSBuilder
  onChange={(a, b, c) => {
    console.log('Value received')
  }}
/>
```

## Playground

Visit https://css-builder.vercel.app/

## Items in queue

- Pending attributes
- Drag/drop for sequencing

## Contribution 🍰

If you understand the importance please feel free to create issue and make pull request

Refer [code of conduct ](./CODE_OF_CONDUCT.md)

Refer [contributing ](./CONTRIBUTING.md)

## License

MIT © [Koustov](https://github.com/koustov)
