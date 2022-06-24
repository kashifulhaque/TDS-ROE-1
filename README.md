# ROE 1

Date: June 25, 2022 7:30 PM-8:30 PM
Type: 🔍 Exam

# IMPORTANT NOTE

**Make sure you’re logged in to your student email ID to access those Colab Notebooks**

### To open/view DBF files

[https://www.dbfopener.com/](https://www.dbfopener.com/)

### To open/view Shapefiles (can also open DBF)

[https://mapshaper.org/](https://mapshaper.org/)

### Excel sheet to scrape weather data

[Week 2 Lecture 2 - Scrape Weather data.xlsx](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_2_Lecture_2_-_Scrape_Weather_data.xlsx)

### How to scrape weather data from a website into an excel sheet

Example URL: [https://www.timeanddate.com/weather/india/chennai/ext](https://www.timeanddate.com/weather/india/chennai/ext)

- Copy the URL
- Go to Excel
    - Then go to **Data** tab
    - Choose **New Query** or **Get Data**
    - Choose **From Other Sources** and then **From Web**
    
    ![Untitled](ROE%201%204e1e2f1090994424a80c23e239c15c98/Untitled.png)
    
- Paste in the URL

![Untitled](ROE%201%204e1e2f1090994424a80c23e239c15c98/Untitled%201.png)

- Choose Table View in Table 0 and click on **Load**

![Untitled](ROE%201%204e1e2f1090994424a80c23e239c15c98/Untitled%202.png)

- Double click to open query editor

![Untitled](ROE%201%204e1e2f1090994424a80c23e239c15c98/Untitled%203.png)

- To transform the table, select the columns required and delete them

![Untitled](ROE%201%204e1e2f1090994424a80c23e239c15c98/Untitled%204.png)

---

### BBC Weather Location API with Python

**Jupyter Notebook 👇**

[Week_2_Lecture_3_BBC_Location ID_Weather_Scraping.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_2_Lecture_3_BBC_Location_ID_Weather_Scraping.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/18OjJLjhXq9BOBfRorQ7yYWOTqBhVT-At](https://colab.research.google.com/drive/18OjJLjhXq9BOBfRorQ7yYWOTqBhVT-At)

**Example API URL 👇**

```
https://locator-service.api.bbci.co.uk/locations?api_key=AGbFAKx58hyjQScCXIYrxuEwJh2W2cmv&stack=aws&locale=en&filter=international&place-types=settlement%2Cairport%2Cdistrict&order=importance&s=los%20angeles&a=true&format=json
```

---

### Scrape weather data from BBC Weather

**Jupyter Notebook 👇**

[Week_2_Lecture_4_BBC_weather_scrape.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_2_Lecture_4_BBC_weather_scrape.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/1WN-Iaf3uJ4APNIlOa95hqwOYXUC3Np__](https://colab.research.google.com/drive/1WN-Iaf3uJ4APNIlOa95hqwOYXUC3Np__)

**Example API URL 👇**

```
https://locator-service.api.bbci.co.uk/locations?api_key=AGbFAKx58hyjQScCXIYrxuEwJh2W2cmv&stack=aws&locale=en&filter=international&place-types=settlement%2Cairport%2Cdistrict&order=importance&s=mumbai&a=true&format=json
```

---

### Scrape top 250 movies from IMDb

**Jupyter Notebook 👇**

[Week_2_Lecture_5_Web_Scraping_IMDb.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_2_Lecture_5_Web_Scraping_IMDb.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/1Kwi14Twb6cnPPu850dKuo1VtTctoBqG5](https://colab.research.google.com/drive/1Kwi14Twb6cnPPu850dKuo1VtTctoBqG5)

---

### Geocoding using Nominatim

**Jupyter Notebook 👇**

[Week_2_Lecture_6_Geocoding_using_Nominatim.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_2_Lecture_6_Geocoding_using_Nominatim.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/1cKOxglTK8aGoWMZfd2y5PoHo2DRXHF_z](https://colab.research.google.com/drive/1cKOxglTK8aGoWMZfd2y5PoHo2DRXHF_z)

⚠️ **IMPORTANT NOTE** ⚠️

```
If you get a HTTP Error 403 from Nominatim
use your email ID instead of “myGeocoder” in Nominatim
(user_agent="myGeocoder")
```

---

### Wikipedia data using Wikimedia library

**Jupyter Notebook 👇**

[Week_2_Lecture_7_Wikipedia_Library.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_2_Lecture_7_Wikipedia_Library.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/1UZky5JdOn2oMYIkls23WefTaT8VinYyg](https://colab.research.google.com/drive/1UZky5JdOn2oMYIkls23WefTaT8VinYyg)

---

### Scrape PDF using Tabula

**Jupyter Notebook 👇**

[Week_2_Lecture_8_PDF_Scraping_Tabula.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_2_Lecture_8_PDF_Scraping_Tabula.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/1mNhUTij7LdsjxgcfOKgfsmbFOI526y2t](https://colab.research.google.com/drive/1mNhUTij7LdsjxgcfOKgfsmbFOI526y2t)

---

### Practice Assignment 2

- To load an excel sheet as a pandas dataframe (*assume pandas is imported as pd*)
    
    ```python
    link = 'https://rbidocs.rbi.org.in/rdocs/Content/DOCs/IFCB2009_85.xlsx'
    data = pd.read_excel(link)
    ```
    
- Get the latitude and longitude of a city (stored in a variable named `city`)
    
    ```python
    locator = Nominatim(user_agent="myGeocoder")
    location = locator.geocode(city)
    print("Latitude = {}, Longitude = {}".format(location.latitude, location.longitude))
    ```
    
- A python code snippet to download PDF files
    
    ```python
    import requests
    from bs4 import BeautifulSoup
    from urllib.parse import urljoin
    import os
     
    url = 'https://www.premierleague.com/publications'
    folder_location = r'/content/drive/MyDrive/Colab Notebooks/premier_league'
    if not os.path.exists(folder_location):
        os.mkdir(folder_location)
     
    response = requests.get(url)
    soup = BeautifulSoup(response.text, "html.parser")     
     
    for link in soup.select("a[href$='.pdf']"):
        filename = os.path.join(folder_location, link['href'].split('/')[-1])
        with open(filename, 'wb') as f:
            f.write(requests.get(urljoin(url,link['href'])).content)
    ```
    

### Graded Assignment 2

- Beautiful Soup is the library used to parse HTML contents
    - It has methods like `find` and `find_all`
- The following piece of code scrapes data about football scores and presents in a structured form of HTML/CSS tags as available in the given URL
    
    ```python
    from bs4 import BeautifulSoup as bs
    
     import requests
    
     r = requests.get("https://www.espn.in/football/scoreboard")
    
     soup = bs(r.content)
    
     contents = soup.prettify()
    ```
    
- A piece of code to scrape the following HTML snippet
    
    ```html
    <head>
    	<title>An e-commerce website</title>
    </head>
    <div class='footer'>
    	<p>Information about the Organization</p>
    </div>
    ```
    
    ```python
    org = soup.find(‘div’, class_=’footer’)
    orginfo = org.p.text
    print(orginfo)
    ```
    
    **Code to extract the title of a webpage** 👇
    
    ```python
    title = soup.title.text
    print(title)
    ```
    

---

### Scrape assembly election results

**Jupyter Notebook 👇**

[Week_3_Lecture_1_election.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_3_Lecture_1_election.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/1SP8yVxzmofQO48-yXF3rujqWk2iM0KSl](https://colab.research.google.com/drive/1SP8yVxzmofQO48-yXF3rujqWk2iM0KSl)

---

### To split text into several columns

- Select the column
- Go to **Data** tab and choose **Text to Column**
    - Choose **Delimited**
        
        ![Untitled](ROE%201%204e1e2f1090994424a80c23e239c15c98/Untitled%205.png)
        
    - Choose from a list of delimiters or enter your own
        
        ![Untitled](ROE%201%204e1e2f1090994424a80c23e239c15c98/Untitled%206.png)
        

---

### Pandas Profiling

**Jupyter Notebook 👇**

[Week_3_Lecture_6_pandas_profile.ipynb](ROE%201%204e1e2f1090994424a80c23e239c15c98/Week_3_Lecture_6_pandas_profile.ipynb)

**Google Colab URL:** [https://colab.research.google.com/drive/1xgbs_xJe8hQVV6ot9Qsk5gnQLKsiwudW?usp=sharing](https://colab.research.google.com/drive/1xgbs_xJe8hQVV6ot9Qsk5gnQLKsiwudW?usp=sharing)

---

### Practice Assignment 3

- A separate Excel report gets generated while running `ProfileReport()` function in pandas profiling
- In pandas profiling, we use **“Toggle Details”** to find quantile statistics
- `Trim()` function is used to remove additional spaces between characters in Excel
- The clustering method “Nearest neighbour” in the ‘OpenRefine’ tool uses **Edit distance** to cluster texts
- Sparklines are used to find trends in the data in Excel

---

### Graded Assignment 3

- Code snippet to save a `.jpg` file as a `.png`
    
    ```python
    from PIL import Image; i = Image.open(‘hello.jpg’); i.save(‘hello.png’)
    ```
    
- Code snippet in the pillow library to blur images
    
    ```python
    Image.filter()
    ```