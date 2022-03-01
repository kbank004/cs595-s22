# Keshaun Banks Assignment 3
To complete this assignment I wrote 2 python programs.
1) ``main.py`` Performs reads the sites from ``sites.txt`` and then performs all the requests and generates the data to be stored in ``results.json``

2) ``table.py`` is then ran, and it generates the markdown table from the data in ``results.json``

### Note
* I removed 5 problematic sites from my list. As explained in the Google group, these sites were either down or didn't have a DNS record at all

To run this yourself, you must install ``requests`` and ``pytablewriter``. To do so run ``pip install -r requirements.txt``. Then run main.py to generate the JSON file and run table.py afterwards to generate the markdown file
which contains the table.

##(Copied from table.md)
# Results
|        Sites         |Status Code|Cookie Count|HttpOnly|Secure|SameSite|SameSite Strict|SameSite Lax|SameSite None|Path|Non-default Path|
|----------------------|----------:|-----------:|-------:|-----:|-------:|--------------:|-----------:|------------:|---:|---------------:|
|abcnews.go.com        |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|about.com             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|accounts.google.com   |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|alibaba.com           |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|amazon.co.uk          |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|amazon.de             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|amazon.es             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|amzn.to               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|as.com                |        302|           2|       0|     0|       0|              0|           0|            0|   2|               0|
|bbc.co.uk             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|berkeley.edu          |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|biblegateway.com      |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|bild.de               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|bitly.com             |        405|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|box.com               |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|britannica.com        |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|cambridge.org         |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|clarin.com            |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|code.google.com       |        200|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|deezer.com            |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|digitaltrends.com     |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|disqus.com            |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|dot.tk                |        302|           3|       0|     0|       0|              0|           0|            0|   3|               0|
|dw.com                |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|ebay.co.uk            |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|enable-javascript.com |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|engadget.com          |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|eonline.com           |        301|           1|       1|     0|       1|              1|           0|            0|   1|               0|
|espn.com              |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|example.com           |        200|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|fastcompany.com       |        301|           2|       0|     0|       0|              0|           0|            0|   2|               0|
|fda.gov               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|feedburner.com        |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|fifa.com              |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|forms.gle             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|fortune.com           |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|gettyimages.com       |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|globo.com             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|gnu.org               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|goo.gl                |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|google.com.br         |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|google.fr             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|google.pl             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|googleblog.com        |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|gooyaabitemplates.com |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|hbr.org               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|huffingtonpost.com    |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|ietf.org              |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|imgur.com             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|kakao.com             |        302|           1|       0|     1|       0|              0|           0|            0|   1|               0|
|line.me               |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|m.wikipedia.org       |        301|           2|       0|     2|       2|              0|           0|            0|   2|               0|
|mail.ru               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|mediafire.com         |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|medium.com            |        301|           1|       0|     1|       0|              0|           0|            0|   1|               0|
|mercurynews.com       |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|mit.edu               |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|mixcloud.com          |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|nationalgeographic.com|        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|newyorker.com         |        301|           4|       2|     0|       3|              0|           0|            2|   4|               0|
|ok.ru                 |        200|           2|       0|     2|       2|              0|           0|            0|   2|               0|
|outlook.com           |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|ovh.net               |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|pbs.org               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|pcmag.com             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|picasaweb.google.com  |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|politico.com          |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|prezi.com             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|python.org            |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|rakuten.co.jp         |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|researchgate.net      |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|sciencedaily.com      |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|sedo.com              |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|slideshare.net        |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|surveymonkey.com      |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|ted.com               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|thefreedictionary.com |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|translate.google.com  |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|un.org                |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|uol.com.br            |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|usda.gov              |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|utexas.edu            |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|video.google.com      |        200|           1|       1|     0|       1|              0|           0|            0|   1|               0|
|wa.me                 |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|weather.com           |        301|           1|       0|     0|       1|              0|           0|            0|   1|               0|
|wikia.com             |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|wikihow.com           |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|wikimedia.org         |        301|           2|       0|     2|       2|              0|           0|            0|   2|               0|
|wp.com                |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|wsj.com               |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|www.weebly.com        |        301|           6|       0|     0|       0|              0|           0|            0|   6|               0|
|xda-developers.com    |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|yadi.sk               |        302|           0|       0|     0|       0|              0|           0|            0|   0|               0|
|yandex.ru             |        301|           3|       0|     0|       1|              0|           0|            0|   3|               0|
|zendesk.com           |        301|           0|       0|     0|       0|              0|           0|            0|   0|               0|

### Min: 0 

### Max: 6 

### Median: 0 

### Mean: 3.064516129032258 

        