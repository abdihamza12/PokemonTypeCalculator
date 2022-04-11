# PokemonTypeCalculator
An application where you search for a type combination and the program will output every pokemon that matches that type combination. 


Hello to those who are reading this!
This is my first github repository and I'm using it to display the first larger project that I've created

Current Issues with the code:
  - The excel spreadsheet that I used to gather data from is only updated up to generation 5 of pokemon (649 / 898 PKMN)
  - Window does not expand when text goes beyond the frame
  - When a generic pokemon type is searched (pure water), the buttons will spread apart from each other. 


Libraries Used:
  - os
  - pillow   (for image processing)
  - tkinter  (for gui)
  - openpyxl (for data manipulation)


I found this excel sheet in a reddit thread when I was brainstorming this project. It had gotten the data from Smogon, the leading pokemon database/ competetive platform. There are 2 excel sheets because the original V5.14 left empty cells if a pokemon had no secondary typing. I had to reformat all the cells that were empty to say 'none' and when I did that the sheel lost its color coding and formatting. Thats why 'V5.14 Ugly' exists. It works better for the code but I included the original for reference. 


REDDIT THREAD: https://www.reddit.com/r/pokemon/comments/2q30m5/national_pokedex_in_google_spreadsheets/
SMOGON PAGE:   https://www.smogon.com/forums/threads/excel-pokedex-v5-14-smogon-tiers-and-legal-dw-abilities-here-outdated.102714/

