# RTL Time Picker

RTL Support and flexible to change language.

<a href="https://amiryxe.github.io/rtl-timepicker/"><h2>View Demo</h2></a>

# How to use

1. Make sure your Project included jQuery library
2. Include `mdtimepicker.css` and `mdtimepicker.js` like this:

```html
<link rel="stylesheet" href="mdtimepicker.css" />
<script src="mdtimepicker.js"></script>
```

3. Create a input for Time Picker

```html
<input type="text" id="timepicker" />
```

4. Add this code to `Script` tag

```Javascript
$(document).ready(function(){
  $('#timepicker').mdtimepicker(); //Initializes the time picker
});
```

```javascript
// Example of more configs:

$("#timepicker").mdtimepicker({
  timeFormat: "hh:mm:ss.000", // format of the time value (data-time attribute)
  format: "hh:mm tt", // format of the input value
  readOnly: false, // determines if input is readonly
  hourPadding: false,
  theme: "green",
  okLabel: "تائید",
  cancelLabel: "انصراف",
});
```

Developed based on <a href="https://github.com/dmuy/MDTimePicker">MDTimePicker</a>
