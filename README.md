The [https://wordpress.org/plugins/events-manager/](events-manager wordpress plugin) is hard to export data from.

This takes all its data, and gives you a CSV file you can export into google sheets.

You also need to run this formula to import to a new sheet and fix stuff:

`=ARRAYFORMULA(SUBSTITUTE(SUBSTITUTE(SUBSTITUTE(SUBSTITUTE(raw!A1:AJ14022,"YAR77D",CHAR(10)),"YAR77C",","),"YAR77B",""""),"YAR77A","'"))`

or something like that
