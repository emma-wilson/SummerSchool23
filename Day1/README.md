# Day 1

## Seminar: What's the internet archive?
*Speaker: Jessica Witte*

Jessica's research involved webscraping and cleaning data from the Internet Archive. Her talk offered an introduction to webscraping.

The aim of the internet archive is to collect and curate information from the internet, including web pages, podcasts, texts, videos, and images. 
Brewster Kahle, the founder of Internet Archive, envisioned the Internet Archive as a digital "Library of Alexandria". 
Internet Archive is accessible to everyone and anyone can add to it.
However, not all publishers agree with Kahle's vision and Internet Archive has recently lost a copyright lawsuit.

We know from research that digitial libraries have a problem with bias and overrepresentation (e.g. popularity and mainstream languages). 
Other barriers include technology limits. Digitised texts are only as accurate as the OCR technology that produced them, digital tools differ between institutions, and not all physical objects are suitable for digitisation.
Copyright laws mean that most of the texts we have available for text analysis are historical. However, technological barriers can prevent these texts being used computationally.

As Internet Archive's database is user-drive, Jessica was interested in seeing what texts, authors and genres were represented in the Internet Archive and if Internet Archive could be considered a library.

To answer the first question, Jessica relied on accurate metadata describing the text's authors, etc. 
However, most metadata is machine-generated and may not always be accurate. 
Jessica's dataset comprised over 33 million texts, 13% of which needed metadata to be manually annotated. 
445 languages were represented, however English-language bias was significant and top contributors were libraries and government organisations.

Jessica encountered various problems during her research. Traumatic and violent texts were intersperced with books and magazines. This was considered as part of her second question, "what is a library?", as it brings up questions about what sort of texts should be preserved.
Additionally, machine-generated metadata erased information about minority language texts. Copyright laws, legal cases, and API subscriptions are major barriers to webscraping and may put future preservation of digital materials at risk.

## Webscraping
Webscraping is the extraction of data from a website. Webscrping allows researchers to do "big qualitative" data analysis. The session started with a short presentation by James Besse about webscraping.

### What is HTML?
HTML is the standard markup used for creating the structure and content of websites. 
HTML tags are the building blocks of a HTML document and HTML attributes also provide additional information about HTML elements.
CSS selector gadgets are web-based tools that allow us to target specific parts of HTML, just like the inspect tool in web browsers. 
This can help select specific data to scrape from a website.

### Webscraping approaches
There are three main approaches to webscraping:

- **Crawl** and scrape HTML / XML
- Application programming interfaces (**APIs**)
- **Web browser automation** using tools such as Selenium or Puppeteer

### Law and Ethics
Some websites specifically ban webscraping in their terms of service, so it may not always be legal. 
However, it's not always clear whether permission is needed to webscrape.

### Practicalities
Webscraping requires you to be better at writing and editing code than as required by statistical modelling. 
Web data is messy and you will have to do extensive cleaning. 
Additionally, websides may be internally and externally inconsistent in how text and HTML is formatted.
What works for one website will unlikely work for other websites, and may not work for every page on that website.
Often, websites will change. They will also try to block scrapers.

## Practical
In Day One's practical session, we used the [rvest](https://rvest.tidyverse.org/index.html) package, which is part of the tidyverse.

The session aims were to:

- Automatically extract news items from the UK Government website News sections on the cost of living
- Do the same for the Scottish Government website
