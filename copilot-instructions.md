## typescript coding style guide

Use the JIRA ticket number in the beginning of the branch name, in the beginning of each commit and in the beginning of the PR headline.

Use absolute addressing instead of relative except for enums. Like this '@domain/inventory/types' instead of '../../../types' you can find it inside package.json file.

Use .prettierrc formatter as source of formatting.

Always assign type for the functions.

If possible for util functions use lodash library or /lendis-tech/shared-library repo.

Use google style https://google.github.io/styleguide/tsguide.html

If possible create Jest test file along side of your change.

For existing models create centralized mock functions alongside the model file with the suffix ".mock.ts". 

Always provide comments for hard-to-explain codes. skip easy code explaining.

Prefer async/await over promise chains for asynchronous code.

Use Types instead of Interfaces for object shapes.

Use enums instead of union types for static value definitions. 

Name variables and functions descriptively; avoid single-letter names.

Keep functions small and focused—prefer single responsibility.

Avoid using "any" type; always strive for strict typing.

When adding new dependencies, update package.json and run `npm install` or `yarn install`.

Write meaningful commit messages following the Conventional Commits specification.

Do not delete package.json, package-lock.json or yarn.lock files; they are essential for dependency management.

Before each commit execute "npm run tsc" & "npm run lint" and fix issues when reported.
