import requests
from bs4 import BeautifulSoup

url = 'https://www.bike24.com/backpacks-hydration-packs.html?menu=1300,1350,1357&__qf_form-filter=&mid[367]=1&sort=price_desc'
response = requests.get(url)
soup = BeautifulSoup(response.text, 'lxml')

print(soup)
