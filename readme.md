# TacocaT Challenge Minisite

This is a complete minisite that contains a visual representation of the "Tacocat" challenge.

## What is the "TacocaT" challenge?

The word "Tacocat" is a palindrome, meaning it's spelled the same forwards and backwards.
This challenge is about building a function to detect these.

Traditionally knows as the "reverse a string" exercise, it has in some form
been used by technology companies such as Amazon, Microsoft, VMware and Norton
to assess a candidate’s ability to code an impromptu algorithm.

## Installation

You can view this site [live](https://tacocat-challenge.netlify.app).

To download and run locally, clone this repository and open index.html.

``` sourceCode
git clone https://github.com/joshpters/TacocaT
```

## Core Function

This is the core function that determines if a string is a palindrome.

The minisite has a modified version of this to work with animations for better appearence.

```javascript
function checkPalindrome(text) {
    let latter = text.length - 1;
    let halfwayPoint = latter / 2;
    for (let former = 0; former < halfwayPoint; b++) {
        if (text[former] != text[latter]) {
            return false;
        }
        latter--;
    }
    return true;
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.