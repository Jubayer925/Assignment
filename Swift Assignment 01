//MARK: - Question1
/*
Write a function that takes a String as parameter and returns nothing. The function calculates and prints the frequency of each character in the given string, that means, how many times each character came up in the given string.
Example input:
let string = "Hello"
Example Output:
H = 1
e = 1
l = 2
o = 1
*/

import UIKit

func printCharacterFrequency(_ input: String) {
    let frequencyDict = input.reduce(into: [:]) { dict, char in
        dict[char, default: 0] += 1
    }

    for (char, count) in frequencyDict {
        print("\(char) = \(count)")
    }
}

let string = "Hello"
printCharacterFrequency(string)


//MARK: - Question2
/*
 Write a function that returns a closure, which transforms its input by adding a particular suffix at the end.
 Example:
 let add_ly = add_suffix("ly")
 add_ly("hopeless") ➞ "hopelessly"
 add_ly("total") ➞ "totally"
 let add_less = add_suffix("less")
 add_less("fear") ➞ "fearless"
 add_less("ruth") ➞ "ruthless"
 */
 
 func add_suffix(_ suffix: String) -> (String) -> String {
    return { input in
        return input + suffix
    }
}

let add_less = add_suffix("less")
print(add_less("fear")) 
print(add_less("ruth")) 

