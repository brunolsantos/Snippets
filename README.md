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
