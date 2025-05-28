## typescript coding style guide

Use absolute addressing instead of relative. You can find it inside package.json file.

import { Inventory, WarehouseNotification } from '../../../../inventory/types'

import { Inventory, WarehouseNotification } from '@domain/inventory/types'

use .prettierrc formatter as source of formatting.

Always assign type for the functions

If possible for util functions use lodash library or /lendis-tech/shared-library repo.

Use google style https://google.github.io/styleguide/tsguide.html

If possible create Jest test file along side of your change.

always provide comments for hard-to-explain codes. skip easy code explaining.
