# Parsing CLDR Data

This is a PHP CLI tool designed to parse CLDR data and print a list of all the languages spoken in the world as well as the total number of speakers per language.

### Running the program
1. Clone this repo to your machine and navigate to the `parse_cldr` folder;
2. Ensure that you have PHP installed in your system and accessible in your terminal environment. Go to your terminal of choice and simply run
```
./cldr_parse
```

> If running the script raises a permission denied error, ensure to give the script execute access. You can just do `chmod 777 cldr_parser`.

That's it! You should see a beautiful table printed with all the language statistics you need.

The data used for this program is located [here](http://unicode.org/repos/cldr/trunk/common/supplemental/supplementalData.xml).

### Tools used
- [Punic](https://punic.github.io/) - PHP Unicode CLDR toolkit
- [php-cli-tools](https://github.com/wp-cli/php-cli-tools) - Command line utilities for PHP