# actindo-date-picker
A material design based date picker. Using the paper-date-picker
for day and year selection. The latter is based on an iron-list.
Some adjustments were required in paper-date-picker.
The selected date is set in the paper-input line.

## Example
```javascript
<actindo-date-picker label = "Select date" format = "l" local = "de"></actindo-date-picker>
```

![Example day](https://raw.githubusercontent.com/ActindoElements/actindo-date-picker/master/example/example_day.png)
![Example day](https://raw.githubusercontent.com/ActindoElements/actindo-date-picker/master/example/example_year.png)
## Properties

**format**:
Use moment.js style of format. i.e. "l" for "dd.mm.yyyy". It supports the local option

**local**:
Set the local for the date, i.e. "de", "en-gb". This adjusts the supported format for the input and output date


**label**:
Set the lable visible in the paper-input line

