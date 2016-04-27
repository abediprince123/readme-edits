var persons={
Kwame:{
	firstName:"Kwame",
name: "Kwame Nkasa",
 age:"16",
 street: "2009",
 country:"United States of America",
 city:"Ohio"
 },
 Gifty:{
	 firstName:"Gifty",
	 name:"Gifty Obeng",
 age:"22",
 street:"Kasoa",
 country:"Ghana",
 city:"Obosomanse"
 }
 };
 var search=prompt("Whose information are you looking for");
 var goThru=function(search){
 for(var i in persons){
if(search===persons[i].firstName){
	console.log(search+"'s full name is  "+persons[i].name);
 console.log(search+"'s age is:  " +persons[i].age);
 console.log(search+" stays at a street called:  " +persons[i].street);
 console.log(search+" is at a country called:  " +persons[i].country);
 console.log(search+" is at a street called:  " +persons[i].street);
 }
 else{
 console.log(search +" cannot be found sorry!!");
 }
 }
 };
 goThru(search);
 
