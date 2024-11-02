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

### 2. Interesting fact from the analysis:

</li>
          <li>   Correlation coefficient of 0.054 between the number of followers and the number of public repositories among users in Moscow and 0.221 for additional followers a user gets per additional public repository shows weak positive correlation, contrary to common belief.
</li>
</ul>
</p>

### 3. An Actinable recommendation to developers based on analysis:
</li>
          <li>  Having an additional public repository is less likely to translate into a big spike in additional followers as the correlation coefficient is low (0.221), and hence other aspects should also be focused to increase the follower count.
