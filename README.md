# datepicker
2 axis date picker Dart, Flutter

# How to use

You have to call the widget SmoothDatePicker, and customize it by changing the proprieties

```dart
SmoothDatePicker(
            mainColor: Colors.blue,
            secondColor: Colors.yellow,
            onMonthChanged: (month){
              print(month),
            },
            onDayChanged: (day){
              print(day),
            },
          ),
```
