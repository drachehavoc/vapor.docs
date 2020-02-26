```TypeScript

import { MySQL } from "vapor/driver/mysql";
import { Schema } from "vapor/schema";

const driver = new MySQL();
const schema = new Schema(`schema name`, driver);

```