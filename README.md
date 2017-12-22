# Snippets
## React Native code snippets for Sublime Text

## Usage
### Component
#### [rnc] - Create react-native component
```javascript
import React, { Component } from 'react';
import {
    View,
    Text,
    StyleSheet,
} from 'react-native';


export default class MyComponent extends Component {
    render() {
        return (
            <View style={styles.container}>
                <Text>I am the MyComponent component</Text>
            </View>
        );
    }
}


const styles = StyleSheet.create({
    container: {
        flex: 1,
        justifyContent: 'center',
        alignItems: 'center',
        backgroundColor: '#F5FCFF',
    }
});
```
### Javascript
#### [for] - Create a for loop
```javascript
    for (let index = 0; index < array.length; index++) {
        let element = array[index];
           
    }
```

#### [log] - Create console.log()
```javascript
  console.log();
```

#### [view] - Create View tag
```javascript
  <View style={styles.StyleName}></View>
```

#### [text] - Create Text tag
```javascript
  <Text style={styles.StyleName}></Text>
```

#### [scroll] - Create ScrollView tag
```javascript
  <ScrollView style={styles.StyleName}></ScrollView>
```

#### [texti] - Create TextInput tag
```javascript
  <TextInput style={styles.StyleName}></TextInput>
```

#### [img] - Create imageBackground tag
```javascript
  <ImageBackground source={require('')}
    style={styles.StyleName}
  />
```

#### [constr] - Create Constructor
```javascript
  constructor() {
        super();
        this.state = {
        
        };
    }
```
