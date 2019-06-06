# Filesystem library

Table of Content

[**client.open_file**](https://github.com/Aviarita/filesystem/blob/master/README.md#clientopen_filefilename-pathid)<br>
[**file:read**](https://github.com/Aviarita/filesystem/blob/master/README.md#fileread)<br>
[**file:write**](https://github.com/Aviarita/filesystem/blob/master/README.md#filewritetext)<br>
[**file:clear**](https://github.com/Aviarita/filesystem/blob/master/README.md#fileclear)<br>
[**file:close**](https://github.com/Aviarita/filesystem/blob/master/README.md#fileclose)<br>

### client.open_file(filename, [pathid](https://github.com/Aviarita/filesystem/blob/master/README.md#paths-ids))
    filename - name of the file you want to open
    path id - pathid of the path where the file will be created/opened in/from
    Returns a table with the following functions.

### file:read()
    Returns the content of the file.
    
### file:write(text)
    text - text you want to write to the text
    Writes the given text ot the file.
    
### file:clear()
    Clears the file.
    
### file:close()
    Closes the file.

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
