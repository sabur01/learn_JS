
## Sozlemin ichinden soz tapyan **programma**
```
function checkSpam(str) {
    let str1= str.toLowerCase(); 
    let sub1='viagra';
    let sub2='xxxxx';
   if(str1.indexOf(sub1) != -1 || str1.indexOf(sub2) != -1){
        return true
   }
    else if(str1.indexOf(sub1)==-1) {
        return false 
    }
}
console.log(checkSpam('buy  agra now'));
console.log(checkSpam('buy ViAgRA now'));
console.log(checkSpam('free xxxxx'));
```
