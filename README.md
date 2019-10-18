### PROBLEM
ERROR_Argument-passed-in-must-be-a-single-String-of-12-bytes-or-a-string-of-24-hex-characters

### INSTRUCTIONS: 
#### Unpack Gzip Tar File:
$> tar xzvf ERROR_Argument-passed-in-must-be-a-single-String-of-12-bytes-or-a-string-of-24-hex-characters.tar.gz [ENTER]

#### Change URL To Your Own Database:
$> cd ./util/database.js
Neovim database.js> 
  ...
      'mongodb+srv://happiesttigger:admin@cluster0-drl8s.mongodb.net/shop?retryWrites=true&w=majority'
  ...
  
  (Change above to your own database).
