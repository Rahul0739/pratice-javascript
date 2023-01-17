### Javascript Practice Questions

#### 1. Check the frequency of the elements of the array.
```
let arr = ["hello", "hello", "world", "check", "world"];

function frequency(arr) {
    let check = {}
    arr.forEach(item => {
        if(!check[item]) {
            check[item] = 1;
        }
        else {
            check[item]++;
        }
    })
    return check;
}

console.log(frequency(arr))
```
