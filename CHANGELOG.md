# 1.12.2

 * Upgrade `matcha` to `0.6.0` and `browserify` to `6.3.2`.
 * Add own `trimRight` helper instead of relying on the string instance method.
 * Support JSX spreads that aren't the first.

# 1.12.1

 * Fix `this` and `arguments` mapping in the `_aliasFunctions` transformer.

# 1.12.0

 * Combine `jsx` and `react` transformers to `react`.
 * Update `react` syntax output to React v0.12.

# 1.11.15

 * Fix JSX literal whitespace generation.

# 1.11.14

 * Avoid using a switch for let-scoping continue and break statements and use an if statement instead.
 * Remove excess whitespace and newlines from JSX literals.

# 1.11.13

 * Update regenerator-6to5
 * Add support for most escodegen formatting options
