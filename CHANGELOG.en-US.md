---
order: 2
title: Change Log
toc: false
---

`@ant-design/react-native` strictly follows [Semantic Versioning 2.0.0](http://semver.org/).

#### Release Schedule

- Weekly release: patch version at the end of every week for routine bugfix (anytime for urgent bugfix).
- Monthly release: minor version at the end of every month for new features.
- Major version release is not included in this schedule for breadking change and new features.

---

### 3.1.1

`2019-01-30`

Happy Chinese New Year

- `popover` adds the `placement` property to support configuration of different positions `'top | right | bottom | left | auto'` [#308](https://github.com/ant-design/ant-design-mobile-rn/issues/308)

### 3.1.0

`2019-01-27`

- Refactor `popover` [#298](https://github.com/ant-design/ant-design-mobile-rn/pull/298)
  - Removed the (`overlayStyle` `contextStyle` `name` `openMenu / closeMenu / toggleMenu` `style` ) property. The refactored version supports multiple Popovers.
  - Please see the popover example for how to use it.
- Fix `input-item` style should not be applied to outer container [#279](https://github.com/ant-design/ant-design-mobile-rn/issues/279)

### 3.0.6

`2019-01-15`

- Fixes `image-picker` `groupTypes` is not supported on Android [#264](https://github.com/ant-design/ant-design-mobile-rn/issues/264)
- Fixes `tab-bar` does not update component after tab has changed [#201](https://github.com/ant-design/ant-design-mobile-rn/issues/201)

### 3.0.5

`2019-01-03`

- Modify `search-bar` icon size [#250](https://github.com/ant-design/ant-design-mobile-rn/pull/250)
- Fixes `input-item` has new line after blur under `ios` [#249](https://github.com/ant-design/ant-design-mobile-rn/issues/249)
- Fixes `input-item` clear icon is not displayed correctly under `android` [#248](https://github.com/ant-design/ant-design-mobile-rn/issues/248)

### 3.0.4

`2018-12-28`

- Modify `SegmentedControl` default color to theme color [#211](https://github.com/ant-design/ant-design-mobile-rn/pull/211)
- Allow overriding `Tabs` `tabBarUnderlineStyle`
- Improve `SwipeAction` TypeScript type definition [#230](https://github.com/ant-design/ant-design-mobile-rn/pull/230)
- Improve the `Grid` document and modify the `onClick` property to `onPress` [#234](https://github.com/ant-design/ant-design-mobile-rn/pull/234)
- Fixed `Modal` circular reference warning [#242](https://github.com/ant-design/ant-design-mobile-rn/pull/242)

### 3.0.0

`2018-12-15`

**Breaking Changes** for more informations please checkout [#119](https://github.com/ant-design/ant-design-mobile-rn/issues/119)

- We get a new package name `@ant-design/react-native` from [afc163](https://github.com/afc163). Thanks..
- Remove the native suffix
- More friendly theme support
- Improve TypeScript type definitions
- Bug fixes
- We can preview our Components online using codesandbox and react-native-web
- Refactor Icon Component and use [ant-design-icons](https://github.com/ant-design/ant-design-icons/tree/master/packages/icons-react-native) instead
- `Toast` has removed method `hide`
- Change `Grid` property `onClick` to `onPress`
- Upgrade from 2.x to 3.0.0 please checkout [upgrade notes](https://rn.mobile.ant.design/docs/react/upgrade-notes)

### 2.3.0

`2018-10-20`

- `Input` add `editable` support. ([#78](https://github.com/ant-design/ant-design-mobile-rn/pull/78))
- Fix `Button` component's `activeStyle` does not work. ([#105](https://github.com/ant-design/ant-design-mobile-rn/pull/105))
- `Modal` add locale support. ([#115](https://github.com/ant-design/ant-design-mobile-rn/pull/115))
- Spanish. ([#75](https://github.com/ant-design/ant-design-mobile-rn/pull/75))
- TypeScript type definition improvements. ([#83](https://github.com/ant-design/ant-design-mobile-rn/pull/83))

### 2.2.1

`2018-07-17`

- Calculate `Grid` item height via `column` property. ([#61](https://github.com/ant-design/ant-design-mobile-rn/pull/61))
- Replace with normalize-css-color. ([#57](https://github.com/ant-design/ant-design-mobile-rn/pull/57))

### 2.2.0

`2018-06-15`

- split the antd-mobile react native code to `antd-mobile-rn` package.
- Feature: Make `Tag` support long press. ([#20](https://github.com/ant-design/ant-design-mobile-rn/issues/20))

### 2.1.11

`2018-05-31`

[antd-mobile@2.1.11 and before change log](https://github.com/ant-design/ant-design-mobile/blob/master/CHANGELOG.en-US.md#2111)
