## js-faster 🐶

<img src="https://img.shields.io/badge/js--faster-v1.0.1-4CAF50"/> <img src="https://img.shields.io/badge/dayjs-1.11.10-%23EC407A"/> <img src="https://img.shields.io/badge/lodash-4.17.21-orange"/>

### Cách cài đặt

```
npm i js-faster
```

or

```
yarn add js-faster
```

## Cách sử dụng

- English document: [VIEW ENGLISH](https://github.com/chaudev/js-faster)

- Tài liệu tiếng việt: [XEM BẰNG TIẾNG VIỆT](https://github.com/chaudev/js-faster#vi-readme)

### 1. `formatDateString`

Định dạng một đối tượng Date thành chuỗi ngày (DD/MM/YYYY).

```javascript
const formattedDate = formatDateString(new Date());
// Kết quả: 09/01/2024
```

### 2. `formatDateTimeString`

Định dạng một đối tượng Date thành chuỗi thời gian và ngày (HH:mm DD/MM/YYYY).

```javascript
const formattedDateTime = formatDateTimeString(new Date());
// Kết quả: 16:46 09/01/2024
```

### 3. `formatNumberWithCommas`

Chuyển đổi một số nguyên thành một chuỗi có định dạng được phân tách bằng dấu phẩy.

```javascript
const formattedNumber = formatNumberWithCommas(1000000);
// Kết quả: 1,000,000
```

### 4. `parseFormattedNumber`

Chuyển đổi một chuỗi có chứa dấu phẩy thành một số nguyên.

```javascript
const parsedNumber = parseFormattedNumber("1,000,000");
// Kết quả: 1000000
```

### 5. `toUpperCase`

Chuyển đổi một chuỗi thành chữ in hoa.

```javascript
const upperCaseString = toUpperCase("hello world");
// Kết quả: HELLO WORLD
```

### 6. `toLowerCase`

Chuyển đổi một chuỗi thành chữ thường.

```javascript
const lowerCaseString = toLowerCase("Hello World");
// Kết quả: hello world
```

### 7. `arrayToStringWithCommas`

Chuyển đổi một mảng thành một chuỗi, nối các phần tử bằng dấu phẩy.

```javascript
const stringFromArray = arrayToStringWithCommas([1, 2, 3]);
// Kết quả: 1,2,3
```

### 8. `parseStringToArray`

Chuyển đổi một chuỗi được phân tách bằng dấu phẩy thành một mảng số nguyên.

```javascript
const arrayFromString = parseStringToArray("1,2,3");
// Kết quả: [1, 2, 3]
```

### 9. `isInteger`

Kiểm tra xem một giá trị có phải là số nguyên hay không.

```javascript
const result = isInteger(42);
// Kết quả: true
```

```javascript
const result = isInteger("42");
// Kết quả: false
```

### 10. `getRandomNumberInRange`

Tạo ra một số ngẫu nhiên trong khoảng được chỉ định.

```javascript
const randomNum = getRandomNumberInRange(1, 100);
// Kết quả: [Random number between 1 and 100]
```

### 11. `isArray`

Kiểm tra xem một giá trị có phải là mảng hay không.

```javascript
const result = isArray([1, 2, 3]);
// Kết quả: true
```

```javascript
const result = isArray(1);
// Kết quả: false
```

### 12. `sortAscending`

Sắp xếp một mảng theo thứ tự tăng dần.

```javascript
const sortedArray = sortAscending([3, 1, 2]);
// Kết quả: [1, 2, 3]
```

### 13. `sortDescending`

Sắp xếp một mảng theo thứ tự giảm dần.

```javascript
const sortedArray = sortDescending([3, 1, 2]);
// Kết quả: [3, 2, 1]
```

### 14. `containsNumber`

Kiểm tra xem một chuỗi có chứa ký tự số hay không.

```javascript
const result = containsNumber("Hello123");
// Kết quả: true
```

## Thông tin liên hệ

### NGUYỄN PHÚC BẢO CHÂU

- Website: https://ischau.org
- Website 2: https://dovuihainao.com
- Website 3: https://thatthuvi.com/react-practical
- Telegram: https://t.me/baochau9xx
- Facebook: https://facebook.com/baochau9xx
- Mail: chau.02it@gmail.com

### Từ khoá

baochau9xx, green, js-faster, react-practical, react tools, react-native, native, baochau, thatthuvi
