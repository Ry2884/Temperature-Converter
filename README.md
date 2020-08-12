# Temperature-Converter
Codecademy Temperature Converter Project 

//This is just a constant variable named kelvin.//

const kelvin = 300
console.log('The temperature is ' + (kelvin) + ' degrees Kelivn.')

// This converts kelvin to celsius//

const celsius = kelvin - 273;
console.log('The temperature is ' + (celsius) + ' degrees Celsius.')

// This converts celsius to farenheit//

let farenheit = celsius * (9/5) + 32;

//This rounds farenheit down to the nearest whole number//

farenheit = Math.floor(farenheit);
console.log('The temperature is ' + (farenheit) + ' degrees Farenheit.')

//This converts celsius to newton//

let newton = celsius * (33/100);

//This rounds newton down to the nearest whole number.//

newton = Math.floor(newton);
console.log('The temperature is ' + (newton) + ' degrees Newton.')
