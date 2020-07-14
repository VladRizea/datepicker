GET /{@rizeavlad.dev}/media

# Smooth Date Picker
2 scroll axis date picker Dart, Flutter





# How to use

You have to call the widget SmoothDatePicker, and customize it by changing the proprieties

```dart
SmoothDatePicker(
            scrollDirection: Axis.vertical,
            cardDirection: Axis.horizontal,
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
## Result

<img width="300" alt="Picker Example" src="https://github.com/VladRizea/referenceimages/blob/master/example.jpg">

## List of proprieties

* onMonthChanged - get the selected month
* onDayChanged - get the selected day
* mainColor - main color of a card
* secondColor - secondary color of a card(Text)
* scrollDirection - scroll direction of the picker
* cardDirection - the card orientation
* width - width of the picker
* height - height of the picker
* diameterRatio - diameterRatio of the picker
* padding - padding inside the card
* duration - duration of the animation between selection
* cardWidth - the width of the card
* cardHeight - the height of the card

## other combinations
### Horizontal scroll with vertical card
<img width="300" alt="Picker Example" src="https://github.com/VladRizea/referenceimages/blob/master/horizontal%20but%20vertical.jpg">

### Horizontal scroll with horizontal card
<img width="300" alt="Picker Example" src="https://github.com/VladRizea/referenceimages/blob/master/horizontal%20horizontal.jpg">


