# Writing Mantainable Javascript

## Variables

* No explicit types.

    var x = 99;
    var name = "Paul";

* Implicit casting

    var x = name;

## Functions

* Always return something. If it's not explicitly defined, they return
  undefined.

## For Loop

    for (var i = 0; i < 10; i++)
    {
      console.log(i);
    }

## Object Literal

    var jsonObj = { foo: 25, bar: "hello" };

## New Basic

    var object = new Object();

## Objects Everywhere

    function getRandomNumber()
    {
      return 42;
    }
    
    getRandomNumber.y = "I am Y";
    console.log(getRandomNUmber.y);

## Equality

* It's weird. Google it.

## Big Numbers

* Javascript starts to round numbers when they get large.
* To fix this pass numbers around as strings because Javascript can't handle
  large numbers.

## Variable Scope

    x = "Hi!"

`x` is a global variable.

    var y = "Hi!"

`y` is scoped to the block it is created in.


## Namespaces

* Javacript isn't familiar with the traditional idea of namespaces.

    var MyObject = function() {
      this.Name = "Paul Mendoza";
    };

    var MyObject = function() {
      this.Name = "Not Paul Mendoza";
    };

    var o = new MyObject();
    // We want to see "Paul Mendoza" printed out.
    console.log(o.Name);

## Arrays

    var arrayA = [4, 5, 6];
    var arrayB = new Array(4, 5, 6);

    var arrayC = [4];
    var arrayD = new Array(4);

    console.log("arrayA.length: " + array.length);
    console.log("arrayB.length: " + arrayB.length);
    console.log("arrayC.length: " + arrayC.length);
    console.log("arrayD.length: " + arrayD.length);

* The takeaway for this is to always use the square bracket syntax for
  creating arrays.

## Strict

* Put `"use strict";` anywhere in a file to force the browser to be stricter
  with Javascript parsing.
* New browsers accept it, old browsers don't care. Totally backwards
  compatible.
