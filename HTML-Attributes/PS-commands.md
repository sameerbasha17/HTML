commands used in Command prompt(not PS):
To create a file (not the directory i.e:folder) :

        type nul > style.html         //creates  the style.html file



while i am learning the html-attributes i have learnt some PowerShell(ps) commands through the chatgpt .

        To create a file (not the directory i.e:folder) :

                    New-Item hi.html        // creates the hi.html file
        
        another method :
        
                    New-Item -Name "hi.html" -ItemType "file"

        To create a directory(folder):

                    New-Item -Name "h" -ItemType "directory"

        Rename:

                    Rename-Item -path "hi.html" -NewName "PS-commands.md"
