# School

Here we create and edit files and links to open with cubari ( Cubari.moe ) , ETC . It contains books , classworks , book answers , etc . 
Please help us . We are in need of members . Also join our discord server ( https://discord.gg/eYEutvrgse ) . 

# How to create a file for cubari .

This guide was created from - https://www.reddit.com/r/manga/comments/mcicbp/sl_how_to_host_a_series_on_imgur_with_guyamoe

Step 1 : Create a new file 
Step 2 : Paste this piece of code 

{
  "title": "<manga title>",
  "description": "<manga description>",
  "artist": "<manga artist>",
  "author": "<manga author>",
  "cover": "<mangacoverurl.jpg>",
  "chapters": {
    "<chapter number>": {
      "title": "<chapter name>",
      "volume": "<volume number>",
      "groups": {
        "<group name>": "/proxy/api/imgur/chapter/<imgur id>/"
      },
      "last_updated": "1616368746"
    },
  }
}

Step 3 : Replace every <headers> . Look our files for examples .
Step 4 : Upload required files to imgur and replace <imgur id> with the alphabets after following https://imgur.com/a/ .
Step 5 : Remove the last comma ( , ) .

# Add new chapters

Step 1 : Add the last comma you removed .
Step 2 : Paste this code before the last two brackets . 

 "<chapter number>": {
      "title": "<chapter name>",
      "volume": "<volume number>",
      "groups": {
        "<group name>": "/proxy/api/imgur/chapter/<imgur id>/"
      },
      "last_updated": "1616368746"
    },

You can do this for every chapter you want to add . Just make sure to remove the last comma ( , ) .

It should look something like this :

{
  "title": "<manga title>",
  "description": "<manga description>",
  "artist": "<manga artist>",
  "author": "<manga author>",
  "cover": "<mangacoverurl.jpg>",
  "chapters": {
    "<chapter number>": {
      "title": "<chapter name>",
      "volume": "<volume number>",
      "groups": {
        "<group name>": "/proxy/api/imgur/chapter/<imgur id>/"
      },
      "last_updated": "1616368746"
    },
 "<chapter number>": {
      "title": "<chapter name>",
      "volume": "<volume number>",
      "groups": {
        "<group name>": "/proxy/api/imgur/chapter/<imgur id>/"
      },
      "last_updated": "1616368746"
    }
  }
}

 