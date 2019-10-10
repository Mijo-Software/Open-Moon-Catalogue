# Open Moon Catalogue

The Open Moon Catalogue is a catalogue of all known moons in the solar system and beyond. It is completely open. We welcome contributions and corrections from both professional astronomers and the general public.

## Data access

This website is just a front end that displays the database in a browser. The actual database is stored in a distributed version control system. There are multiple ways to download the entire database if you want to dive deeper. As a starting point, visit the main repository of the Open Moon Catalogue on github. The website itself is also open source and hosted over at github.

## The XML file format and the version control system git

The data in the Open Moon Catalogue is stored in human readable XML files. There is one file for all known moons. The combination of small text files and a human readable file format makes the entire catalogue work smoothly with git, a popular version control system used to manage different versions of the catalogue. Git allows you to keep your local database in sync with the main repository on github. You can make correction to the files and submit them back to github to be included in the main repository (you can either ask to get write access or send a pull request). Furthermore, you can trace back all changes made to every parameter and find out who made a certain entry and on what date. The git commit message usually includes the reference to the scientific paper where the data is taken from. Thus, you can easily find the scientific reference for every value in the catalogue.

If you are more familiar with simple comma or tab-separated ASCII tables, you can find these in the omc_tables repository on github. They contain mostly the same information as the XML files. However, some information, especially in the case of a binary system cannot be easily represented in an ASCII table. You are therefore encouraged to use the original XML files provided by the Open Moon Catalogue.
