## dargon2_core

This library generally should not be used in most contexts

This library is an umbrella library that  contains all method bindings for dargon2 and dargon2_flutter.

This library uses a given library (by dargon2 or dargon2_flutter) to create the bindings between Dart and argon2's C library. If you're using this library directly, you'll need to supply a LibLoader conforming to the class

## Usage

A simple usage example:

```dart
import 'package:dargon2_core/dargon2_core.dart';

main() {
  var awesome = new Awesome();
}
```

## Features and bugs

Please file feature requests and bugs at the [issue tracker].

[issue tracker]: https://github.com/tmthecoder/dargon2_core/issues
