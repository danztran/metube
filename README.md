# metube
Shell script to download entire youtube playlist videos and convert to music format.

## Setup
```sh
./metube install
```

## Run
Prepare a sources file contains all playlists including name and url in the following format: 

sources.txt
```
name1,url1
name2,url2
```

```sh
./metube download sources.txt /path/to/music
```

