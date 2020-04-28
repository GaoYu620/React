##Java script basic

##1. function
const mutiply = (number)=> {
    return  number *2;
}

console.log(mutiply(2));

## other way
const mutiply = (number)=>   number *2;


##2. imports & exports(modules)
//person.js

const person = {
     name : "max"
}

export default person


//utility.js

export const clean = () => {}
export database = 10;

//app.js

import person from './person.js'
import prs from './person.js'


import {database} from './utility.js'
import{clean} from './utility.js'

//default export
import person from './person.js'
import prs from './person.js'


//named export
import {smth} from './utility.js'
import{smth as Smth} from './utility.js'
import * as bundled from './utility.js'

##3. classes

class Person{
  constructor(){
    this.name = "max";
  }
  
  printName(){
    console.log(this.name);
  }
}

const person = new Person();
person.printName();


##inherantence

class Human{
  
  constructor(){
    this.gender = "male";

  }
  
  printGender(){
    console.log(this.gender);
  }
}

class Person extends Human{
  constructor(){
    super();
    this.name = "max";
    this.gender = "female";
  }
  
  printName(){
    console.log(this.name);
  }
}


const person = new Person();
person.printName();
person.printGender();






