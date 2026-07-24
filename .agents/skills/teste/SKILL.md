```markdown
# teste Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill introduces the core development patterns and conventions used in the `teste` JavaScript repository. It covers file naming, import/export styles, commit practices, and testing approaches to ensure consistency and maintainability across the codebase.

## Coding Conventions

### File Naming
- Use **camelCase** for filenames.
  - Example: `myComponent.js`, `userProfile.test.js`

### Import Style
- Use **relative imports** for modules within the project.
  ```javascript
  import { myFunction } from './utils';
  ```

### Export Style
- Use **named exports** for functions, constants, and objects.
  ```javascript
  // utils.js
  export function myFunction() { ... }
  export const MY_CONSTANT = 42;
  ```

### Commit Patterns
- Commit messages are **freeform** and often start with a prefix, with an average length of 40 characters.
  - Example: `fix login bug on userProfile page`

## Workflows

### Adding a New Module
**Trigger:** When you need to add new functionality as a separate file or component  
**Command:** `/add-module`

1. Create a new file using camelCase naming (e.g., `newFeature.js`).
2. Implement your functionality.
3. Export your functions or constants using named exports.
   ```javascript
   export function newFeature() { ... }
   ```
4. Import your module where needed using a relative path.
   ```javascript
   import { newFeature } from './newFeature';
   ```
5. Write corresponding tests in a file named `newFeature.test.js`.

### Writing and Running Tests
**Trigger:** When you add or update code and need to ensure correctness  
**Command:** `/run-tests`

1. Create a test file with the pattern `*.test.js` (e.g., `userProfile.test.js`).
2. Write your test cases using the project's preferred (unknown) test framework.
3. Run the test suite using the appropriate command for your environment (e.g., `npm test` or similar).

### Making a Commit
**Trigger:** After making changes that are ready to be saved in version control  
**Command:** `/commit-changes`

1. Stage your changes.
2. Write a concise, descriptive commit message (around 40 characters).
   - Example: `add validation to registration form`
3. Commit your changes.

## Testing Patterns

- Test files are named using the pattern `*.test.js`.
- The specific test framework is **unknown**, but tests should be colocated with the corresponding module or in a dedicated test directory.
- Example test file:
  ```javascript
  // userProfile.test.js
  import { getUserName } from './userProfile';

  test('returns correct user name', () => {
    expect(getUserName({ name: 'Alice' })).toBe('Alice');
  });
  ```

## Commands
| Command         | Purpose                                      |
|-----------------|----------------------------------------------|
| /add-module     | Scaffold and integrate a new module          |
| /run-tests      | Run all test files matching `*.test.js`      |
| /commit-changes | Stage and commit changes with a good message |
```
