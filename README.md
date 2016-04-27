var persons={
 Ruth:{
 firstName:"Ruth",
 name:"Ruth Obeng",
 age:"32",
 street:"Kasoano",
 country:"Ghana",
 city:"Soanocity"
 },
  Lawrence:{
 firstName:"Lawrence",
 name:"Lawrence Tetteh",
 age:"27",
 street:"Kasaco",
 country:"Ghana",
 city:"Kasacity"
 },
  Love:{
 firstName:"Love",
 name:"Love Kese",
 age:"30",
 street:"Tema",
 country:"Ghana",
 city:"Temacity"
 },
  Pamela:{
 firstName:"Pamela",
 name:"Pamela Obeng",
 age:"28",
 street:"Kaso",
 country:"Ghana",
 city:"Kasity"
 },
  Richmond:{
 firstName:"Rich",
 name:"Richmond Obeng",
 age:"25",
 street:"Tutu",
 country:"Ghana",
 city:"Turucity"
 },
  Jedidiah:{
 firstName:"Jedidiah",
 name:"Jedidiah Obeng",
 age:"29",
 street:"Kumawu",
 country:"Ghana",
 city:"Kumacity"
 },
  Abedi:{
 firstName:"Abedi",
 name:"Abedi Richmond",
 age:"26",
 street:"Adukrom",
 country:"Ghana",
 city:"Aducity"
 },
  Prince:{
 firstName:"Prince",
 name:"Prince Obeng",
 age:"22",
 street:"Ash ville",
 country:"Ghana",
 city:"Akropong"
 },
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
 
