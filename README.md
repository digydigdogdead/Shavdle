# Shavdle

Shavdle is a daily word guessing game built in ASP.NET Blazor. It is similar to similar well known daily guessing games but with a twist, it uses the [Shavian Alphabet](https://shavian.info/), an alternative alphabet for the English language designed by Kingsley Read to better reflect the phonemes of the English language. 

Use the in-game keybord to spell a 4 letter word and submit it. Your guess will be added to the grid below. If a letter is highlighted in Green, it is both correct and in the right place. If it is highlighted in orange, that means the letter you chose is present in the target word, but it's not in the right place. If the letter is hightlighted in grey, that means that that letter is not in the target word at all.

Compared to similar games, the words are only 4 letters long because the average word spelled in Shavian is shorter than the latin-alphabet equivalent, and you get more guesses because the Shavian alphabet is considerably larger.

## To-Do and Considerations
- Similar games prevent you from submitting words that aren't in the dictionary. A similar function may be of benefit here, however there isn't a complete Shavian dictionary to my knowledge, and if there was it could cause some controversy within the community, as some spellings are disagreed upon (especially words ending in an -ee sound like "Happy" which is standardised as 𐑣𐑨𐑐𐑦 but many argue should be written as 𐑣𐑨𐑐𐑰). So, at least for now, the app will not attempt to verify the words submitted and will allow any old gibberish. Which does allow you to "game" the system more than similar games would allow (for example by putting the same letter in every slot to determine exactly where it goes).
- Some similar daily games will reflect your results as you progress in the on screen keyboard to make it easier to make your next choice. That could be implemented here.
- I would like to host this on github pages, just need to figure out exactly how that works.

### Acknowledgements
- This app makes use of [Mudblazor](https://github.com/MudBlazor/MudBlazor)
