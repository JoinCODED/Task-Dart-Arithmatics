1. You main method should look like this:

```dart
void main() {
  double tempInFahrenheit = 86;
}
```

2. Create another variable of type double and name of `tempInCelsius`:

```dart
void main() {
  double tempInFahrenheit = 86;
  double tempInCelsius = 0.0;
}
```

3. Start applying the formula:

```dart
void main() {
  double tempInFahrenheit = 86;
  double tempInCelsius = (tempInFahrenheit - 32) / 1.8;
}
```

4. Print out the result:

```dart
void main() {
  double tempInFahrenheit = 86;
  double tempInCelsius = (tempInFahrenheit - 32) / 1.8;
  print('${tempInFahrenheit}F = ${tempInCelsius}C');
}
```

### 🍋 Floats Methods

To show only 1 fractional digit we will use `toStringAsFixed()` method by passing it the number of fractional digits we want:

```dart
void main() {
  double tempInFahrenheit = 86;
  double tempInCelsius = (tempInFahrenheit - 32) / 1.8;
  print('${tempInFahrenheit}F = ${tempInCelsius.toStringAsFixed(1)}C');
}
```

### 🌶 Vice Versa

```dart
void main() {
  double tempInCelsius = 26;
  double tempInFahrenheit = tempInCelsius * 1.8 + 32;
  print('${tempInFahrenheit.toStringAsFixed(1)}F = ${tempInCelsius}C');
}
```
