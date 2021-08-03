# igcomment.py

from selenium import webdriver
from selenium.webdriver.common.keys import keys
import time

driver = webdriver.Chrome('chromedriver.exe')
driver.get('http://instagram.com')

time.sleep(3)

a = driver.find_elements_by_class_name('Look into Developer tools id code')[0]
a.send_keys('Insert IG account ID')

a = driver.find_elements_by_class_name('Look into Developer tools id code')[1]
a.send_keys('Insert IG account Password')
a.send_keys(Keys.ENTER)

time.sleep(3)

a = driver.find_elements_by_class_name('Look into Developer tools id code')[0]
a.click()

driver.find_elements_by_css_selector('#react-root form input')[0]

#''' Use the code below and scrap the instagram posts comment '''
driver.get('https://www.instagram.com/explore/tags/sllo/?hl=en' + i.a['href'])
for i in insta:
    (a = driver.find_elements_by_class_name('comment code')[0].get_text)
    print(a)

#'''  Use the code below and scrap the instagram post comment '''
a = driver.find_elements_by_class_name('comment code')[0].get_text
print(a)

time.implicitly_wait(5)

#''' Use the code below and bring the instagram post image '''
a = driver.find_elements_by_class_name('post code').get_attribute('src')
print(a)

time.implicitly_wait(5)

#''' instagram comment bot '''
a = driver.find_elements_by_class_name('comment class name')[0]
a.click()
a = driver.find_elements_by_class_name('comment class name')[0]
a.send_keys('leave the comments')
a.send_keys(Keys.ENTER)

time.sleep(6)
