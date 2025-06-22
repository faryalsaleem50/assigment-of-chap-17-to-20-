# assigment-of-chap-17-to-20-
    question no 1
// multideminsial array 

let emptyarray =[[], [], []];
console.log("empty multideminsial array:");
console.log(emptyarray)

    question no 2
    const matrix=[
[1, 2, 3],
[4, 5, 6],
[7, 8, 9],
];

for(let i=0; i <matrix.length; i++){ 
  for(let j=0; j <matrix[i].length;j++) {
  console.log(`Element at row ${i}, column ${j}: ${matrix[i][j]}`)
}}

  
         question no 3
// Print numeric counting from 1 to 10,

for (let i = 1; i <= 10; i++) {
  console.log(i);
}


     question no 4
// Take table number input from user
let tableNum = +prompt("Enter a number to show its multiplication table");

// Take table length input from user
let tableLength = +prompt("Enter length of multiplication table");

// Print the table using for loop
for (let i = 1; i <= tableLength; i++) {
  console.log(`${tableNum} x ${i} = ${tableNum * i}`);
}

           question no 5
  let fruits = ["apple", "banana", "mango", "orange", "strawberry"];

for (let i = 0; i < fruits.length; i++) {
  console.log("Element at index " + i + " is " + fruits[i]);
}

question no 6 (c,d)
  //  EVEN ODD

document.write("even/odd");
for (let i=1;i<=20;i++){
    if(i%2==0){
        console.log(i+"even/odd");
    }else{
        console.log(i+"/odd")
    }
}
Q6(B)
For(let ;=20; i <1, 1--)
{console.log(i):
};
Q6(A)
for (let i = 1; i <= 15; i++) {
  console.log(i);
}

         QUESTION NO 7
 var A=["CAKE","PATTIES"];
user=prompt("enter item");
ans=A.includes(user);
console.log(ans);
if(ans===true){
  console.log("the itemispresent")
}
else{
  console.log("no item")
}

     question no 8

let A = [24, 53, 78, 91, 12];
let largest = A[0]; // assume the first number is the largest

for (let i = 1; i < A.length; i++) {
  if (A[i] > largest) {
    largest = A[i];
  }
}
console.log("The largest number is: " + largest);

     QUESTION NO 9

let A = [24, 53, 78, 91, 12];
let smallest = A[0]; // assume the first number is the smallest

for (let i = 1; i < A.length; i++) {
  if (A[i] < smallest) {
    smallest = A[i];
  }
}

console.log("The smallest number is: " + smallest);

        QUESTION NO 10


for (let i = 1; i <= 100; i++) {
  if (i % 5 === 0) {
    console.log(i);
  }
}













   





