#Install-selenium
#Download-FireFox-WebDriver
from selenium import webdriver
firefox = webdriver.Firefox(executable_path="#import-Your-WebDriver-Address")
firefox.get('https://web.whatsapp.com/')
#First-Answer-inputs-And-Then-Scan-QR-Code
name = input('Enter the name of user or group : ')
msg = input('Enter your message : ')
count = int(input('Enter the count : '))
input('Enter anything after scanning QR code')

user = firefox.find_element_by_xpath('//span[@title = "{}"]'.format(name))
user.click()

msg_box = firefox.find_element_by_xpath('//*[@id="main"]/footer/div[1]/div[2]/div/div[2]')
for i in range(count):
    msg_box.send_keys(msg)
    firefox.find_element_by_xpath('//*[@id="main"]/footer/div[1]/div[3]/button').click()
    
   
#Instagram ==> _.hesampv
#Telegram ==> @hesamzs
