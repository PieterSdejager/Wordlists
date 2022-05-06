# Wordlists
A repo for wordlists I have made. I am usually using curl/wget with a combination of grep and other linux commands to clean the dataset to get the important parts from it.

### 111111_movie_names.txt (Updated May 6, 2022)

Combined the following IMDB movie lists:

https://www.imdb.com/list/ls057823854/

https://www.imdb.com/list/ls075401331/

https://www.imdb.com/list/ls063676189/

I cleaned it up a bit removing the extra data that was not needed for this. I then sorted it to remove duplicates (`cat <file> | sort -u`).
