## custom_date_range_picker

**custom_date_range_picker**

<p align="center"><img src="https://raw.githubusercontent.com/El-Mazouzi/custom_date_range_picker/master/screenshot.jpg" width="320" height="650"/></p>

To call the CustomDateRangePicker component, you need to pass the following props:

```dart
...
  floatingActionButton: FloatingActionButton(
        onPressed: () {
          showCustomDateRangePicker(
            context,
            dismissible: true,
            minimumDate: DateTime.now(),
            maximumDate: DateTime.now().add(const Duration(days: 30)),
            endDate: endDate,
            startDate: startDate,
            onApplyClick: (start, end) {
              setState(() {
                endDate = end;
                startDate = start;
              });
            },
            onCancelClick: () {
              setState(() {
                endDate = null;
                startDate = null;
              });
            },
          );
        },
        tooltip: 'choose date Range',
        child: const Icon(Icons.calendar_today_outlined, color: Colors.white),
      ),
```
<<<<<<< HEAD

Many Thanks to the creator of this Repo https://github.com/mitesh77/Best-Flutter-UI-Templates

## Getting Started

For help getting started with Flutter, view our online [documentation](https://flutter.io/).

For help on editing package code, view the [documentation](https://flutter.io/developing-packages/).
=======
>>>>>>> 1898a6d299ddf5cee802abd9c6327d26643e6995
