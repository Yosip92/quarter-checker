    ##Quarter checker

    A simple project which allows to identify
    coordinate quarter of input 'x' and 'y' values.

    Here is its script:

    ```javascript
    if (isNaN(x) || isNaN(y)) {
        print('Some coordinates was passed with incorrect value!');
    }
    if (x == '' || y == '') {
        print('Some coordinate value is empty');
    }
    else if (x > 0 && y > 0) {
        print('Point is in the first QUARTER!');
    }
    else if (x < 0 && y > 0) {
        print('Point is in the second QUARTER!');
    }
    else if (x < 0 && y < 0) {
        print('Point is in the third QUARTER!');
    }
    else if (x > 0 && y < 0) {
        print('Point is in the fourth QUARTER!');
    }
    else if (x == 0 && y == 0) {
        print('Point is in the beginning of coordinate system!');
    }
    else if (x == 0 && y > 0) {
        print('Point is in the 1st and the 2nd QUARTERS!');
    }
    else if (x == 0 && y < 0) {
        print('Point is in the 3rd and the 4th QUARTERS!');
    }
    else if (x < 0 && y == 0) {
        print('Point is in the 2nd and the 4th QUARTERS!');
    }
    else if (x > 0 && y == 0) {
        print('Point is in the 1st and the 4th QUARTERS!');
    }
    ```

Link on project:
https://yosip92.github.io/quarter-checker/