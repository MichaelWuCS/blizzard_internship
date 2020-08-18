# blizzard_internship
This is a repository dedicated to my internship at Blizzard Entertainment in the summer of 2020. I was the intern for the IT Corporate Applications team where I worked on developing ThinkGlobally, a project aiming to asssociate real world locations with their corresponding geographical coordinates. This program was coded in JavaScript, specifically in Vue.js. Since I cannot upload the code that I created during this internship, I have uploaded a pdf of my SharePoint page displaying the highlights of my internship. 

# Project Description
ThinkGlobally is a Vue program whose primary purpose is to map associate amenities and other points of interests with their latitude and longitudes. While we can drop pins on Google Maps, we need to know the internal structure of the building to be more precise. By knowing the latitude and longitude of every single conference room in each building, we can automatically populate a map with all of the relevant points of interest. To do so, we create map. By knowing the exact latitude and longitude of simply two points on the map, we can calculate the latitude and longitude of every other location on the map assuming that the two points of interest are not coolinear. From there, creating a point of interest is as easy as dragging a point around on the map. This information is then persisted in a NoSQL database. To achieve this end, I also wrote the backend of the API along with validation rules in both the backend and frontend. Additionally, this was deployed to the Blizzard intranet so that any Blizzard employee could access this by going to /dev-thinkglobally. 

# Tools Utilized
Visual Studio Code
Ghosthub
Jenkins
Ocotopus
Portainer
Postman

