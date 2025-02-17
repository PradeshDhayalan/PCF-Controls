# PCF-Controls
Controls using PowerApps Components Framework

[NN Checkboxes](#nn-checkboxes)

[Custom Switch](#custom-switch)

## NN Checkboxes

[Download](https://github.com/MscrmTools/PCF-Controls/releases/)

### Purpose
The purpose of this control is to allow user to associate/disassociate records for a many-to-many relationship displaying all possible records as checkboxes or toggle switches

![Vidéo](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/video.gif?raw=true)

### Samples
||Checkboxes|Switches|
|--|--|--|
|No color / Not grouped|![Sample2](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample2.png?raw=true)|![Sample1](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample1.png?raw=true)|
|Records Color / Not grouped|![Sample5](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample5.png?raw=true)|![Sample6](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample6.png?raw=true)|
|No color / Grouped|![Sample3](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample3.png?raw=true)|![Sample9](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample9.png?raw=true)|
|Records color / Grouped |![Sample4](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample4.png?raw=true)|![Sample7](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample7.png?raw=true)|
|Group color / Grouped|![Sample10](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample10.png?raw=true)|![Sample8](https://github.com/MscrmTools/PCF-Controls/blob/master/NNCheckboxes/Screenshots/Sample8.png?raw=true)|

### Configuration

This is the list of parameters that can be set on the control

|Parameter|Description|Required|Bound to an attribute|
|---------|-----------|:----:|:---:|
|**Display attribute**|Attribute to use as label for the checkbox|X|X|
|**Relationship schema name**|Schema name of the relationship. *required only if multiple many-to-many relationship exist for both related entities*|?||
|**Background color**|Attribute to use as background color||X|
|**Color**|Attribute to use as forecolor||X|
|**Columns**|Number of columns to display checkboxes|X||
|**Grouping Attribute**|Attribute used to group records. *If used, this attribute must be the first attribute used to sort the view used by this control*||X
|**Layout**|Choose the layout for the rendering|X||
|**Switch Off color**|Default background color when the switch is Off. *This parameter is overriden by the parameter **Background color***||X|
|**Switch On color**|Default background color when the switch is On. *This parameter is overriden by the parameter **Background color***||X|


## Custom Switch

[Download](https://github.com/MscrmTools/PCF-Controls/releases/)

### Purpose
The purpose of this control is to allow user to add switch for Two Options attribute and apply the color and shape they want to fit with the color of the company.

### Samples

![Screenshot](https://github.com/MscrmTools/PCF-Controls/blob/master/CustomSwitch/screenshots/capture.png?raw=true)

### Configuration

This is the list of parameters that can be set on the control

|Parameter|Description|Required|Bound to an attribute|
|---------|-----------|:----:|:---:|
|**Attribute**|The attribute to display as a switch|X|X|
|**Off color**|Color used for the switch background when the value is Off|||
|**On color**|Color used for the switch background when the value is On|||
|**Switch color**|Color used for the switch|||
|**Layout**|Square or Round|X||
|**Display label**|Indicates if selected option label must be displayed next to the switch||
