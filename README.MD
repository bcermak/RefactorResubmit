## Homework 1 - Refactoring ##

## Main Objective ##

The goal of this assignment is to "clean up" the HTML/CSS to ensure accessibility of the webpage. 

## Explanation ##

The first error that stood out was that the document had technically DID have a "footer", but this was being constructed using a class instead of traditional footer section. I deleted that class and moved the same copy into a Footer. Additionally, the H2 tag that was being used didn't make logical sense, so I updated those to be H4 tags to better fit being located at the bottom of the script. From there, I knew I needed to update the CSS to reflect these changes. 

Next, I noticed there were *divs* in many places that could be using better desciptive semantics. I updated these to be *nav* and *section*.

The image tags all appeared to not be closed properly, so I added the proper closing brackets. 


## Actions Taken ##

<li>Added a 'true' Footer, rather than creating the footer using classes.
<li>Reordered H tags by numerical order
<li>Changed *div* to *nav* for the Navigation Bar
<li>Changed *div* to *section* for main webpage contents
<li>Fixed image tags on all images by closing tag
<li>Added more descriptive Meta Tag
<li>Reordered CSS file H tags by numerical order
<li>Reordered CSS file classes/IDs to fit page order
<li>Added CSS styling for new footer/H tags


