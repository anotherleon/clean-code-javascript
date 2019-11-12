# clean-code-javascript

## 介绍

## 变量

### 使用有意义和可发音的的变量名字

Bad:

```js
const yyyymmdstr = moment().format("YYYY/MM/DD");
```

Good:

```js
const currentDate = moment().format("YYYY/MM/DD");
```