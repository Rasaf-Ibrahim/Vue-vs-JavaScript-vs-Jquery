## Explanation



```js
 data() {
        return {
          item: undefined
        }
}
```



At first, 'item' is undefined. 



```html
  <div @click="item = 1" :class="{active:item == 1}">
    Home
  </div>

  <div @click="item = 2" :class="{active:item == 2}">
    About
  </div>
```



When you click Home, item becomes '1' and Home gets  the class 'active'  as 'item == 1' becomes true. 

In  the same way, when you click 'About', item becomes '2' and About gets the class 'active' as 'item ==2' becomes true. 

