100 days-sentence-maker.md

   Day 1 : Sentence Maker - Debugging Strings

What I built : A small JS program that takes variables and combines them into a story using string concatenation.

Problem I hit
My sentence was coming out as `bravedragonwholoved` with no spaces. 

What I learned
In JS, `+` joins things exactly as written. If you want spaces, they have to be inside the quotes:  
`"word " + variable + " word"` not `"word"+variable+"word"`

I Fixed :  
```javascript
firstStory = "Once upon a time, there was a(n) " + adjective + " " + noun + " who loved to eat " + noun2 + ".";


Lesson for future me:

Small syntax details break big things. Check spaces and quotes first when debugging strings.