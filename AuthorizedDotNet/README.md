
# react-native-authorized-dot-net

## Getting started

`$ npm install react-native-authorized-dot-net-library-ckn --save`

### Mostly automatic installation

`$ react-native link react-native-authorized-dot-net-library-ckn`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-authorized-dot-net-library-ckn` and add `RNAuthorizedDotNet.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNAuthorizedDotNet.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.scit.rn_authorizeddotnet.RNAuthorizedDotNetPackage;` to the imports at the top of the file
  - Add `new RNAuthorizedDotNetPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-authorized-dot-net-library-ckn'
  	project(':react-native-authorized-dot-net-library-ckn').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-authorized-dot-net-library-ckn/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-authorized-dot-net-library-ckn')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNAuthorizedDotNet.sln` in `node_modules/react-native-authorized-dot-net-library-ckn/windows/RNAuthorizedDotNet.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Authorized.Dot.Net.RNAuthorizedDotNet;` to the usings at the top of the file
  - Add `new RNAuthorizedDotNetPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNAuthorizedDotNet from 'react-native-authorized-dot-net-library-ckn';

// TODO: What to do with the module?
RNAuthorizedDotNet;
```
  
