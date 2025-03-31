# ARK Dino Data Parser

A Blueprint library to parse ARK Dino Data bytes.

Example Usage:
![Example Usage](https://github.com/Nevcairiel/ASADinoDataParser/blob/master/DinoDataExample.png?raw=true)

The data is output using a JSON Object, which has the advantage of allowing structured arbitrary data without needing complex data structures.
For determining which fields are present in the JSON Object, I would recommend to serialize it into a string and printing it, as the information can vary depending on the dino and its status.

## Limitations

The library does not currently support fields of these types:
- float/double
- int64
- Map

Float/Double and int64 could be supported without that much effort, but I have had no personal need for it.
