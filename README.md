# Forbidden Lands Character Name Generator
A name generator for the forbidden lands TTRPG. Based on names from official _German_ publications (currently core set and Raven's Purge). Will generate names for any of the playable races.

## How to use
Run the script or the exe file. You will be asked for the race and gender to generate names for, and how many names to generate.
After the names have been generated you have the option to save these to a csv-file.

These names are generated in a relatively simple manner (see below), so some names might be unusable/unpronouncable. Still, the majority of the generated names should be usable.

## How it works
It is simply, really :-). I looked up all the names from the core set and Raven's Purge and sorted them by race and gender.
Then I split these names into 2-3 parts (usually based on syllables, but not always).
I created three lists for each race/gender combination, one list for each part.
If a name only has 2 parts, these went into the first and last list. The middle list was then filled with an empty string.
When generating names, the script simply shuffles each list and takes one random part from each list and smashes them together.
I added a small check to make sure that no duplicate names are generated. And that is all!
