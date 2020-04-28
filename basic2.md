##ES6/Bael  next generation java script



class Human{
    gender = "male";
  
  printGender(){
    console.log(this.gender);
  }
}

class Person extends Human{

    name = "max";
    gender = "female";
 
  printName(){
    console.log(this.name);
  }
}

const person = new Person();
person.printName();
person.printGender();


## spread operator/ array

const number = [1,2,3];
const newNumber = [...number,4];
console.log(newNumber); //[1,2,3,4]

## spread operator/ object

const person = {
  name:'Max'
};

const newPerson = {
  ...person,
  age:28
};

console.log(newPerson);

## rest
const filter = (...args) =>{
  return args.filter(el => el === 1);
}
console.log(filter(1,2,3)) //[1



 const numbers = [1,2,3];
[number1,number2] = numbers;
console.log(number1,number2)//[1,2]]


 const numbers = [1,2,3];
[number1, ,number3] = numbers;
console.log(number1,number3) //[1,3]

## array functions
 const numbers = [1,2,3];
 const doubleNumbers = numbers.map((nums) => {
   return nums*2;
 })
 
 console.log(numbers);//[1,2,3]
 console.log(doubleNumbers);[2,4,6]



