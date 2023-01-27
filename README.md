const kelvin = 0;
// the forecast today is 293 degrees in kelvin weather
const celsius = kelvin - 273;
// celsius degree are 273 degrees less than kelvin, that way, we can find the degree in celsius by subtracting 273 degrees from kelvin
let farenheit = celsius * (9 / 5) + 32;
// thats the way that we calculate the farenheit degree
farenheit = Math.floor(farenheit);
//we use the method floor to round down the farenheit value
let newton = celsius * (33 / 100);
newton = Math.floor(newton);

console.log(
  `The temperature is ${farenheit} degrees Fahrenheit,${kelvin} in kelvin, ${celsius} in celsius and ${newton} in newton scale 8D`
);
