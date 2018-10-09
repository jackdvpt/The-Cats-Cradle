# The Cats Cradle

The new king Richard has taken the throne from the retched King Dale (arguably little difference between the two men). Richard has decided that his first act as king is to reshape the dictionary in his own shape. Although coming up with new words is difficult so he has instead decided to remove words which he feels are no longer necessary in the kingdom.

You have to write a series of functions which when fed a word will identify if it is suitable for the new dictionary (Richordary... His still working on the name really)

## The New Rules
1. No words may contain the word "DALE". *Why should anyone be reminded of that wretched old ruler?*
2. No words that have the same letter twice next to each other
3. If a word contains the same letter twice then they must be at least half the word away from each other (IE there must be  => n/2 letters between them)
4. If a word is more than 8 letters then it must have an even number of vowels
5. Words starting with D cannot be less than 4 letters long
6. A word can contain the same letter 3 or 5 times. These letters can be next to each other but
7. The letter 'L' cannot appear in a plural (limes will fail but lime will pass)
8. Words that follow the rule i before e except after c are not allowed
9.  No onomatopoeia
10. If the word contains an i then it must have an even number of continents
11. The word Richard is allowed

Each of the rules is represented by a function for testing. There is also a main function which when provided a word returns true or false and if false will identify which rule it breaks. Functions should be used for this project as the kings rules are highly volatile and subject to change with no notice at all so must be updatable at the same rate
