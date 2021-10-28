# SassExercise
9/10/21 Sass Exercise

1. Link the correct file to your HTML file so the styles are displayed in the browser (HINT: “Styles” folder)
2. Set the background color for the “main” div to tan
3. Using Nesting in SASS change the “Eddie Brock / Venom” h1 text color to this hexadecimal color (#ddd)
4. Create a partial file in the “Styles” folder called “_values.scss”
5. Import the “_values” partial file at the top of the “main.scss” file
6. Inside the “_values” partial file create a variable with the name of “$brown1” and set the value for it to #964B00
7. In the main.scss file, use the “$brown1" variable to set the background color for the “Cletus Kasady / Carnage” h2 and the text color for the “Anne Weying” h3
8. Set the background color for the “minor” div to silver
9. Use nesting again to give the “Shriek” h1 a text decoration of underline
10. Also use nesting to give the “Dr. Dan Lewis” h2 a text decoration of line-through
11. Inside the “_values.scss” partial file create an extendable class called “%center” with the following values properties in it (text-align: center & padding: 20px)
12. Extend the “%center” class to the “Shriek” h1 and the “Dr. Dan Lewis” h2 elements so that they will have the text-align and padding properties applied to them

<hr>

BONUS <br>
1. Use the “:hover” pseudo selector on the “Eddie Brock / Venom” h1. Set it so that when you hover over it it has the styles that the “Shriek” h1 has. Must still retain the #ddd color as well. (Hint: Use the “%center” extendable class)
2. Set a 100px bottom margin on the “Shriek” h1 by multiplying 25px by 4
3. Inside the “_values” partial file create a mixin called “flex” with two parameters “$justify” and “$align”. Create the three following properties in the flex mixin (display, justify-content, and align-items). Set the appropriate values for each of the three properties. Then use this mixin to have the “Eddie Brock / Venom” h1 all the way to the left, the “Cletus Kasady / Carnage” h2 in the middle, the “Anne Weying” h3 all the way to the right, and have the Detective Mulligan h4 no longer display on the webpage. Also, use the mixin to make all three (h1, h2, h3) centered vertically in the “.main” div. (NOTE: The “Carnage” h2 just needs to be in between the h1 and h3 elements with equal space between all three. It will NOT actually display centered.)
