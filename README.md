The process

This project sought to analyse the oral arguments at the Supreme Court using regular expressions. To first do this required accessing the transcripts of the arguments on the website of the Supreme Court. This was done using BeautifulSoup.

These transcripts were then matched with the respective cases, using the docket numbers, a unique identifier.

The result of this was a dataframe that showed the cases by docket numbers, summary of the case as well as dates of publication.

In order to get the transcripts, BeautifulSoup was used to download multiple pdfs and converted to text files.

These text files made it for easier analysis using regular expressions.

But before the analysis, regular expressions was deployed to clean the text files which had characters that could hamper the any regex code to analyze the set of text files.

The next output, a dataframe, saw the transcribed oral arguments matched to other details of their respective cases i.e title, docket numbers, date etc. Here, it was possible to just select a number of cases and read their arguments.
