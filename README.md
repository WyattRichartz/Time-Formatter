# Install with:
```
pip install timeprintformat==1.0.0
import timeprintformat
```

# Information
This library is a single function that outputs an easy-to-read string of a time input. This is useful for printing values to the console that are intended to be read by the user (in other words, the readability and presentability of the time is important). By "easy-to-read," I mean the function outputs a time in terms of years, months, weeks, days, hours, and so on so that the time being printed will have a sensible unit attached to it.

# Examples
```
timeprintformat.format_time(7982.92)
```
> output = '2.21748 hours'

```
timeprintformat.format_time(7982.92, max_displayed_units=3)
```
> output = '2 hours, 13 minutes, and 2.92 seconds'

```
timeprintformat.format_time(7982.92, decimal_points=2, max_displayed_units=2)
```
> output = '2 hours and 13.05 minutes'
