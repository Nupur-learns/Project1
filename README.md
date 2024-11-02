## IITM Tools in Data Science Project 1 - Moscow 50

### 1. Scraping mechanism <a href="https://github.com/Nupur-learns/Project1/blob/main/gitscrap1.py">(VSCode)</a>

I scraped the data from the Github site using the github API with a personal access token <br>
             GITHUB_TOKEN =  'personal-token' <br>
             HEADERS = {'Authorization': f"token {GITHUB_TOKEN}", <br>
                        "Accept": "application/vnd.github.v3+json" <br>
             } <br>
      
USERS: https://github.com/Nupur-learns/Project1/blob/main/users.csv

REPOSITORIES: https://github.com/Nupur-learns/Project1/blob/main/repositories.csv

response = requests.get(<above-url>, headers=HEADERS)

   <p align="left">
<ul>

### 2. Some facts discovered from the analysis:

  <li>   The top 5 users in Moscow with the highest number of followers are <a href="https://github.com/Nupur-learns/Project1/blob/main/users.csv">
              maxlapshin,veged,alexeyr,alec-c4,alno    </a>

</li>
          <li>   The majority of these developers work at YANDEX
</li>
          <li>    A correlation coefficient of 0.054 means there is a very weak positive correlation between the number of followers and the number of public repositories among users in Moscow. Also, the correlation for additional followers a user gets per additional public repository is 0.221 showing some weak positive correlation. Hence, though less, having an additional public repository does give some hopes for having additional followers.
</li>
</ul>
</p>
      

