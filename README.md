# AlphabetizeArray
 Assets for working in the Ark Dev Kit to make mods. Example function library that will allow you to alphabetically sort arrays. Includes a test singleton actor you can use in PIE to see how it works.

## License
Creative Commons Zero v1.0 Universal
_meaning do what you like with this and I am not responsible in anyway... :D_

## Contents
- __Alphabetize_Struct
  - structure used by the sort logic, function returns array of these
  - includes sorted string as well as the original item's array index
- _AlphabetizeFuncs
  - function library that provides function to sort alphabetically
  - function name: Alpha_SortStringArray
- AlphaSortTestActor
  - singleton actor for testing & demo of usage 
  
## Other
- Included PIE_Tests_Output.PNG shows log output sorting strings and dinos both asc/desc 
- Will _somewhat_ sort unicode characters 