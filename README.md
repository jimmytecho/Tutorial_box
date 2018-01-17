# Tutorial_box
following sentdex's machine learning with python tutorial on youtube


Worked in Virtual Box Ubuntu
(tut means the sentdex tutorial)

## regression

### tutorial 2
\>need to do "pip install quandl --user" in /regression
\>tut used Quandl for some reason. need to change to quandl
\>failed for some reason

\>success after adding quandl.ApiConfig.api_key = "key"

### tutorial 4

\> second y = np.array(df[\'label\']) is not neccesary

### tutorial 18

\> for python 2 corrrect/total needs to be float(correct)/float(total), or else it will output 0, because it uses integer division.

## supported vector machine

\> for introductions to supported vector machine, better watch "Support Vector Machines: A Visual Explanation with Sample Python Code" (https://www.youtube.com/watch?v=N1vOgolbjSc) then "16. Learning: Support Vector Machines" (https://www.youtube.com/watch?v=_PwhiWxHK8o) for more mathematics details.



## Side notes

### sublime text jump out of quotes
in Key Bindings - User
"keys": ["shift+space"], "command": "move", "args": {"by": "characters", "forward": true} }
(https://stackoverflow.com/questions/14800608/sublime-text-2-move-cursor-out-of-parenthesis-quotes-or-brackets)
try later {
https://gist.github.com/koulmomo/8396647
https://gist.github.com/craiggists/2268146
https://forum.sublimetext.com/t/shortcut-to-move-cursor-out-of-parenthesis-quotes-brackets/4330/3
}
