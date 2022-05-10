need to do a short study for home appliance products listed on lowes. 
I wrote a piece of python code to web scrape lowes home appliance category, it works smoothly at the beginning, but suddenly my code stops working. Tried to switch proxy ips but still failed. 
Then i switched to a 3rd party vendor and sourced the data smoothly, <a href="https://barkingdata.com/?crawlers/lowes-crawler.html"> https://barkingdata.com/?crawlers/lowes-crawler.html So far it works well.

I used pandas to load the raw data to memroy and i'm able to analyze the data using dataframe now. 

Pandas lib:
http://pandas.pydata.org/pandas-docs/stable/10min.html

http://pandas.pydata.org/pandas-docs/stable/cookbook.html#cookbook


import pandas

import openpyxl


data_end = []

wb = pandas.DataFrame(data_end[:-2])

wb.to_excel('lowes.xlsx')

wb.to_html('lowes.html')

wb.to_csv('lowes.csv')
————————————————
