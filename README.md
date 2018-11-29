
Frontend challenge
------------

### Requirements:
- Consistent across all modern browsers
- Integrate with the backend API or view (Display the output from backend)

### What you need to build:

The following design in HTML/CSS/JS, however does not have to be 100% accurate

![Design](https://github.com/ilyasfoo/fullstack-challenge/blob/master/readme-images/result.png "Design")

### Bonus points if u use:
- Vuejs/react/angular or similar frameworks
- SASS/LESS or similar CSS preprocessors
- Flexbox
- Responsive media queries for different screen sizes
- Any animations or extra effects will be added on creativity bonus

### Notes:
Fonts used: [https://fonts.google.com/specimen/Sofia?selection.family=Quicksand:400,500,700|Sofia](https://fonts.google.com/specimen/Sofia?selection.family=Quicksand:400,500,700|Sofia)

All assets can be found here: [https://github.com/ilyasfoo/fullstack-challenge/tree/master/assets](https://github.com/ilyasfoo/fullstack-challenge/tree/master/assets)

Background
- background-color: `#333333`

Yellow box container
- background-color:  `#FEEA3A`
- box-shadow: `rgba(0,0,0,0.5) 0 0 10px`

Header
- color: `#333333`
- font-size: `46px`
- font-weight: `700`

Input
- color: `#000000`
- font-size: `18px`

Buttons
- color: `#6E672D`
- font-size: `16px`
- font-weight: `800`

Summarized distances between elements are as follows:

![Design](https://github.com/ilyasfoo/fullstack-challenge/blob/master/readme-images/sizings.png "Design")


Backend challenge
-------------

### Requirements:
You need to use the following as a minimum: Laravel Framework utilizing at least `Routes`, `API/Views`, and `Controller`

### What you need to build:
An API to produce output from the given input, as explained below.

Types of cats
-------------

A type of cat is defined by the words containing any of the following characters `ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz-` and ends with the immediate word `cat`.
List all types of cats found from the input.

### Example
Input: `The softbottomcat is jumping over a memecat and fell down on top of catnips`

Output:
```json
[
	"softbottomcat",
	"memecat"
]
```

Input: `Electrocatosis is a process where a oxycat is transmuted-cat into hydrogen cat`

Output:
```json
[
	"oxycat",
	"transmuted-cat"
]
```

Input: `When cat hits the fan, the cat and the fan shall become one catfan`

Output:
```json
[]
```

### Notes:
Length of input characters are ranged from 0 to 5000


Submission
-------------
Create a publicly hosted git repository with your source code and send the link to us
