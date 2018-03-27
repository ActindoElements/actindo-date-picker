# actindo-date-picker
A material design based date picker. Using the paper-date-picker
for day and year selection. The latter is based on an iron-list.
Some adjustments were required in paper-date-picker - see/use this 
fork of the [paper-date-picker](https://github.com/ActindoElements/paper-date-picker).
The selected date is set in the paper-input line. It supports to
set a dedicated label. The date format can be set via a locale
variable based on [moment.js](https://momentjs.com/). A minimum
and maximum date can be set.


## Example
```javascript
<actindo-date-picker label = "Select date" format = "l" locale = "de" min-date = "01.01.2018" max-date = "31.12.2018"></actindo-date-picker>
```

![Example day](https://raw.githubusercontent.com/ActindoElements/actindo-date-picker/master/example/example_day.png)
![Example day](https://raw.githubusercontent.com/ActindoElements/actindo-date-picker/master/example/example_year.png)
## Properties

**format**:
Use moment.js style of format. i.e. "l" for "dd.mm.yyyy". It supports the locale option

**locale**:
Set the locale for the date, i.e. "de", "en-gb". This adjusts the supported format for the input and output date

**min-date**:
Set the minimum date allowed for the date picker. Should be in the same format as given in format

**max-date**:
Set the maximum date allowed for the date picker. Should be in the same format as given in format

**label**:
Set the label visible in the paper-input line

