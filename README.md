## IITM Tools in Data Science Project 1 - Moscow 50

### 1. Scraping mechanism <a href="">(VSCode)</a>

I scraped the data from the Github site using the github API with a personal access token <br>
             GITHUB_TOKEN =  'personal-token' <br>
             HEADERS = {'Authorization': f"token {GITHUB_TOKEN}", <br>
                        "Accept": "application/vnd.github.v3+json" <br>
             } <br>
      
USERS: https://github.com/Nupur-learns/Project1/blob/main/users.csv

REPOSITORIES: 

response = requests.get(<above-url>, headers=HEADERS)

   <p align="left">
<ul>
