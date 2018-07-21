# city-match
![image](https://user-images.githubusercontent.com/4397663/43040457-a39601f6-8d01-11e8-9dcb-0fad50c248a7.png)
# What
A simple tool that given some text, outputs a list of city names based on the fuzzwuzzy string similarity algorithm. 

# Why 
Often you have some data that describes a some metric at a city-level but is contained in some larger text. This type of data is hard to geocode. If you could use a utility that scanned each row and extracted just the city names then such data can be geocoded that much more easily.

# How 
Usage: 
```
python city-match.py "some text" <number of matches>
```

# Credits:
- https://github.com/seatgeek/fuzzywuzzy
- https://github.com/richard512/Little-Big-Data
