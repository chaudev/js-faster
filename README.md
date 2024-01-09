## js-faster 🐶

<img src="https://img.shields.io/badge/js--faster-v1.0.1-4CAF50"/> <img src="https://img.shields.io/badge/dayjs-1.11.10-%23EC407A"/> <img src="https://img.shields.io/badge/lodash-4.17.21-orange"/>

### Intall

```
npm i js-faster
```

or

```
yarn add js-faster
```

- English document: [VIEW ENGLISH](https://github.com/chaudev/js-faster)

- Tài liệu tiếng việt: [XEM BẰNG TIẾNG VIỆT](https://github.com/chaudev/js-faster/blob/main/vi-readme.md)

## How to use

### 1. `formatDateString`

Formats a Date object into a date string (DD/MM/YYYY).

```javascript
const formattedDate = formatDateString(new Date());
// Result: 09/01/2024
```

### 2. `formatDateTimeString`

Formats a Date object into a time and date string (HH:mm DD/MM/YYYY).

```javascript
const formattedDateTime = formatDateTimeString(new Date());
// Result: 16:46 09/01/2024
```

### 3. `formatNumberWithCommas`

Converts an integer to a string with comma-separated format.

```javascript
const formattedNumber = formatNumberWithCommas(1000000);
// Result: 1,000,000
```

### 4. `parseFormattedNumber`

Converts a string with commas to an integer.

```javascript
const parsedNumber = parseFormattedNumber("1,000,000");
// Result: 1000000
```

### 5. `toUpperCase`

Converts a string to uppercase.

```javascript
const upperCaseString = toUpperCase("hello world");
// Result: HELLO WORLD
```

### 6. `toLowerCase`

Converts a string to lowercase.

```javascript
const lowerCaseString = toLowerCase("Hello World");
// Result: hello world
```

### 7. `arrayToStringWithCommas`

Converts an array to a string, joining elements with commas.

```javascript
const stringFromArray = arrayToStringWithCommas([1, 2, 3]);
// Result: 1,2,3
```

### 8. `parseStringToArray`

Converts a comma-separated string to an array of integers.

```javascript
const arrayFromString = parseStringToArray("1,2,3");
// Result: [1, 2, 3]
```

### 9. `isInteger`

Checks if a value is an integer.

```javascript
const result = isInteger(42);
// Result: true
```

```javascript
const result = isInteger("42");
// Result: false
```

### 10. `getRandomNumberInRange`

Generates a random number within a specified range.

```javascript
const randomNum = getRandomNumberInRange(1, 100);
// Result: [Random number between 1 and 100]
```

### 11. `isArray`

Checks if a value is an array.

```javascript
const result = isArray([1, 2, 3]);
// Result: true
```

```javascript
const result = isArray(1);
// Result: false
```

### 12. `sortAscending`

Sorts an array in ascending order.

```javascript
const sortedArray = sortAscending([3, 1, 2]);
// Result: [1, 2, 3]
```

### 13. `sortDescending`

Sorts an array in descending order.

```javascript
const sortedArray = sortDescending([3, 1, 2]);
// Result: [3, 2, 1]
```

### 14. `containsNumber`

Checks if a string contains a numeric character.

```javascript
const result = containsNumber("Hello123");
// Result: true
```

## Contact

### NGUYEN PHUC BAO CHAU

- Website: https://ischau.org
- Website 2: https://dovuihainao.com
- Website 3: https://thatthuvi.com/react-practical
- Telegram: https://t.me/baochau9xx
- Facebook: https://facebook.com/baochau9xx
- Mail: chau.02it@gmail.com

### Keyword

baochau9xx, green, js-faster, react-practical, react tools, react-native, native, baochau, thatthuvi
