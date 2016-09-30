# weheartswift.com
//CHAPTER1_FIRST STEPS
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
var a = 11
var b = 22




