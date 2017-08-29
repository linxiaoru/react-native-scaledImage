# react-native-scaledImage

A Image component which can be sacled written in pure javascript for cross-platform support.

### Documentation

#### Props
- uri, uri of the image, required
- width number, width of the image, optional
- height number, width of the image, optional

#### Step 1 - install
```
npm install react-native-scaledImage --save
```

	
#### Step 2 - import and use in project
```javascript
import scaledImage from 'react-native-scaledImage';

<ScaledImage uri={image} />

// or
<ScaledImage uri={image} >
  {... some other View or Text}
</ScaledImage>
```
	