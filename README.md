# scraping_simple_text_with_selenium

## Importing Libraries
![image](https://github.com/user-attachments/assets/945935f9-af88-4e09-835e-9dfe69d7b97e)

### This line imports the **webdriver** module from Selenium, which provides tools to control web browsers programmatically.

![image](https://github.com/user-attachments/assets/3032b36b-709b-410d-bf35-753e852778e5)

## Creating Chrome Options
![image](https://github.com/user-attachments/assets/fa56a4a0-59ba-41b7-81f6-7a1c4b2c37c7)

### disable-infobars: Hides the "Chrome is being controlled by automated software" infobar.

### start-maximized: Starts the browser in maximized mode.

### disable-dev-shm-usage: Disables the use of /dev/shm for shared memory to avoid certain errors

### no-sandbox: Disables the sandboxing feature for security reasons (may be needed in some environments).

### excludeSwitches=["enable-automation"]: Hides the automation switch message in the browser.

### disable-blink-features=AutomationControlled: Helps in avoiding detection of automated control by web pages.

visit any website copy the url

#### for example :
![image](https://github.com/user-attachments/assets/d10ff78a-e078-4d64-a2d1-c766e7320aa6)

click any word
![image](https://github.com/user-attachments/assets/cc11a6f1-2a59-4e30-b87c-aef19fac24ee)

inspect -> click copy -> click copy full xpath

then paste that x path here :
![image](https://github.com/user-attachments/assets/6607a09a-57f9-4a11-94ac-144f72f5347d)

# output:
![image](https://github.com/user-attachments/assets/0b586819-f875-43ee-8afd-bbc1719e75b9)








