# weheartswift.com
//CHAPTER2_CONDITIONALS
//: Playground

import UIKit

var numberOfOranges = 15
var numberOfApples = 5

if numberOfApples > numberOfOranges {
    print("You have more apples than oranges!")
}
else{
    print("You have more oranges than apples!")
}
//  >   <   >=   <=     ==      != (not equal)
var money = 20
var burgerPrice = 205
// if you have enough money pay for the burger
if money >=  burgerPrice {
    print("pay burger")
    money -= burgerPrice
        // if you have some money left order desert
        if money > 0 {
            print("order desert")
        }
} else {
    // otherwise you will need to go wash dishes to pay for your meal
    print("wash dishes")
}

var age = 23
var money2 = 25000

if age >= 18 {
    if money2 >= 20000 {
        print("Getting a new car, baby!")
    } else {
        print("Sorry, you don't have enough money.")
    }
} else {
    print("Sorry, you're not old enough.")
}

//     a && b (AND)       a || b   (OR)         !a   (NOT)        (a...b)  RANGE
var age3 = 18
if age3 >= 13 && age3 <= 19 {
    print("Teenager")
}
var age4 = 123
if age4 <= 0 || age4 >= 100 {
    print("Warning age is probably incorrect!")
}

//An OR statement is also true when both conditions are true at the same time
var numberOfSisters = 1
var numberOfBrothers = 2
if numberOfSisters > 0 || numberOfBrothers > 0 {
    print("Has siblings")
}

//Range
for index in 1...5 {
    print("\(index) times 5 is \(index * 5)")
}

// if NOT allowedEntry == if alloweEntry is false
let allowedEntry = false
if !allowedEntry {
    print("ACCESS DENIED")
}

//You can negate a condition using the ! operator
var age5 = 18
if !(age5 >= 13 && age5 <= 19) {
    print("Not a teenager!")
}

//2.1 Max_Print the largest number
var a = 111
var b = 22

if a > b {
    print("The lasrgest number is \(a)")
} else {
    print("The lasrgest number is \(b)")
}

//2.2 Even or odd
var number = 1
if number % 2 == 0 {
    print("even")
} else {
    print("odd")
}

//2.3 Divisibility (=podzielność)
var c = 17
var d = 3
if c % d == 0 {
    print("divisible")
} else {
    print("not divisible")
}

//2.4 You are given three variables a, b and c. Check if at least two variables have the same value. If that is true print At least two variables have the same value otherwise print All the values are different.
var e = 0
var f = 23
var g = 23

if e == f || e == g || f == g {
    print("At least two variables have the same value")
} else {
        print("All the values are different")
}

//2.5 Breakfast
/*You are working on a smart-fridge. The smart-fridge knows how old the eggs and bacon in it are. You know that eggs spoil after 3 weeks (21 days) and bacon after one week (7 days).
Given baconAge and eggsAge(in days) determine if you can cook bacon and eggs or what ingredients you need to throw out.
If you can cook bacon and eggs print you can cook bacon and eggs.
If you need to throw out any ingredients for each one print a line with the text throw out ingredient (throw out bacon or throw out eggs) in any order.
*/
var baconAge = 7 // the bacon is 6 days old
var eggsAge = 33 // eggs are 12 days old
if baconAge >= 7 {
    print("Throw out bacon")
    if eggsAge >= 21 {
        print("Throw out eggs")
    }
} else {
    print("Cook bacon and eggs")
}

//2.6 Leap year
//You are given a year, determine if it’s a leap year. A leap year is a year containing an extra day. It has 366 daysinstead of the normal 365 days. The extra day is added in February, which has 29 days instead of the normal 28 days. Leap years occur every 4 years. 2012 was a leap year and 2016 will also be a leap year. The above rule is valid except that every 100 years special rules apply. Years that are divisible by 100 are not leap years if they are not also divisible by 400. For example 1900 was not a leap year, but 2000 was. Print Leap year! or Not a leap year! depending on the case.

let year = 2014



