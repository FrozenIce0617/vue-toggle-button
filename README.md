# Vue.js toggle / switch button
VueJS ToggleButton component

### How to use

```xml
<toggle-button @change="onChangeEventHandler"/>

<toggle-button v-model="myDataVariable"/>

<toggle-button :value="false"
               color="#82C7EB"
               :sync="true"
               :labels="true"/>

<toggle-button :value="true"
               :labels="{checked: 'Foo', unchecked: 'Bar'}"/>
```
