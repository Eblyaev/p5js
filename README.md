# p5js
## Функции
```C++
function greet(name) {
  console.log("Hello," + name); //print()
  }
greet(" Sweety"); // без вызова функция не вызывается, вызов функции
greet(" Woman");

function greet(A, B) {
  console.log(A + B);
}
greet(4,3);

let ages = [21, 19, 20, 23];
  console.log(ages);


function age(){
  let sum = 0;
  for (let i = 0; i < ages.length; i++) {
  
  sum = sum + ages[i];
}

  console.log(sum/ages.length);
}
age();

let N1 = [21, 19, 20, 23];
let N2 = [55, 60, 78, 45];
  console.log(N1);
  console.log(N2);


function age(ages){
  let sum = 0;
  for (let i = 0; i < ages.length; i++) {
  
  sum = sum + ages[i];
}

  console.log(sum/ages.length);
}
age(N1);
age(N2);

let N1 = [21, 19, 20, 23];
let squared = [21*21, 19*19, 20*20, 23*23];
 console.log(squared);
//let NA = [];
//NA.push (squared[0]);
//NA.push (squared[1]);
//NA.push (squared[2]);
//NA.push (squared[3]);
// console.log(NA);
  
function age(ages){
  let sum = 0;
  for (let i = 0; i < ages.length; i++) {
  
  sum = sum + ages[i];
}
  console.log(sum/ages.length);
    return sum; //возвращается из вывода значения
}
let ag = age(squared); //сохраняется
```
