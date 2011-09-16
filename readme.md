#Random Regex that are useful
first line is Search
second line is Replace

##CSS

###2 spaces to 4 spaces

    \n  (\w)
    \n    $1
    
or any number to 4 spaces (dangerous if you space erratically for flagged properties)

    \n\s+(\w)
    \n    $1