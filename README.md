# Neat Design System Base

## Running the Project

1. Run `yarn install` to install dependencies.

2. To modify any color, edit `colors.tokens.json` and then run `yarn style-dictionary build` to generate the updated output files.

## Installation

1. First, generate a [GitHub token](https://github.com/settings/tokens) with `read:packages` permissions.

2. Then, install the package with:

    ```bash
    yarn add git+https://<TOKEN>@github.com/Neat-Pagos/neat-design-system-base.git
    ```

    or

    ```bash
    npm install git+https://<TOKEN>@github.com/Neat-Pagos/neat-design-system-base.git
    ```

## Usage

### Using with JavaScript

Example:

```javascript
import { Primary5 } from 'neat-design-system-base';

console.log(Primary5);
```

For a list of all available JavaScript variables, refer to the colors.js file in this repository.


## Using with SCSS

```CSS
@import '~neat-design-system-base/build/css/colors.scss';

.btn {
  background: $primary-5;
}
```
For a list of all available SCSS variables, refer to the colors.scss file in this repository.


