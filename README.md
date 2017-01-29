# Reformatting-Data-using-BeautifulSoup
Web scraping using Beautiful Soup to retrieve data that exists on any website, and convert it into a format that is usable for analysis.

DESCRIPTION 

Reformatting Data
Steps to follow while executing:( Ran in Linux)
transform.py
1) Make sure python3 is installed.
2) Make sure BeautifulSoup is installed.The following link explains how to install BeautifulSoup.
http://www.crummy.com/software/BeautifulSoup/bs4/doc/
3) Execute python3 transform.py .The extracted portion will be displayed.
4) Alternatively, the output of the program will be saved in result.csv.It can be opened and verified.


Description of output:
1)The html file is opened using urlopen.
2)Use BeautifulSoup to read the html file.
3)The "wikitable sortable" table is extracted.
4)After teh table is extracted we obtain the data for each field that we want from the table. 
2)The output is displayed in the form game_number ,year_s , win , score , losing_team ,venue
