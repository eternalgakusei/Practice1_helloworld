# Practice1_helloworld
# Insert comma
A = "Sekai"
B = "konnichiwa!"
print(A + ", " + B)


# Random Haiku Generator from Translated Haiku Lines

import random

first1 = "The old pond,"
first2 = "Spring ocean,"
first3 = "Skinny frog,"
first4 = "The canola flowers,"
first5 = "Oh, tranquility,"
first6 = "When I ate a persimmon,"
first7 = "The green leaves for eyes,"
first8 = "The snow is falling,"
first9 = "The well-bucket is,"
first10 = "A single plum blossom,"
second1 = "A frog leaps in,"
second2 = "Swaying gently,"
second3 = "Don\’t get beaten,"
second4 = "The moon is in the eastern sky,"
second5 = "Penetrating the very rock,"
second6 = "The bell rung,"
second7 = "The little cuckoo in the mountain,"
second8 = "The Meiji era got,"
second9 = "Taken by the morning glory,"
second10 = "It is warm,"
third1 = "Sound of the water."
third2 = "All day long."
third3 = "Issa-san is here."
third4 = "The sun is in the western sky."
third5 = "A cicada\’s voice."
third6 = "The Horyuji temple."
third7 = "The first bonito of the season."
third8 = "Further away."
third9 = "Going to a neighbour for water."
third10 = "As a single."

first = [first1, first2, first3, first4, first5, first6, first7, first8, first9, first10]
second = [second1, second2, second3, second4, second5, second6, second7, second8, second9, second10]
third = [third1, third2, third3, third4, third5, third6, third7, third8, third9, third10]

print random.choice(first),
print random.choice(second),
print random.choice(third)
