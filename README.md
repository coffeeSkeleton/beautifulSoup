# beautifulSoup
Programs to test BeautifulSoup functionality

Just some simple code to experiment with web scraping

- Tomato Harvest goes through 2 pages of tomato seed listings on a gardening website and prints out the names of all the varieties available. Because there were two pages, I set up functionality to easily loop through both. If there were ever more pages added to the website for tomatoes, it would be easy to go in and update the code. For all pages, the program first downloads the webpage; then, grabs all 'span' elements, as these are the page elements that store the tomato names; next, it gets the text of all spans, and appends this text to a list; and finally, from this list all items that contain the word 'tomato', which all the tomato listings do, are printed out. Additionally, the word 'tomato' is stripped from the items before printing; we already know that these are tomatoes, so it's redundant information. 

- Chicken Soup goes through Oklahoma State University's list of chicken breeds and prints the title and main paragraph of chicken facts from each. Loop shortened not to go through whole imported list of links, as some were extraneous to the list of chicken breeds. Runs fairly slowly, probably because the program has to go to each individual web page and pull things from it. Troubleshooting: Some breed pages must not fit the same html schema as the rest, because no paragraph data prints under the titles, even though there is data on the actual web page. Can't think of a simple fix at the moment.
