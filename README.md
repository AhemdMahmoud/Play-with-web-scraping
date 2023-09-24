# Play-with-Web-Scraping
### This project scrapes a web page for football match details on a specific date entered by the user and saves the data to a CSV file, including the teams' names, the match time, and the result.
## Quick Start
### Want to play with these notebooks online without having to install anything?

<a href="https://colab.research.google.com/github/AhmedMahmoud1D/Play-with-Web-Scraping/blob/main/WebScrap.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> (recommended)
  
⚠ _Colab provides a temporary environment: anything you do will be deleted after a while, so make sure you download any data you care about._

### Just want to quickly look at some notebooks, without executing any code?

* <a href="https://nbviewer.org/github/AhemdMahmoud/Play-with-web-scraping/blob/main/WebScrap.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a>
* [github.com's notebook viewer](https://github.com/AhemdMahmoud/Play-with-web-scraping/blob/main/WebScrap.ipynb) also works but it's not ideal: it's slower, the math equations are not always displayed correctly, and large notebooks often fail to open.
## Want to install this project on your own machine?
#### 1.Clone the repository to your local machine.
#### 2.Install the required libraries: csv, requests, and beautifulsoup4.
~~~
!pip install beautifulsoup4
!pip install lxml
!pip install requests

~~~





#### 3.Run the program from the command line using the following command: python main.py.
#### 4.Enter the desired date in the format `yyyy-mm-dd`.
![## True Format](https://user-images.githubusercontent.com/118063610/230723845-e1082d34-ed24-4fd5-9093-c86a67c3ce27.png)
#### 5.The program will scrape the matches details and save them in a CSV file named matches.csv in the same directory as the program.
![](https://user-images.githubusercontent.com/118063610/230724139-a9a62309-7399-47a2-a1a8-0b7d55942355.png)
# Dependencies

### This project depends on the following libraries:

- [x] csv: to write the matches details to a CSV file.
- requests: to send HTTP requests to the website.
- beautifulsoup4: to parse the HTML response and extract the required information.
# Notes
#### The program saves the matches details to a CSV file named matches.csv

# Visit  [yallakora Website](https://www.yallakora.com/match-center/%D9%85%D8%B1%D9%83%D8%B2-%D8%A7%D9%84%D9%85%D8%A8%D8%A7%D8%B1%D9%8A%D8%A7%D8%AA?date=6/4/2023#days)
