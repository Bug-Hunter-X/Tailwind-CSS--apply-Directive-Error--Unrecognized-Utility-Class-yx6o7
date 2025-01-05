# Tailwind CSS @apply Directive Error: Unrecognized Utility Class

This repository demonstrates a common error encountered when using Tailwind CSS's `@apply` directive. The error arises when attempting to apply a utility class that is not defined in your Tailwind configuration.

## Problem

The `@apply` directive is a powerful tool for reusing styles, but if you misspell a class name or use a class that hasn't been included in your `tailwind.config.js` file, you'll run into problems. These may manifest as missing styles or build errors.

## Solution

The solution is straightforward.  Ensure the utility class used with `@apply` is correctly spelled and is included in your Tailwind configuration. You might need to regenerate your CSS to reflect changes to your `tailwind.config.js`.

## Reproduction

1. Clone this repository.
2. Run `npm install` (if necessary). 
3. Open `bug.html` to see the error.
4. Compare it to `bugSolution.html` to see the corrected version.

## Contributing

Contributions are welcome!