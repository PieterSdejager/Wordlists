# Wordlists for CTFs

A repo for wordlists I have made. These are meant for Capture-the-flag competitions, but could potentially be used for cracking actual passwords. I am usually using curl/wget with a combination of grep and other linux commands to clean the dataset to get the important parts from it.

## Wordlist Info

- [111111 Movie Names](https://github.com/harisqazi1/Wordlists#111111_movie_namestxt-updated-may-6-2022)
- [306 Game Characters]()

### 111111_movie_names.txt (Updated May 6, 2022)

Combined the following IMDB movie lists:

https://www.imdb.com/list/ls057823854/

https://www.imdb.com/list/ls075401331/

https://www.imdb.com/list/ls063676189/

I cleaned it up a bit removing the extra data that was not needed for this. I then sorted it to remove duplicates (`cat <file> | sort -u`).

### 306 Game Characters

Combination of characters from the following links:

https://nintendo.fandom.com/wiki/Nintendo_characters

https://videogamefanon.fandom.com/wiki/List_of_Gaming_All-Stars_Characters
