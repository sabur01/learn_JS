## 1-mesele textyn uzynlygy 
```
let s = 'hello';
console.log(s.length);
```
## 2-mesele  simwoly coda gecyan programma
```
let str = ' space ';
let k = 0;
for (let i = 0; i < str.length; i++) {
    if((str[i].codePointAt(0) >= 65 && str[i].codePointAt(0) <= 90) || (str[i].codePointAt(0) >= 97 && str[i].codePointAt(0) <= 122)){
        continue; 
    }
    else{
        k++
    }
}console.log(k);
```
