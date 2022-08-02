//const colors = ['red', 'orange', 'yellow']
//for(var color of colors) {
//  console.log(color);
//}





/* FOR OF LOOP PRACTICE */
/*
const car = {
  engine: true 
}
const sportsCar = Object.create(car) 
  sportsCar.speed = "Fast";
  console.log("the sportsCar object", sportsCar);

  for(prop in sportsCar) {
    console.log('ok', prop);
  }
  for(prop of Object.keys(sportsCar)) {
    console.log('main', prop + ':' + sportsCar[prop]);
  }
*/




/* Maps in Javascript */

/*let bestBoxers = new Map();
bestBoxers.set(1, 'The Best');
bestBoxers.set(2, 'Runner-up');
bestBoxers.set(3, 'Third Place');


console.log(bestBoxers.get(3)); */




/* set method to filter an array for unique members 

const amazingRace = ['swim','run', 'swim', 'jump', 'run', 'bike']
const uniqueRace = new Set(amazingRace);
console.log(uniqueRace);
*/




/* Spread Method-->
let top3 = [
  'The Colosseum',
  'Trevi Fountain',
  'The Vatican City'

]
function showItinerary(place1, place2, place3) {
  console.log('visit' + place1);
  console.log('Then visit' + place2);
  console.log('Finally with a visit to' + place3);
}
showItinerary(top3[0], top3[1], top3[2]);
*/




/*
Rest Operator Practice.


  const top7 = [
    'The Colosseum',
    'The roman Forum',
    'The Vatican',
    'Trevi Fountain',
    'The Pantheon',
    'Piazza Venezia',
    'The Palantine Hill'
  ]
  const [] = top7;
  const [first,second, third, ... secondVisit] = top7;

   
  function addTaxToPrices(taxRate, ...itemsBought){
    return itemsBought.map(item => taxRate * item)
  }
  let shoppingCart = addTaxToPrices(1.1,46,89,35,79);

  console.log(shoppingCart);

  */


/* practicing rest and spread functions */


/* adding objects using the spread method
  const bike =['wheels', 'handles', 'chain']
  const car = ['seat', 'horn']
  const bikeAndCar = [...bike, ...car]
  console.log(bikeAndCar);


  const cats = {legs: 4}
  const dogs = {ears : 2}
  const animal = {...cats, ...dogs}
  console.log(animal)
  
let people = ['legs', 'arms'];
people = [...people, 'mouth', 'ears'];
console.log(people)
*/

/*
more practice with rest and spread methods

const greeting = "Hello";
const arrayOfChars = [...greeting];
console.log(arrayOfChars);

const bike1 = {
  wheels: 4,
  color: 'red'
}
const bike2 = {...bike1}

bike1.wheels = 3

console.log(bike1.wheels, bike2.wheels);

const fruit1 =['apples', 'pears']
const fruit2 = [...fruit1]
fruit1.pop()
console.log(fruit1, 'not', fruit2)

let food = 'chocolate';
console.log(`my favourite food is ${food}`);


let set = new Set();
set.add(1);
set.add(2);
set.add(3);
set.add(2);
set.add(1);
console.log(set);
*/
