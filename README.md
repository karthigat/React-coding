#classes:

class human{
 
gender = 'male';
  
  printgender=()=>{
    console.log(gender);
  }
}

class person extends human{

    name='karthiga';
    gender='female';
  }
  printmyname=()=>{
    console.log(name);
  }
}

const Person = new person();
Person.printmyname();
Person.printgender();

# spread and rest:

const number=[1,2,3];
const numbers=[...number,4];
console.log(numbers);

const person={
  name:'karthiga'
};

const newperson={
  ...person,
  age:28
}

console.log(newperson);

const filter = (...args)=>{
  return args.filter(el => el ===1 )
}

console.log(filter(1,2,3));
