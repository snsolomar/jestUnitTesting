# jestUnitTesting

## Install

- npm init -y
- npm i --save-dev jest (saved as development dependencies because we only use it in development environments)

## How to use

- npm test

## Difference between toBe() and toEqual()

- toBe(): This matcher is used to check for strict equality between two values. It uses the === operator to compare the values, which means the values must be of the same type and have the same value to pass the assertion.

- toEqual(): This matcher is used to perform a deep equality check between two values. It recursively checks the properties and values of objects and arrays to ensure they are equal, rather than checking for reference equality. It is more flexible than toBe() as it allows comparing complex data structures
