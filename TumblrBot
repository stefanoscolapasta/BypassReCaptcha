from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
from selenium.webdriver.support import expected_conditions
import pyautogui, time

browser = webdriver.Chrome('C:\\Python\\chromedriver')
browser.get('https://tumblr.com//')

body = browser.find_element_by_css_selector('body')
body.send_keys(Keys.PAGE_DOWN)
tasto_accetto = browser.find_element_by_xpath('/html/body/div[4]/div/div/div/div[2]/div/button[2]')
tasto_accetto.click()
browser.implicitly_wait(5)
tasto_inizia = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/button[1]/span[1]')
tasto_inizia.click()
browser.implicitly_wait(5)
email = "YOUR@EMAIL.com"
password = "YOUR_PASSWORD"
nome_utente = "YOUR_USERNAME"
email_box = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/div[1]/div/form/div[3]/div[1]/input')
email_box.send_keys(email)
password_box = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/div[1]/div/form/div[3]/div[2]/input')
password_box.send_keys(password)
nome_utente_box = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/div[1]/div/form/div[3]/div[3]/input')
nome_utente_box.send_keys(nome_utente)
registrati_box = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/button[1]/span[3]')
registrati_box.click()
anni_box = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/div[1]/div/form/div[4]/div[1]/div/input')
anni_box.send_keys('20')
browser.implicitly_wait(20)
accetta_condizioni_box = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/div[1]/div/form/div[4]/div[2]/input')
browser.implicitly_wait(20)
browser.execute_script("arguments[0].click();", accetta_condizioni_box)
avanti_box = browser.find_element_by_xpath('/html/body/div[2]/div[1]/div[3]/div[1]/button[1]/span[4]')
avanti_box.click()
pyautogui.moveTo(804, 556, 5)
pyautogui.click()
