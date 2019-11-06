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
