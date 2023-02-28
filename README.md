# Create app with information about artist
This files was created for working with artists from Spotify.
Both files have some similar functions:
- get_token (Function for getting token from client ID and client secret)
- get_auth_header(Function for making authorithation header)
- search_for_artist(Function has two arguments - token and artist name, returns id of artist)
- get_song_id_by_artist_id(Function returns name of the best song of artist and id of this song. get_song_id_by_artist_id has two arguments - token and artist_id)
- get_markets(Functions returns list of available markets of song. Function has two arguments - token and song_id)
## File "lab2_task2" 
In this file you can get information about artists, for example: name of artist, name of the most popular song, artist's id, available markets for song.
You can get all this information from function get_general_info. As argument takes artist's name.
### Example of input and all available options:
![Знімок екрана 2023-02-28 о 21 41 20](https://user-images.githubusercontent.com/116551880/221961217-379be4f5-2f57-4203-8b0f-8c066bacdaaf.png)

## File "lab2_task3"
This file has two additional functions for creating map: get_coordinates(function returns coordinates of country) and create_map, which create map.
Result of this program was taken to pythonanywhere (http://anastasiako.pythonanywhere.com)
### Example of input:
![Знімок екрана 2023-02-28 о 21 24 41](https://user-images.githubusercontent.com/116551880/221963086-b059f945-95ca-4b31-bc35-8195615eb91c.png)
### Example of output:
![Знімок екрана 2023-02-28 о 21 53 27](https://user-images.githubusercontent.com/116551880/221963906-522d8c67-1208-40a4-a4c5-3cae59e137c0.png)
