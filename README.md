# International-Dialing-Codes
A list of Internation Dialing Codes Based off Wikipedia Data

Since I couldn't find a pre-made list which was to my satisfaction. I pulled data from this wikipedia article https://en.wikipedia.org/wiki/List_of_country_calling_codes.

As This article doesn't have the Alpha 2 Code such as 'IN' for India in it. I pulled that data from this wikipedia article https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes. which has that data. I did a levenshtein match to merge the two as the country names didn't match excatly. I have tried to fix the edge case innacuracies from the levenshthien match. There could still be few inaccuracies in the data, If you find any please let me know.

The final resulting data omits dialing codes that are not part of a nation and rather are of satellite services or something of similar nature, which is found on the original wikipedia list.
