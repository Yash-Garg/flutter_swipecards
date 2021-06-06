# flutter_swipecards

Tinder/TanTan Card Widget.

## Screenshots

![screenshot](./assets/example_swipecards.gif)

## Getting Started

1. Depend on it by adding this to your pubspec.yaml file: `flutter_swipecards: ^x.x.x`

2. Import it: `import 'package:flutter_swipecards.dart'`

3. Add TinderSwapCard in your widget layout and write the single card layout builder you need, then you get a Tinder(探探) like swap card widget!

4. Use `CardSwipeCompleteCallback` for the swiped orientation and index!

5. Use `CardController` to trigger swap from outside. Init a CardController as param for widget, and invoke method `triggerLeft/Right` of your `CardController` to trigger swipe!

6. Use `CardDragUpdateCallback` to get swiping card's detail.

## Example

[See Here](./example/example/lib)

## Async Example

[See Here](./example/async_data/lib)
