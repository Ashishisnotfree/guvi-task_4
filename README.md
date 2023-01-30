# guvi-task_4



#1 function isEqual(json1, json2) {
  let string1 = JSON.stringify(obj1, Object.keys(obj1).sort());
  let string2 = JSON.stringify(obj2, Object.keys(obj2).sort());

  return string1 === string2;
}

let obj1 = { name: "Person1", age:5,  };
let obj2 = { age: 5,  name: "Person1" };

console.log(isEqual(obj1, obj2)); // outputs: true
