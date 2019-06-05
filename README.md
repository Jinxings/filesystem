# Filesystem library

Table of Content

[**open_file**](https://github.com/Aviarita/filesystem/blob/master/README.md#clientopen_filefilename-pathid)<br>
[**read**](https://github.com/Aviarita/filesystem/blob/master/README.md#fileread)<br>
[**write**](https://github.com/Aviarita/filesystem/blob/master/README.md#filewritetext)<br>
[**clear**](https://github.com/Aviarita/filesystem/blob/master/README.md#fileclear)<br>
[**close**](https://github.com/Aviarita/filesystem/blob/master/README.md#fileclose)<br>

### client.open_file(filename, [pathid](https://github.com/Aviarita/filesystem/blob/master/README.md#paths-ids))
    filename - name of the file you want to open
    path id - pathid of the path where the file will be created/opened from
    returns a metatable of functions

### file.read()
    returns the content of the opened file
    
### file.write(text)
    text - text you want to write to the text
    Writes the given text ot the file
    
### file.clear()
    Clears the file
    
### file.close()
    Closes the file

### Paths IDs
    MOD
        The first SearchPath only.
    GAME
        All SearchPaths, including those inside GCFs.
    GAMEBIN
        The game binaries folder (client, server).
    EXECUTABLE_PATH
        The engine binaries folder.
    DEFAULT_WRITE_PATH
        Wherever the game is currently configured to write out to. Defaults to the first SearchPath.
