# react-native-trix

#### React Native Trix editor component with no native code for React Native apps built using WebView

## Installation

```
yarn add react-native-trix
```

or

```
npm install --save react-native-trix
```

and then

```jsx harmony
import CKEditor from 'react-native-tix';
```

## Usage

Creating a Trix editor:


```jsx harmony
<Trix
  content={values.description}
  onChange={value => {
    setFieldValue('description', value);
  }}
/>
```
