[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)
[![pub package](https://img.shields.io/pub/v/june_lego.svg)](https://pub.dartlang.org/packages/june_lego)

# june_lego
lego that template for june state management

##  Installation
1. open terminal in the lego project root directory, enter the following command for install cli.
   and create a new lego project if you don't have one.
```bash
flutter pub global activate lego_cli
lego create
```
2. in terminal, enter the following command for add lego to project.
 ```bash
 lego add june_lego
 ```

## Usage
```dart
import 'package:june/june.dart';

import '../../../../../../../../../../../main.dart';

class NewVM extends JuneState {
  // int count = 0;

  // someAction() {
  //   count++;
  //   setState();
  // }
}

/* usage
JuneBuilder(
  () => NewVM(),
  builder: (vmNew) => widget
)
 */
```
