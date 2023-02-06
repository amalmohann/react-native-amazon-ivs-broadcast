
# react-native-amazon-ivs-broadcast

## Getting started

`$ npm install react-native-amazon-ivs-broadcast --save`

### Mostly automatic installation

`$ react-native link react-native-amazon-ivs-broadcast`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-amazon-ivs-broadcast` and add `RNAmazonIvsBroadcast.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNAmazonIvsBroadcast.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNAmazonIvsBroadcastPackage;` to the imports at the top of the file
  - Add `new RNAmazonIvsBroadcastPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-amazon-ivs-broadcast'
  	project(':react-native-amazon-ivs-broadcast').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-amazon-ivs-broadcast/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-amazon-ivs-broadcast')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNAmazonIvsBroadcast.sln` in `node_modules/react-native-amazon-ivs-broadcast/windows/RNAmazonIvsBroadcast.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Amazon.Ivs.Broadcast.RNAmazonIvsBroadcast;` to the usings at the top of the file
  - Add `new RNAmazonIvsBroadcastPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNAmazonIvsBroadcast from 'react-native-amazon-ivs-broadcast';

// TODO: What to do with the module?
RNAmazonIvsBroadcast;
```
  