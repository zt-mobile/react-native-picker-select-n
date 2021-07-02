# react-native-picker-select-n

## Getting started

`$ npm install react-native-picker-select-n --save`

### Mostly automatic installation

`$ react-native link react-native-picker-select-n`

## Usage
```javascript
import React from "react";
import { View } from "react-native";
import { Icon } from "native-base";
import PickerSelectN from 'react-native-picker-select-n';

const PickerSelectN = props => {
    return(
        <View style={{ flex: 1 }}>
            <PickerSelectN
                placeholder={"Please select"}
                onValueChange={val => console.log(val)}
                value={val}
                itemStyle={{ color: "white" }}
                Icon={<Icon name="md-caret-down" />}
            />
        </View>
    );
};

```
