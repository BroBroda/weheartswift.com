# weheartswift.com
//CHAPTER1_FIRST STEPS
//: Playground

import UIKit

//Variables and Constants
let sum = 2 + 5
let diff = 15 - sum
let mul = diff * sum
let div = mul / diff
let modulo = 7 % 3
//because 2 * 3 + 1 = 7       +   -   *   /    %
let modula2 = 13 % 5

let diff2 = 5 / 2
let diff3 : Double = 5 / 2
let remainder = 5 % 2
15 / 5
15 % 5      //divided by 5

var numberOfApples = 7
var numberOfOranges = 2

// you eat an apple
numberOfApples = numberOfApples - 1

// a wizard doubles your oranges
numberOfOranges = numberOfOranges * 2

var stashedFruits = numberOfApples + numberOfOranges //(6 + 4)

// you receive 2 apples (numberOfApples = 8). stashedFruits remains unchanged!
numberOfApples += 2

stashedFruits /= 2 // you lose half your stashed fruits 5 (10 / 2)

//1.1 Sum
var a : Float = 0.8
var b : Float = 92837
var sumAB = a + b
print(sumAB)

//1.2 Determine the number of seconds in a year
let secondsInDay = 24 * 60 * 60
let daysInMonth = 365
var secondsInYear = secondsInDay * daysInMonth
print("There are \(secondsInYear) seconds in a year")

//1.3 Find out the values of the original numbers
let sumCD = 16 // c+d
let diffCD = 4 // c-d
//sumCD + diffCD = c + d + c - d
//sumCD + diffCD = c + c
let c = (sumCD + diffCD)/2
let d = sumCD - c
print("Value of c is \(c) and the value od d = \(d)")

//1.5 L Area
var width = 8
var height = 12
var x = 4
var y = 3
/*
 _x_
|   |
|   |
|   |___
|       |
|_______| y
width
*/
var height2 = height - y
var width2 = width - x
var perimeter = height + width + x + y + height2 + width2
var area = width*height - height2*width2
print("Perimeter of L shape is \(perimeter) and the area is \(area)")

//1.6 Swap
var e = 5
var f = 8
var g = f
f = e
e = g
print("e = \(e)  f = \(f)")

//1.7 Last digit
var h = 123
//hint: use %
var i = 567867
print(h % 10)
print("Last digit of \(i) is \(i % 10)")
/*  a = k * (a / k) + a % k
var k: Int
//123 = k * (123/k) + 123 % k
3 * (123/3) + 123 % 3
123 / 3
123 % 3 // 0    lastDigit = 3
//h = h/lastDigit * lastDigit + h % lastDigit
var lastDigit: Int
h = h/lastDigit * h + h % lastDigit
print(lastDigit)
*/

//1.8 Dog years__1 human years is 7 dog years
var rockyAge = 50
//1 = 7
//g = 50
var rockyHumanAge = rockyAge / 7
print("Dog Rocky has \(rockyHumanAge) human years")

//1.9 Brothers
//x years from now Alice will be y times older than her brother Bob. Bob is 12 years old. How many years does Alice have?
var yearsPast = 3
var timesOlder = 2
var bob = 12
var alice : Int
//alice + yearsPast = (bob + yearsPast) * timesOlder
alice = (bob + yearsPast) * timesOlder - yearsPast
print("Alice is now \(alice) years old")

/*1.10 Apples and Oranges
 You have x apples. Bob trades 3 oranges for 5 apples. He does not accept trades with cut fruit.
 How many oranges can you get from Bob and how many apples will you have left?
 The number of apples you will have left should be stored in a variable named apples. The number of oranges you will have after the trade should be stored in a variable named oranges */
var applesBeginning = 17
var apples:Int
var oranges = applesBeginning / 5 * 3
apples = applesBeginning % 5
print("After trade I will have \(apples) apples and \(oranges) oranges")

//1.11 Boys and Girls: Print the percentage of boys in the class followed by the percentage of girls in the class. The percentage should be printed rounded down to the nearest integer. For example 33.333333333333 will be printed as 33.
var numberOfBoys : Int = 10
var numberOfGirls : Int = 20
var holeClass = numberOfBoys + numberOfGirls
var percentageOfBoys = numberOfBoys * 100 / holeClass
var percentageOfGirls = numberOfGirls * 100 / holeClass
print("Girls: \(percentageOfGirls)% ; Boys: \(percentageOfBoys)%")
