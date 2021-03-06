# Voynich Project

welcome to my Voynich Project

Don't open the notebook until you do all the installation stuff.

## Installation (for C9)

I use C9. It's dope. It's sometimes hard to install stuff. You will need the following stuff 
for this to work. BEFORE ALL THIS you need install anaconda, which you can get directions for
[here](https://medium.com/p/b40eba4df49/edit).

1. nltk (NLP program) `conda install nltk`
2. BeautifulSoup (web scraper) `pip install beautifulsoup4`
3. matplotlib (graphing) `conda install matplotlib`
4. numpy (matrix stuff) `conda install numpy`

You will need to download the following files (use `curl -O`) (alternatively, clone this repository):
1. [Enhanced Voynich Dataset](http://www.voynichese.com/1/data/folio/voynichese_data.zip)
2. [Moby Dick from Project Gutenberg](https://www.gutenberg.org/files/2701/old/moby10b.txt)

To unzip files, use `unzip` from the command line.

## Citations
@inproceedings{CrossLanguageDatasetLREC2016,
  TITLE = {{A Multilingual, Multi-Style and Multi-Granularity Dataset for Cross-Language Textual Similarity Detection}},
  AUTHOR = {J{\'e}r{\'e}my Ferrero and Fr{\'e}d{\'e}ric Agn{\`e}s and Laurent Besacier and Didier Schwab},
  BOOKTITLE = {{The 10th edition of the Language Resources and Evaluation Conference (LREC 2016)}},
  ADDRESS = {Portoro{\v z}, Slovenia},
  YEAR = {2016},
  MONTH = May,
  KEYWORDS = {Cross-language plagiarism detection ; Dataset ; Cross-language dataset ; Cross-language similarity detection ; Evaluation},
}
