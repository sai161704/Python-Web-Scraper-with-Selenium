from selenium import webdriver
from selenium.webdriver.common.by import By

driver = webdriver.Chrome()
driver.get('https://example.com')

element = driver.find_element(By.XPATH, '//h1')
print(element.text)

driver.quit()
# Python-Web-Scraper-with-Selenium
