## typescript coding style guide

Use absolute addressing instead of relative.use this '@domain/inventory/types' instead of '../../../types' you can find it inside package.json file.

use .prettierrc formatter as source of formatting.

Always assign type for the functions

If possible for util functions use lodash library or /lendis-tech/shared-library repo.

Use google style https://google.github.io/styleguide/tsguide.html

If possible create Jest test file along side of your change.

always provide comments for hard-to-explain codes. skip easy code explaining.

Prefer async/await over promise chains for asynchronous code.

Use interfaces instead of types for object shapes unless a union or intersection is required.

Name variables and functions descriptively; avoid single-letter names

Keep functions small and focused—prefer single responsibility.

Avoid using "any" type; always strive for strict typing.

When adding new dependencies, update package.json and run `npm install` or `yarn install`.

Write meaningful commit messages following the Conventional Commits specification.
