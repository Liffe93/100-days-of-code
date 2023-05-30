# 100 Days Of Code - Log

### Day 0: May 17, 2023 

**Today's Progress**: Understanding how to traverse Linux  

**Thoughts:** Having a scrip that informs me of the computer's memory, cpu, 777 files 

**Link to work:** https://github.com/Liffe93/bash/blob/main/basicInfo

### Day 1: May 18, 2023

**Today's Progress**: webscrapping html code in python

**Thoughts**: I want to automate this more. Where you enter the script name and a url and it can scrape more than the html. However, this is a good spot to start. 

**Link(s) to work**: https://github.com/Liffe93/OSINT/blob/main/request.HTML.py


### Day 2: May 21, 2023 

**Today's Progress**: Learning webscrapin from XSS RAT 

**Thoughts** he had a cool crawler.txt that I want to look at... This was mostly a review on awk and sed. 

**Link(s) to work**
<img width="480" alt="Screen Shot 2023-05-21 at 7 39 59 PM" src="https://github.com/kallaway/100-days-of-code/assets/111470998/cbd77bfc-9c2f-4e0b-b114-7d6fb3061ca4">

### Day 3: May 21, 2023 

**Today's Progress**: Working on portscanning 

**Thoughts** This is important coding skill to fully understand and commit to memory. Port scanning can be used to determine the security posture of a system, find open portts annd services, and identify potenttial targetts for malicous attacks. 

**Link(s) to work**
nmap -iL targets.txt
nmap --script=http-shellshock <target> 
  #list all website pages and direcory 
nmap --script=http-sitemap-generator <target>
  #DNS server snooping
nmap --script=dns-cache-snoop <target>

**### Day 4: May 22, 2023 **

**Today's Progress**:  Learning how to connect Google Drive API to python to run a webscrapping to Google Sheets script 

**Thoughts** Got the OAUTH 2.0 clientt-secret key downloaded and able to connect drive API to end-point. Was not able to get the main.py from the Corona-websscraping github to work. The issue states: "not found import scripts.sheets as gsheet and covid19_data" 

**Link(s) to work** 
Inspiration is from (https://github.com/binarynightowl/corona_webscraper) 
Needed to understand how to connect drive api to python  🐍  (https://developers.google.com/drive/api/quickstart/python) 
Found a great youtube video to follow: Python Project for Beginners | Browser automation and web scraping craigeslist (https://www.youtube.com/watch?v=s9jT2fVqNME) Will ues that tomorrow to scrape data on a musician that needs help creating a database of his music, splits and numbers.
  
 
### Day 5: May 23, 2023 

**Today's Progress**: Researching how to better implement git

**Thoughts** git is a tool to manage CI/CD. Branches are made to contain any edits. Commits are recorded in a log and you can go back to any past iteration whenever + copy it to the master code if something goes wrong. GitHub needs git... yet, it doesn't need github. 

**Link(s) to work** https://www.youtube.com/watch?v=USjZcfj8yxE 
git status
  git add
  git commit 
  git branch 
  
  
### Day 6: May 24, 2023 

**Today's Progress**: Found some potential clients that would need a web scraper to gather artists royalty data. Will begin focusing my work on building this. 

**Thoughts** was able to download the HTML of an artists song register to BMI. 
  NEED Select() ideas

**Link(s) to work**
  import requests
res=requests.get('https://repertoire.bmi.com/Search/Catalog?num=KcdW2xRlEMR23Xhvza%252fmtA%253d%253d&cae=YO0HedHMatLb45JzS23DVw%253d%253d&partType=PerformerList&search=%7B%22Main_Search_Text%22%3A%22omer%20netzer%22%2C%22Sub_Search_Text%22%3Anull%2C%22Main_Search%22%3A%22Performer%22%2C%22Sub_Search%22%3Anull%2C%22Search_Type%22%3A%22all%22%2C%22View_Count%22%3A20%2C%22Page_Number%22%3A0%2C%22Part_Type%22%3Anull%2C%22Part_Id%22%3Anull%2C%22Part_Id_Sub%22%3Anull%2C%22Part_Name%22%3Anull%2C%22Part_Cae%22%3Anull%2C%22Original_Search%22%3Anull%2C%22DisclaimerViewed%22%3Anull%7D&resetPageNumber=True')
res.raise_for_status()
playFile=open('PlaceToStart.Omer.BMI.txt', 'wb')
for chunk in res.iter_content(1000000):
    playFile.write(chunk)

    
27428

  -- took MDW off --
 ### Day 7: May 30, 2023 

**Today's Progress**: Still working on helping a media company back log their music royalties. Testing out download homebrew and wget 

**Thoughts** 

**Link(s) to work**
  https://docs.brew.sh/Installation
  https://www.cyberciti.biz/faq/howto-install-wget-om-mac-os-x-mountain-lion-mavericks-snow-leopard/
  https://gist.github.com/stvhwrd/985dedbe1d3329e68d70

  
  
  future project ideas: 
  https://www.youtube.com/watch?v=jAfQvMxcokI
  https://developers.google.com/apps-script/guides/menus
