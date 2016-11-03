we be branching!

git cheat sheet - https://www.git-tower.com/blog/git-cheat-sheet/

DRY it up! Don't repeat yourself. Once you've got code that works, consolidate it to be more compact - don't repeat yourself!
The simplest possible code is best

.length is a property available on array objects

Math.random uses the computer's clock to generate a random decimal number between 0 and 1
Math.floor rounds a number DOWN to the nearest integer
Math.ceiling rounds a number UP to the nearest integer

Basic object:
    var dog = {
      name: 'Fido',
      age: 8,
      bark: function() {
        return 'woof';
      },
      collar: true
      }
    };

    pairing ekys with values (name is a key--or a property, 'Fido' is a value)

Functions

named function:
  function barkLoudly () {
    return 'WOOF!!!';
  }  --->this is available to be executed from the beginning of the script: NO semi-colon after the end curly bracket because it is not\
  being assigned into a variable, it is a function declaration

  anonymous function being assigned into a variable:
    VAR barkQuietly = function () {
      return 'woooof';
    };  --->this function is available ONLY to be executed in the script after it is written, YES semi-colon after end curly bracket

Classes can be made as functions that are capitalized, basically
  example: function Dog(example1) {
     this.example1 = example1      --------------->"this" refers to the Dog object we are creating; makes generic properties for Dog
  }
---------->  Dog is a class

A function on a class object we call a "method"
