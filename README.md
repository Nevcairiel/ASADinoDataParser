# ARK Dino Data Parser

A Blueprint library to parse ARK Dino Data bytes.

Example Usage:
![Example Usage](https://raw.githubusercontent.com/Nevcairiel/ASADinoDataParser/refs/heads/master/DinoDataExample.png)

The data is output using a JSON Object, which has the advantage of allowing structured arbitrary data without needing complex data structures.
For determining which fields are present in the JSON Object, I would recommend to serialize it into a string and printing it, as the information can vary depending on the dino and its status.

## Limitations

The library does not currently support fields of these types:
- int64
- Map

int64 could be supported without that much effort, but I have had no personal need for it.
