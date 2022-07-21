# core-code-upskilling-readme-JimmyArango
Core-Code

# Smallest Integer In Array

```
function minorNumber(array) {
  let number = array[0];
  for (let i = 0; i < array.length; i++) {
    if(array[i]<number){
      number = array[i]
    }
  }
  console.log(number);
}
```
