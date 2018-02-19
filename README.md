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
