# JavaScript

Insert script into the bottom of the body: <script src="#JavaFileName.js"></script>

STUB out sections for easy identification

NOTE helpful info
.queryselector grabs information from the DOM similarlly to .getelementbyid but instead of ID you use anything like a class or element.
setInterval( #what to do, #how often)

alert?? use a sweet alert 2 toast

const Toast = Swal.mixin({
  toast: true,
  position: 'top-end',
  showConfirmButton: false,
  timer: 3000,
  timerProgressBar: true,
  didOpen: (toast) => {
    toast.addEventListener('mouseenter', Swal.stopTimer)
    toast.addEventListener('mouseleave', Swal.resumeTimer)
  }
})

Toast.fire({
  icon: 'success',
  title: 'Signed in successfully'
})

//SECTION Data Types

//Primative (value type) / Non-primative (reference type)
//number, string, bool   / object, array, function

//primative
let number = 5
let string = "hello"
let bool = true or false

//non-primative
let object = {thing: "it's a thing"}
let array = [1, 2, 3, 4, 5]
function example(){
  console.log("Function")
}


//SECTION operators

//number math and operators
number++
number--
number += (reassigns the variable to the solution)
number -=
number *=
number /=
number %= (modulus divides and assigns the remainder to the variable)

//comparative operators
number == 5 //returns true or false if it's true or false
number === 5 //checks for equality and data type
number >
number <
number >=
number <=

//string operators
string += (adds to the string) //concantination
string = `hello ${example}` (adds to the string) //interpolation
string == (compares strings)

//bool operators
bool == true //are these equal?
bool != false //are these not equal?

//extra conditional fun 
console.log(5 == '5')
console.log(5 == '5' && 5 == '4') //FALSE, && AND returns true if both sides are true
console.log(5 == '5' || 5 < 4) // || OR returns if ONE side is true

//flipping a bool
//marathon way
if(bool){
  bool = false
} else {
  bool = true
}
//shorter way (ternary)
bool = bool ? false : true
//speed run way
bool = !bool

//SECTION functions
Declaration, Name, Parameters, and Return

() Invocation of function

function example(x, y){ }  // x and y would be the parameters
example (a, b)  // a and b would be the argument supplied to the function


//SECTION arrays

let newArray = array.filter() // creates a new hidden array


SECTION dictionary
Object with mutiple values ie.
  let animals = {
    Brian: {
      height: '5ft 7in',
      weight: 190
    },
    Joe: {
      height: '5ft 5in',
      weight: 150
    }
  }

  Easier to access information from a dictionary but more difficult to add or remove information then an array
Drawing to page is not a for loop but looks like:
    for(let key in #dictionary){
      let #banana = #dicionary[key]
      console.log(#dictionary)
    }