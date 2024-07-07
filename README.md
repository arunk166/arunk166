FED ST - 1


ANS - 1  (b) using <link> tag
ANS - 2   (b) using p tag
ANS - 3   (b) false
ANS - 4   (b) false
ANS - 5   (c) 10000000000
ANS - 6    (a)	Output array : ['John', 'Jane', 'Bob']:
        const names = people.map(person => person.name);
	      console.log(names);
   (b)	Output array :
        [{ "id":1,"name":"John","age":30,"salary":50000},
        {"id": 2,"name": "Jane","age": 25,"salary": 50000},
        {"id": 3,"name": "Bob","age": 40,"salary": 50000}]:
        const updatedPeople = people.map(person => ({...person,salary: 50000}));
	      console.log(updatedPeople);
   (c)	const filteredPeople = people.filter(person => person.age > 30).map(person => ({name: person.name,age: person.age}));
	      console.log(filteredPeople);


ANS - 7   function cb1(x, y) {
    return x + y;
   }

   function cb2(x, y) {
    return x - y;
   }

   function main(cb1, cb2, x, y) {
    console.log("Sum of x and y:", cb1(x, y));
    console.log("Difference of x and y:", cb2(x, y));
   }
ANS - 8  (c)map function
ANS - 9 
ANS - 10 (C)[]
ANS - 11  (B) display : none removes the element from the dom while visibility : hidden just hides the element.
ANS - 12  (A) 4 10 18
ANS - 13 (A) [1,2,3,4]
