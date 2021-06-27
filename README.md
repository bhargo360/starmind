# starmind

Task :-
In this dataset of dog names in Zurich, find all names that have a Levenshtein distance of 1 to "Luca". Write your answer here (comma-separated names, in any order).
Link to dataset :- https://opendata.swiss/en/dataset/hundenamen-aus-dem-hundebestand-der-stadt-zurich2/resource/3e48403f-1ca2-434f-8766-cf0a73d7c2a1

For uniformity:
- Install anaconda
- Restore environment "starmind.yml" using following command
conda env create --file starmind.yml
- Activate Environment
conda activate starmind

In case of environmental restoration error kindly install following libraries of Python
- numpy
- pandas
- juypter notebook

The solution for the task is:-
Cuca,Lua,Luba,Lucas,Luce,Lucia,Lucy,Lula,Luma,Luna,Lupa,Yuca

Logic for completing the task:-
- define levenshtein distance function
- import data
- clean data
- apply function
- filter by levenshtein distance of 1
- display result in comma separated

Keep Coding and Keep Smiling