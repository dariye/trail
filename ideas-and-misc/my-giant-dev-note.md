# An endless note on everything dev related

## 01.16.2016

### ReactNative

Build on top of the core concepts of React. 

Single application entry point via `AppRegistry` that can be imported from the
core `react-native` module.

Core components include
- Text
- View
- Image
- Stylesheet

- all dimensions in react native are unitless and represent *density-independent
  pixels* 

- you can use `flex` to determine relative dimensions of sibling components in a
  view.

- Layout with Flexbox
Works the same way as flexbox using CSS for the most part save for:
  - flexDirection defaults to column instead of row
  - flex parameter only supports a single number

### JavaScript30
- localStorage && Event Delegation

- always opt for es6 `` for multiline DOM compositions
- design functions that accept parameters to be robust by providing default
  values
- use `||` operator to conditionally fetch current state or default value
- event delegation allows to defer event listening to a non dynimic element on a
  page ideally the parent of a children to be listened to.



