# trumpFortunes
trump tweet fortune file


This is a string file consisting of President Donald Trump's tweets, excluding re-tweets. The data was obtained from the <a href="http://www.trumptwitterarchive.com/">Trump Twitter Archive.</a>
<p>I downloaded the data and with a bit of sed and awk magic I converted it into a file appropriate for use in the Unix program "fortune." The fortune program is frequently included in Unix and Unix-like distributions and available as a package for most others. <p>
 <p>To use this file with fortune you will need to use a program called strfile that is frequently included in Unix distributions and available as a package for most others. Usage would be "strfile trumpFortunes" to create the file that fortune will use to generate random fortunes. <p>
  Example usage:<br> 
 <br> 
 git clone https://github.com/akessamenos/trumpFortunes.git<br> <br> 
 
#strfile trumpFortunes<br> 
"trumpFortunes.dat" created<br> 
There were 27440 strings<br> 
Longest string: 320 bytes<br> 
Shortest string: 3 bytes<br> 
#fortune trumpFortunes<br> 
More than $500 million designated for Iraqi Army disappeared. Where is it? Our sad sad country--what have we come to?<br> 

<p>Now you too can randomly wonder what have we come to from the command line or many other kinds of fortune cookie dispenser throughout the universe!</p>
