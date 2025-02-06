---
title: "College Football Risk Scripts"
layout: post
categories: undergraduate
---

After playing the game [College Football Risk](https://collegefootballrisk.com), I decided to step into a game developer role, specifically helping to create scripts that assist with team planning during each turn of the game.

For a specific turn in the game, I will calculate odds for each team territory, legal territories to attack/defend for the following turn, and MVP shoutouts for players on the team. 
The code can be found here: [College Football Risk Team Scripts](https://github.com/shen3340/CFB-Risk-Scripts/tree/main/Daily%20Team%20Scripts). 
For non-technical individuals, I have created a Shiny App that will allow you to still use the scripts without running any code at 
[College Football Risk Shiny App (currently archived)](https://shen3340.shinyapps.io/Teams/).

Since some players have expressed displeasure with the RNG of the turns in the game, I decided to create a daily blog that dispels complaints of the game RNG having favorites for any specific team.
Using data manipulation and visualization in R, I post summary statistics of "luck" for each team, combining territory win chances and statistical methods to output which teams had a lucky roll and whcih teams didn't.
For my daily blog posts, I have histograms showing the percentage of each team having their corresponding luck for that roll along with other relevant statistics, and specific territories that had "lucky" wins. 
The blog link can be found on my [WordPress](https://shen3340.wordpress.com), and the code can be found here: [College Football Risk Summary Scripts](https://github.com/shen3340/CFB-Risk-Scripts/tree/main/Daily%20Summary%20Scripts). 
