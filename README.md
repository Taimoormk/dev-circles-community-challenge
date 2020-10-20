# Facebook Dev Circles Community Challenge 🔥🔥🔥

## The Challenge 🎖
Create innovative and immersive tutorials that help fellow developers build with Facebook technologies, for more info please check this [link](https://developercircles2020.devpost.com/?utm_source=social-facebook&utm_medium=devc&utm_campaign=organic&utm_content=post-url&utm_offering=business-tools&utm_product=DevC-CommunityChallenge-Launch_09102020&utm_event=2020DevCCommunityChallengeLaunch&eventSource=OrganicSocialDevC).

## The Category
This tutorial is classified under `intermediate` and `expert` level of developer audiences. Also, the chosen language for this tutorial shall be English.

## Table of Content
- [The Architecture](#the-architecture)
- [Technologies Covered](#technologies-covered)
- [React Pakistan Repositories](#react-pakistan-repositories)
- [React Commons Collection](#react-commons-collection)
- [Baked Responsiveness](#baked-responsiveness)
- [Baked Theme](#baked-theme)
- [React UI Collection](#react-ui-collection)
- [React Icon Collection](#react-icon-collection)
- [React Logo Collection](#react-logo-collection)
- [React Emoji Collection](#react-emoji-collection)
- [React Native Commons Collection](#react-native-commons-collection)
- [Baked Theme](#baked-theme)
- [React Native UI Collection](#react-native-ui-collection)
- [React Native Icon Collection](#react-native-icon-collection)
- [React Native Logo Collection](#react-native-logo-collection)
- [React Native Emoji Collection](#react-native-emoji-collection)
- [React Native Boilerplate](#react-native-boilerplate)
- [React Pakistan Docs](#react-pakistan-docs)
- [Util Functions](#util-functions)
- [Util React Native Functions](#util-react-native-functions)
- [Eslint Config Shared](#eslint-config-shared)

## The Architecture

## Technologies Covered
- React
- React Native
- Docusaurus

## React Pakistan Repositories 
Following are list of all `React Pakistan` repositories and their current status as of today.

| Project             | GitHub           | NPM   | Open Source'd  |
| ------------------- |:----------------:|:-----:|:--------------:|
| React Pakistan Docs | [github](https://github.com/react-pakistan/react-pakistan-docs)     |  ❌    | ✅     |
| React Commons Collection | [github](https://github.com/Taimoormk/react-commons-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-commons-collection)    | ❌ ETA: Q1 2021     |
| React UI Collection | [github](https://github.com/Taimoormk/react-ui-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-ui-collection)    | ❌ ETA: Q1 2021     |
| React Icon Collection | [github](https://github.com/react-pakistan/react-icon-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-icon-collection)    | ✅     |
| React Logo Collection | [github](https://github.com/react-pakistan/react-logo-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-logo-collection)    | ✅     |
| React Emoji Collection | [github](https://github.com/react-pakistan/react-emoji-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-emoji-collection)    | ✅     |
| React Native Commons Collection | [github](https://github.com/Taimoormk/react-native-commons-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-native-commons-collection)    | ❌ ETA: Q1 2021     |
| React Native UI Collection | [github](https://github.com/react-pakistan/react-native-ui-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-native-ui-collection)    | ❌ ETA: Q1 2021     |
| React Native Icon Collection | [github](https://github.com/react-pakistan/react-native-icon-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-native-icon-collection)    | ✅     |
| React Native Logo Collection | [github](https://github.com/react-pakistan/react-native-logo-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-native-logo-collection)    | ✅     |
| React Native Emoji Collection | [github](https://github.com/react-pakistan/react-native-emoji-collection)     | [npm](https://www.npmjs.com/package/@react-pakistan/react-native-emoji-collection)    | ✅     |
| React Native Boilerplate | [github](https://github.com/react-pakistan/react-native-boiletplate)     | ❌    | ✅ Refactor ETA: Q1 2021     |
| Util Functions | [github](https://github.com/react-pakistan/util-functions)     | [npm](https://www.npmjs.com/package/@react-pakistan/util-functions)    | ✅     |
| Util React Native Functions | [github](https://github.com/react-pakistan/util-react-native-functions)     | [npm](https://www.npmjs.com/package/@react-pakistan/util-react-native-functions)    | ✅     |
| Eslint Shared Config | [github](https://github.com/react-pakistan/eslint-config-shared)     | [npm](https://www.npmjs.com/package/@react-pakistan/eslint-config-shared)    | ✅     |

### React Commons Collection
`React Commons Collection` is the most generic form of `React` web components which can be transformed into any design specifications, required by your next project.

The general motivation involved in building this library from the ground zero is to create design-less React web components, which could then we extended upon to build anything specific to the project requirements and custom use cases.

Although, there are a ton of popular `React` UI libraries available, but my intention was to build set of `React Commons Collection` which can be customized however you need to for your project requirements.

#### Baked Responsiveness
`React Commons Collection` library comes with built in responsive feature of responsive for each element right into it's core. Following is the sample code to use the responsive feature of any `React Commons Component`.

```javascript
  <H1
    color='#FFFFFF'
    desktop=''
    fontFamily='Playfair Display'
    fontSize='2em'
    fontWeight={700}
    laptop=''
    laptopL=''
    letterSpacing="1px"
    lineHeight="normal"
    mobileL=''
    mobileM=''
    mobileS=''
    tablet=''
    textAlign="center"
    textTransform="uppercase"
  >
    H1 Component
  </H1>
```

Checkout the above sample H1 code, `desktop`, `laptop`, `laptopL`, `mobileL`, `mobileM`, `mobileS`, `tablet` are optional props that will manage the responsiveness of this component on each of these breakpoints with the help of underlying mechanics.

Imagine if we need to change color of H1 on `desktop` size screen, I'd leverage it's `desktop` props by doing so:

```javascript
  <H1
    color='#FFFFFF'
    desktop={`
      color: 'red;
    `}
    fontFamily='Playfair Display'
    fontSize='2em'
    fontWeight={700}
    laptop=''
    laptopL=''
    letterSpacing="1px"
    lineHeight="normal"
    mobileL=''
    mobileM=''
    mobileS=''
    tablet=''
    textAlign="center"
    textTransform="uppercase"
  >
    H1 Component
  </H1>
```

Notice, we just passed the stringified `CSS` to the concerned props to manage our responsive code for each of these components, this is how simple it is to manage the responsive of each components as per your needs.

#### Baked Theme
By leveraging `StyledComponents` built-in theme support has been configured throughout `React Commons Collection` and all of it's extensions too.

Theme is a massive object that holds a ton of properties categories under various sections, following is the `interface` to put things into perspective.

```typescript
  interface ITheme {
    avatarSizes : IAvatarSizes;
    breakpoints : IBreakpoints;
    colors : IColors;
    misc : IMisc;
    radius : IRadius;
    shadow : IShadow;
    spacing : ISpacing;
    typography : ITypography;
    zIndex : IZindex;
  }
```

### React UI Collection
`React UI Collection` is an extension of `React Commons Collection`, building project specific UI/UX on generic components. There are two fully functional apps built on this library;

An `e-commerce` and `developer portfolio` app were built using `React Commons Collection` components, cutting the development overheads and making sure to enable same coding standards and practices across all projects.

This approach helped a lot to write good standard, robust and maintainable code, single handedly.

### React Icon Collection
`React Icon Collection` is an extension of `React Commons Collection`, this library contains 1000's of `React` SVG components of icons, making is so convenient for developers to take the pain out of using SVG with `React`. Following is the sample code to get started with it.

```javascript
  import { FourthofjulyGrey12 } from '@react-pakistan/react-icons-collection/fourthofjuly-grey';

  <FourthofjulyGrey12
    fontSize="32px"
    fill="#2E2E2E"
  />
```

### React Logo Collection
Same as `React Icon Collection`, but only difference it has is that it contains several logos. Following is the sample code to get started with it.

```javascript
  import { BitcoinColor22 } from '@react-pakistan/react-logo-collection/logos/bitcoin-color';

  <BitcoinColor22
    fontSize="32px"
    color="#2E2E2E"
  />
```

### React Emojis Collection
Same as `React Icon Collection`, but only difference it has is that it contains 1000's of emojis. Following is the sample code to get started with it.

```javascript
  import { BodyParts1 } from '@react-pakistan/react-logo-collection/emoji/body-parts';

  <BodyParts1
    fontSize="32px"
  />
```

### React Native Commons Collection
Same reasoning goes behind building this library as of `React Commons Collection`, except that it focuses on `React Native` platform rather.

#### Baked Theme
Theme support has been baked right into it's core to enable several features across all extended libraries.

### React Native UI Collection
Same reasoning goes behind building this library as of `React UI Collection`, except that it focuses on `React Native` platform rather.

### React Native Icon Collection
Same reasoning goes behind building this library as of `React Icon Collection`, except that it focuses on `React Native` platform rather.

### React Native Logo Collection
Same reasoning goes behind building this library as of `React Logo Collection`, except that it focuses on `React Native` platform rather.

### React Native Emoji Collection
Same reasoning goes behind building this library as of `React Emoji Collection`, except that it focuses on `React Native` platform rather.

### React Native Boilerplate
It is a curated list of built boilerplate of `React Native` using various tool and technologies for everyone to kick-start quicker on their next cool app.

### React Pakistan Docs
Central documentation for all of `React Pakistan` published packages and libraries, built on state of the art `Docusaurus`. This helps developers to save time in switching between docs when using various libraries from `React Pakistan` eco-system.

### Util Functions
A collection of util functions for `React` web libraries, helping to reduce the overall code length and to enable maximum re-useability across all packages.

### Util React Native Functions
Same reasoning goes behind building this library as of `Util Functions`, except that it focuses on `React Native` platform rather.

### Eslint Config Shared
Since all of `React Pakistan` packages heavily relies on `TypeScript` and at some places `JavaScript`, so it'd be meaningful if we have a central space where all of our `Eslint` rules are defined, this package just does that.
