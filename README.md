## Issue

babel-eslint seems to ignore no-unused-vars on 3.1.10 and 3.1.11, but not on 
3.1.9.

## To Reproduce

1.  Clone this repository.

2.  Run `npm install`

3.  Run eslint with `./node_modules/.bin/eslint testcase.js`

4.  Observe the error message:

    ```
    1:4  error  unused is defined but never used  no-unused-vars
    ```

5.  Modify package.json to use 3.1.10 or 3.1.11, rinse-and-repeat.
