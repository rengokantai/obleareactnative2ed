# obleareactnative2ed
```
create-react-native-app first-project
```
traditional
```
npm install -g react-native-cli
react-native init FirstProject
cd FirstProject
react-native run-ios
```
mac
```
open ios/FirstProject.xcodeproj
```

```
<TextInput style={styles.input} onSubmitEditing={this._handleTextChange}/>
```
```
constructor(props) {  
  super(props);  
  this.state = { zip: "" };
}
_handleTextChange = event =>{
  this.setState({zip:event.nativeEvent.text})
}
```

## Chapter 4. Components for Mobile
```resizeMode``` prop, for instance, which can be set to ```contain```, ```cover```, or ```stretch```

The <TouchableHighlight> component also gives you hooks for events such as onPressIn, onPressOut, onLongPress, and the like, so you can use these events in your React applications.
