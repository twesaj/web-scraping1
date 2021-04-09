# Web Scraping Part One
The purpose of this script is to extract an image from a web page. In this script we will be scraping an image of young Nelson Mandela from wikipedia using the BeautifulSoup library. The script uses the get request function to extract the URL 'https://en.wikipedia.org/wiki/Nelson_Mandela'. Then pass the contents of the page through BeautifulSoup so that it can be parsed.  Since I wanted the  image data, I used the img tag with BeautifulSoup. However the most  important part of the code is pulling the image is the src= tag… because this is the URL that i used to obtain the actual image I wanted.
The script returns a download of the image of a young Nelson Mandela.
