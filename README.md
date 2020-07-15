
[![Instagram](https://img.shields.io/twitter/url?label=Follow%20@rizeavladdev&logo=twitter&style=social&url=https%3A%2F%2Fwww.instagram.com%2Frizeavladdev%2F)](https://twitter.com/rizeavladdev)
[![Instagram](https://img.shields.io/twitter/url?label=Follow%20@rizeavladdev&logo=instagram&style=social&url=https%3A%2F%2Fwww.instagram.com%2Frizeavladdev%2F)](https://www.instagram.com/rizeavladdev/)
# Smooth Date Picker

<br>
Horizontal and vertical date picker in  Flutter




# How to use

You have to call the widget SmoothDatePicker, and customize it by changing the proprieties

```dart
SDatePicker(
            scrollDirection: Axis.vertical,
            cardDirection: Axis.horizontal,
            mainColor: Colors.blue,
            secondColor: Colors.yellow,
            onSelectionChanged: (selectedDate){
            print(selectedDate);
            },
          ),
```
## Result

<img width="300" alt="Picker Example" src="https://raw.githubusercontent.com/VladRizea/referenceimages/master/example.jpg">

## Android

The **VIBRATE** permission is required in AndroidManifest.xml.
```XML
<uses-permission android:name="android.permission.VIBRATE"/>
```


## List of proprieties

* onSelectionChanged - what to do when the selection changes
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

## Other combinations
### Horizontal scroll with vertical card
<img width="300" alt="Picker Example" src="https://raw.githubusercontent.com/VladRizea/referenceimages/master/horizontal%20but%20vertical.jpg">

### Horizontal scroll with horizontal card
<img width="300" alt="Picker Example" src="https://raw.githubusercontent.com/VladRizea/referenceimages/master/horizontal%20horizontal.jpg">


