[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)
[![pub package](https://img.shields.io/pub/v/june_lego.svg)](https://pub.dartlang.org/packages/june_lego)

# june_lego
lego that template for june state management

##  Installation
1. If the lego project doesn't exist, please create new project by following [guide](https://lego.junestory.com/).
2. open terminal in the lego project root directory, enter the following command.
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
