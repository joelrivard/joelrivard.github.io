---
layout: post
title: "Cleaning up data with OpenRefine"
published: true
---

In the past couple of weeks, we've begun to take unstructured data such as text from historical databases and convert it to structured text, for later analysis using spreadsheet software.
We've looked at how to automatically download these datasets (wget) and we've begun to clean-up some of this data by using regular expression commands. We're also looking at the OCR process of documents and issues of what happens when OCR is applied to scanned text.  The next step in cleaning-up data is done with the use of OpenRefine, a product that allows users to easily clean-up data with in a multitude of ways. OpenRefine is a really good tool that can easily consolidate data, remove blanks, convert formats of fields (from text to numeric and vice-versa), trim leading and trailing spaces, defining that characters be either lower or upper case and many more just by the click on a few buttons. While some of these operations seem a little trivial, when they are done on a large dataset, they become an extremely important step to do before proceeding to the next step.

>An example on consolidation is to find all instances of "new york" and "New York" and tell OpenRefine that these should be written in the same way. This has the advantage of standardizing your data to make it easier to product visualizations and to analyze the information in the future.
This will often occur in historical documents during the OCR process of documents and often happens these days during collaborative projects, where multiple people are inputting data in a spreadsheet.


When using OpenRefine, I did first find that I had to get used to some of the terminology as I am more comfortable with using spreadsheet data in Excel or ArcMap (GIS software). Once that barrier was overcome, I found myself conducting transformations on data in facets using expressions in their pop-up boxes. 

With dealing with large amounts of data and as was mentioned in the previous tutorial of using regular expressions, it's probably a good idea to create a back-up copy of your data. Even though OpenRefine has an excellent "undo" feature built in (this allows you to go back a few versions and clearly illustrates your steps), I find that it's still a good idea to work on a draft copy since there are many changes that occur automatically within the data that.

Once a user is complete cleaning their data using OpenRefine, they should be left with a nicely cleaned-up dataset for use for visual or interpretation purposes. Cleaning up data is an extremely important step, and one that I find gets less attention when compared to the actual final analyzed product. It reminds me of a quote that a few professors and IT people at work have said. "Garbage in, Garbage out". Suffice it to say, if you don't clean-up your data, your results and analysis will be worthless.
