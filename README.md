## Usage
1. Add [dart_code_metrics](https://pub.dev/packages/dart_code_metrics)'s latest version to your `pubspec.yaml`'s `dev_dependencies`.
2. Create (if does not exist) `analysis_options.yaml`.
3. Depending on your type of project (pure `dart` or `flutter`) copy the content of [dart_analysis_options.yaml](./dart_analysis_options.yaml) or [flutter_analysis_options.yaml](./flutter_analysis_options.yaml) to your porject's `analysis_options.yaml`.
4. Run from the root directory of your project:
```dart
flutter pub get
```