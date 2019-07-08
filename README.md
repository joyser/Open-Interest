# Open-Interest

Simple HTML and javascript script to retrieve Open interest from OKex futures, every 2 seconds (usually how often it refreshes), and print the last 30 results to a HTML table. 

Script uses a proxy server to get around Cross Origin Request blocking policy.


Setup:

1) Download index.html file

2) Close all windows and instances of chrome

3) Open chrome using the following command in the run  (windows + r): chrome.exe -–allow-file-access-from-files

4) Open index.html in chrome, and add add a pair AND lookback so the URL looks like this: index.html?pair=EOS-USD-190628&lookBack=30

lookBack is the number of data points to display before it starts cutting the old ones
