# React Native Typography
This component wraps [Text](http://facebook.github.io/react-native/releases/0.49/docs/text.html#text) and adds an option for System Typography styles like `fontSize`, `letterSpacing`, and more. Styles are taken directly from Apple’s [Human Interface Guidelines](https://developer.apple.com/ios/human-interface-guidelines/visual-design/typography/) and Google’s [Material Design Guidelines](https://material.io/guidelines/style/typography.html).

**Features**
- Use one component to define iOS and Android styles
- Easily define your text style
- All `Text` props are accessible
- Cross-platform

## Installation
```shell
$ yarn add react-native-typography
```

## Usage
```javascript
import { Typography } from "react-native-typography";
```

```javascript
<ScrollView style={styles.container}>
  <Typography iOSTextStyle="largeTitle" androidTextStyle="display4">Lorem Khaled</Typography>
  <Typography iOSTextStyle="title1" androidTextStyle="display3">Lorem Khaled</Typography>
  <Typography iOSTextStyle="title2" androidTextStyle="display2">Lorem Khaled</Typography>
  <Typography iOSTextStyle="title3" androidTextStyle="display1">Lorem Khaled</Typography>
  <Typography iOSTextStyle="headline" androidTextStyle="headline">Lorem Khaled</Typography>
  <Typography iOSTextStyle="body" androidTextStyle="title">Lorem Khaled</Typography>
  <Typography iOSTextStyle="callout" androidTextStyle="subheading">Lorem Khaled</Typography>
  <Typography iOSTextStyle="subhead" androidTextStyle="body2">Lorem Khaled</Typography>
  <Typography iOSTextStyle="footnote" androidTextStyle="body1">Lorem Khaled</Typography>
  <Typography iOSTextStyle="caption1" androidTextStyle="caption">Lorem Khaled</Typography>
  <Typography iOSTextStyle="caption2" androidTextStyle="button">Lorem Khaled</Typography>
</ScrollView>
```

## Props
| Prop | Type | Default | Description |
|---|---|---|---|
| __`children`__ | _Raw text_ | N/A | Text to display. |
| __`iOSTextStyle`__ | _String_ | N/A | iOS Text style. |
| __`androidTextStyle`__ | _String_ | N/A | Android Text style. |
| __`style`__ | _Object_ | N/A | Styles for text. |
