# 1.1.0

- *Incompatible change*: you no longer use `.ns` on export lines, instead you
  get the exported namespace object directly. As a result, you also can no
  longer export a name of `_bridge`.

# 1.0.2

- First release as forked _eximport_
- Support doublequotes (`"`) on import lines
- Support backquotes (```) on import lines
- Support exporting multiple names in one statement (`export {A, B}`)
- Support `as` on import (`import {A as _A} ...`)
- Support `import *`
- Support `import "foo"` (side-effect only)
- Support `export {A, B} from "foo"`
- Support exporting multiple names in `export var` and similar
- Avoid adding any export code if no exports have been found
- Reorganised export work into a single bridge object (`eximport-bridge`)
- Added basic validation of exported names
- Improved support for quotes

# 1.0.0 - 1.0.1

- Earlier releases (of _import-export_)...