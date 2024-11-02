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

  <li>   Top 3 public repo contributors are working for <a href="">
              Apple, MMTechSoft & Stealth Startup   </a>

</li>
          <li>    They had most of the contributions in Javascript, Java, Scala and HTML in this order
</li>
          <li>    Github Users from Hyderabad working in Google, did not have a single repository published
</li>
</ul>
</p>
      
![Logo](Project-1-Findings.jpg)
