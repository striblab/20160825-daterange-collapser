# JS Date Range Collapser

by [Frey Hargarten](https://github.com/jeffhargarten)

Built using Mike Bostock's [D3](https://github.com/mbostock/d3). Takes overlapping and consecutive date rages from a given CSV file and collapses them into single ranges according to a unique name or ID.

The basic CSV file has to have the following columns:


id - A unique ID tied to a specific element whose overlapping dates you're looking to collapse

start - The first date in a range

end - The last date in a range


Unless specified in the code, all other fields will be ignored.

The results will be printed on the page when you launch index.html, usually in a browser with MAMP/LAMP/WAMP running. The output is comma-seperated for easy saving as a CSV.

Of course, feel free to modify anything to your needs, this is a pretty flexible script, though may require some trial and error to put feed additional datapoints into it.