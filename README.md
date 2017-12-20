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
    },
    welcome: {
        fontSize: 20,
        textAlign: 'center',
        margin: 10,
    },
    instructions: {
        textAlign: 'center',
        color: '#333333',
        marginBottom: 5,
    },
});
```
### Javascript
#### [for] - Create a for loop
```javascript
  console.log();
```

#### [log] - Create console.log()
```javascript
  for (let index = 0; index < array.length; index++) {
    let element = array[index];
            
  }
```
