# VK-views-date-scrapper
A simple tool to scrape information about the number of views and posted date of the videos on VK.com

Main goal of the tool is to automate obtaining information about the number of views and posted date of the videos on VK.com

If you want to use it you need to create .xlsx file and place there video urls about which you want to obtain the information, like: 

![data_file_sample](https://user-images.githubusercontent.com/45539133/184718555-9c53f098-24f6-4a6a-9ab0-8586e72d2fe0.jpg)

<b>Before first use:</b>
1) First of all you need to install Python:
    You can download it from the official site: "https://www.python.org/downloads/".
2) Next step is to install Python packages needed for scraper. To do that open Terminal in the project folder and run following command:
    "pip install -r requirements.txt"
3) Open config.yaml and provide needed info there.
4) Open terminal in project folder and run following command:
    "python VK_view-date_scrapper.py"
5) Results will be stored in new .xlsx file with Edited__ prexif
6) BONUS:
    I've also made 
    asynchronous version of the tool, which can massively speed up scrapping process, but to use it you need your own proxy list, otherwise VK won't let       you go that fast. If you want to try it just place your proxies in config file and run "python asynchronous_VK_view-date_scrapper.py"
