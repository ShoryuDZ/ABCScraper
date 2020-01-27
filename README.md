# ABCScraper
A web scraper of the Australian Broadcasting Corporation's News Archive

This web scraper makes use of ABC Archive's bottom naivgation menu as well as systematic dating of URLs to find the location of all published articles from a certain day.
It then goes through and retrieves the content (headline, timestamp and text) of each one, saving to a word document.

As there are over 500,000 articles on the ABC, the script does take time to execute.

It uses BeautifulSoup to parse HTML, and python-docx to create the word file.

Please read [this](https://github.com/ShoryuDZ/ABCScraper/blob/master/DetailedInstructions.txt) for comprehensive instructions.
