[![返回目录](https://parg.co/US3)](https://parg.co/UGZ)

# MobX

## 术语介绍

```js
var numbers = observable([1, 2, 3]);
var sum = computed(() => numbers.reduce((a, b) => a + b, 0));

var disposer = autorun(() => console.log(sum.get()));
// 打印 '6'
numbers.push(4);
// 打印 '10'

disposer();
numbers.push(5);
// 此时并不会打印出任何对象
```

## 可观测类型

## 理解 MobX 的监听对象
