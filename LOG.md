***Challange 1***
undertsnding the  scores of the  selectors. I was not undersdtanding what the numbers refered to and how we could be ranking them. 

**Solution**
I researched and found out that the three digits (0,0,0) first one from right is for ID selector, the second is class selector and the last is element selector. so depending on which one we are using we need to flip the zero to one, and compare with the others to determine the priority.

**Observation**
 From the slide we have the combination of the element and a class as the highest. hoevwe i tried the cobinastion of  ID selector and an element. I notice that thats the one that wins, it has highest priority. as we can compare 1,0,1 and 0,1,1, the forst one wins and i understand why trhe style for that one had to apply.