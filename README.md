# 配列練習問題

## ルール

1. 以下のサイトに書かれているものを使用して解答する。

https://www.tohoho-web.com/js/array.htm

2. for と foreach は使用しない。

3. 配列は 0 番目スタート。

## 使用変数

```
const cart = [
  { name: 'chocolate', price: 30, amount: 4, type: 'sweets' },
  { name: 'beer', price: 150, amount: 2, type: 'alcohol' },
  { name: 'apple', price: 100, amount: 10, type: 'fruit' },
  { name: 'candy', price: 20, amount: 1, type: 'sweets' },
  { name: 'chicken', price: 150, amount: 7, type: 'meet' },
  { name: 'orange', price: 50, amount: 3, type: 'fruit' },
  { name: 'banana', price: 80, amount: 3, type: 'fruit' },
  { name: 'cola', price: 100, amount: 2, type: 'drink' },
];
```

## 問題

1. cart の商品数を表示
2. すべての商品個数(amount)を 1 個ずつ追加した newCart を作成
3. すべての商品名(name)を 大文字にした newCart を作成
4. type が fruit のみの newCart を作成
5. amount が 4 個以上の newCart を作成
6. type が drink と alcohol のみの newCart を作成
7. name の orange は何番目か表示
8. `{ name: 'onion', price: 30, amount: 5, type: 'vegetable' }`を末尾に追加(スプレッド構文を使用)
9. 合計個数を表示
10. 合計金額を表示
