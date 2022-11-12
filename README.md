# HTML
Materials from 
https://www.w3schools.com/html/default.asp
# file://{locationOf(index.html)} 
can be used in any web browser to reach the content

# locationOf(anyFileName.anyExtension)
##File in current directory
IF outputOf(./index.html) != No such file or directory
  locationOf(index.html) = pwd
ENDIF;
##File in somewhere 
  
# '\\' encoding or support may differ among browsers
\'\\' = &%5C
