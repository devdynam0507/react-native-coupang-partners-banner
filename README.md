
# react-native-react-native-coupang-partners-banner

## Getting started

`$ npm install react-native-react-native-coupang-partners-banner --save`

### Mostly automatic installation

`$ react-native link react-native-react-native-coupang-partners-banner`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-react-native-coupang-partners-banner` and add `RNReactNativeCoupangPartnersBanner.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNReactNativeCoupangPartnersBanner.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativeCoupangPartnersBannerPackage;` to the imports at the top of the file
  - Add `new RNReactNativeCoupangPartnersBannerPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-react-native-coupang-partners-banner'
  	project(':react-native-react-native-coupang-partners-banner').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-react-native-coupang-partners-banner/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-react-native-coupang-partners-banner')
  	```


## Usage
```javascript
import RNReactNativeCoupangPartnersBanner from 'react-native-react-native-coupang-partners-banner';

// TODO: What to do with the module?
RNReactNativeCoupangPartnersBanner;
```
  