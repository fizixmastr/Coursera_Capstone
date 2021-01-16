
<div align="center">
  
# Neighborhoods in Joensuu Finland

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fizixmastr/Coursera_Capstone/HEAD) [![image](https://img.shields.io/badge/Author-Charles%20Rambo-orange)](https://github.com/fizixmastr) [![image](https://img.shields.io/badge/-LinkedIn-grey?style=flat&logo=linkedin&labelColor=blue)](https://fi.linkedin.com/in/charles-rambo?trk=profile-badge)
</div>

## Project Description
[Map of Joensuu](https://github.com/fizixmastr/IBM_Data_Science_Capstone/blob/main/map.png)

In previous assignments, it has been shown that Python packages may be used to highlight the key attractions of a city. The city I currently live in is Joensuu, Finland. Joensuu is a "college town" with two universities and a generally small population which means roughly 13% of the cities residents are students. This means that one of the largest (if not largest) providers of housing in the city is the student housing company, Elli. Elli maintains at least 40 different housing complexes across seven neighborhoods in the city. While most apartments are simply assigned as they become available from the waiting list, it is possible to request certain housing complexes. At this time, however, they provide only a little information about the complex/flat, and no information about the neighborhood or its proximity to key city features such as the City Center, and the universities.

My plan is to develop a tool that will be able to provide a "snapshot" of the neighborhoods in order to help Elli and its residents find better matches to their neighborhood wants and needs. I hope to achieve this by leveraging the FourSquare API to establish what kinds of features are most common in the neighborhoods as well as the distance that the neighborhood is from the key city features such as those already mentioned above. Further by applying machine learning it will be possible to suggeest how similar neighborhoods are to each other, in the case that Elli does not have availabilty in a tenants desired neighborhood.Aside from the FourSquare API providing information on the attractions, it will also be necessary to find location information for the neighborhoods and city features. Hopefully this data may be collected through scraping, howevere given the nature of Joensuu I believe this will have to be retreived manualy. Maps will ofcourse be necessary as well and are available from the folium package. Then the goal will be to present this information in well designed manner that is both attractive and easy to use.

## Results 
[Results1](https://github.com/fizixmastr/IBM_Data_Science_Capstone/blob/main/table.png)
By collecting the data regarding the amenities that are near by each housing location we have been able to acheive 2 important results that may be important to both the leasing company Elli and their potential clients. First, both parties may now take advantage of knowing the types of businesses/activities which are comon in the neighborhood. The advantages to future tenants should be obvious. If it is important to the student that they have access to night life they now know that Etu-Noljakka has Pizza and Bars near by. On the other hand if a grad-student with a dog or family is looking for a quieter living condition they can focus on complexes in Kanervala. For Elli this helps them suggest locations to their tenants. Before moving on from the results presented in the table is that for students either with mobility issues that need to live close to the school, or perhaps students who study best at home it is now possible for them to understand how far away from their campus or the City Center the neighborhood is.

[results2](https://github.com/fizixmastr/IBM_Data_Science_Capstone/blob/main/map.png)

## Conclusions
Overall these results illustrate the power of applying machine learning and to data that has been scraped from the internet. As well as the power for python packackes to execute this work in a reliable manner. 
The other key result of this work was been establishing the similarities that exist between neighborhoods. Again this is an important take away for Elli as it will allow them to find alternative neighborhoods for people who have spent long times on the waiting list by suggesting one similar.
