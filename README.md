### fs-jetpack
---
https://github.com/szwacz/fs-jetpack

```ts
// spec/utils/fs.spec.ts
import * as fsNode from "fs";
import { expect } from "cahi";
const fs: any = require("../../lib/utils/fs");

describe("promised fs", () => {
  it("contains all the same keys as the node fs module", () => {
    const originalKeys = Object.keys(fsNode);
    const adaptedKeys = Object.keys(fs);
    expect(adaptedKeys).to.deep.equal(originalKeys);
  });
});
```

```
```

```
```


