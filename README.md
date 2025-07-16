# **Orienteering Interrail Planner**

## Project overview
This project focuses on planning an optimized Interrail itinerary across Southern Europe (Portugal, Spain, France, and Italy) using mathematical modeling and integer linear programming. The main goal is to support sustainable and efficient cultural travel while respecting multiple constraints such as time, budget, and travel days.

The optimization problem has been formulated and solved using data from real-world sources and aims to balance tourism value with logistical feasibility.

## Objectives
- Maximize the overall tourism value of the trip
- Comply with the Interrail Global Pass constraints (7 travel days in 1 month)
- Stay within a fixed total budget
- Optimize time spent in each city and order of visits
- Promote sustainable cultural tourism in Southern Europe

## Scope of application
- Geographical area: Portugal, Spain, France, and Italy
- Cities considered: 40 candidate cities (10 per country), selected for cultural relevance and accessibility
- Pass type: Interrail Global Pass – “7 days within 1 month”
- Optimization problem type: Combinatorial / Integer Linear Programming

## Data Sources 
The Tourism interest index is based on the average rating of the 5 top attractions weighted on the number of ratings for each city on Tripadvisor. 
The Average daily cost has been estimated via platforms like BudgetYourTrip, blogs, and travel portals. It includes lodging, food, and local transportation.

## Project Structure
- Codes_Collab.py – Code implementing the optimization model   
- Codes_Collab.ipynb – Code implementing the optimization model  
- Poster.png – Outputs of the optimization in(e.g., chosen itinerary, total cost)  
- Ppt Presentation.pdf – Presentation slides summarizing the project (methodology, results, insights)  
- README.md – This file  
- Report.pdf – Full report including methodology, results, and discussion (if applicable)  
- interrail_data.xlsx – Contains city data (interest score and daily cost)    

## Output
- Optimal itinerary: cities to visit, duration of stay, order of visits
- Total tourism value
- Total cost
- Number of train travel days used

## Possible Extensions
- Add user preferences (e.g., prioritize art cities or coastal towns)
- Consider carbon footprint per route

## Authors
Luigina Bertolotti, Isabella Cappiello, Martina Pagan


Academic Year: 2024/2025, University of Studies of Brescia

