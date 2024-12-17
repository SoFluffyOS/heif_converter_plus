# HEIF Converter

#### Original package: [heif_converter](https://pub.dev/packages/heif_converter)

Flutter plugin to convert HEIC/HEIF file to PNG/JPEG image.

## Installation

Add the Package

```yaml
dependencies:
  heif_converter: ^lastVersion
```

## How to use

Import the package in your dart file

```dart
import 'package:heif_converter/heif_converter.dart';
```

And call convert method with local HEIC/HEIF image file path.

```dart
String jpgPath = await HeifConverter.convert(heicPath, output: jpgPath);
String pngPath = await HeifConverter.convert(heicPath, format: 'png');
```
