# Ofrades -> eslint and prettier setup

## Do
  - Lints JavaScript code smells
  - Prettify code not matter your editor
  - Warns about not following prettier rules
  - When prettier rules apply eslint rules are disabled

## package
### eslint-config-airbnb
The most used eslint configuration.

### eslint-config-prettier
Turns off all ESLint rules that have the potential to interfere with Prettier rules.

### eslint-plugin-prettier
Turns Prettier rules into ESLint rules.

## eslintrc extends
### airbnb
### prettier

### plugin:prettier/recommended
Enables eslint-plugin-prettier and eslint-config-prettier. This will display prettier errors as ESLint errors.
Make sure this is always the last configuration in the extends array.

## To do
  - Setup for TypeScript

## Install
  1. After the project is set with `npm init` 
  2. Intall with `npx install-peerdeps --dev eslint-config-ofrades`

