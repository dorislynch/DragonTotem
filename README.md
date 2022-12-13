
# react-native-dragon-totem

## Getting started

`$ npm install react-native-dragon-totem --save`

### Mostly automatic installation

`$ react-native link react-native-dragon-totem`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-dragon-totem` and add `RNDragonTotem.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNDragonTotem.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNDragonTotemPackage;` to the imports at the top of the file
  - Add `new RNDragonTotemPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-dragon-totem'
  	project(':react-native-dragon-totem').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-dragon-totem/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-dragon-totem')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNDragonTotem.sln` in `node_modules/react-native-dragon-totem/windows/RNDragonTotem.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Dragon.Totem.RNDragonTotem;` to the usings at the top of the file
  - Add `new RNDragonTotemPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNDragonTotem from 'react-native-dragon-totem';

// TODO: What to do with the module?
RNDragonTotem;
```
  