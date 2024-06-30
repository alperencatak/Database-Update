# ツ Subject 
Update of the database. Demonstration of how a new road changes the path. 

# ツ Data
OpenStreetMap<br />https://github.com/banbar/harita.hacettepe.edu.tr

# ツ Aim and objectives:

<p align="justify">The purpose of this project is to update the database in the back-end of a site built with JavaScript.</p>

<p align="justify">In the field of geographic information systems (GIS), accurate and up-to-date data is crucial for effective spatial analysis and decision-making. One such application is the representation and analysis of road networks within a given area. This project focuses on the process of updating a database to incorporate changes brought about by the construction of a new road and subsequently demonstrating how this alteration affects existing pathways. I utilized QGIS, a powerful open-source GIS software, to visualize and analyze the impact of the new road on the existing road network and associated pathways. With its ability to visualize and analyze spatial data, QGIS and the website creation language JavaScript play an important role in enabling users to make informed decisions and plan for efficient and sustainable urban development.</p>

<p align="justify">The initial step in this project is to update the database with the new road data. The newly constructed road is acquired through reliable sources such as government records, satellite imagery, or field surveys. This information is then integrated into the existing road network dataset within the PostgreSQL database. I created my path and node point in QGIS. Inseted all metadata. After the creating these, I updated the database directly with PostGIS extension. The updated database ensures that the new road is accurately represented and accessible for subsequent analysis.</p>

<p align="justify">To demonstrate the impact of the new road on pathways, a comparison is made between the pre-existing pathways and the updated road network. Using QGIS and JS, after the update spatial datas, I evaluated the new road's influence on pedestrian and transportation routes. I identified areas where new connections are formed, existing pathways that are affected or disrupted, and potential alternative routes resulting from the new road's construction.</p>

<p align="justify">In conclusion, updating a database to incorporate changes brought about by the construction of a new road is a crucial task in GIS analysis. By utilizing QGIS, JS and PostgreSQL, I effectively demonstrated the impact of the new road on existing pathways. I showcased the importance of accurate and up-to-date data, enabling decision-makers to assess the implications of infrastructure development on transportation networks and pedestrian accessibility.</p>

# ツ Project Steps
<p align="justify">(The steps before linking the database are available in the group report.)</p>
<p align="justify">Firstly, I linked the database of https://harita.hacettepe.edu.tr.</p>

![link to qgis](https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/669b064f-fbe0-4a09-9389-b657e8c5e100)

<p align="justify">Then, I searched the deficiency or updateable thing. I found this road. This road existing in the provider OpenStreetMap but not exist in this project.</p>

![qgis no road](https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/426d481d-d75c-43fb-bcbd-368244e5d3ef)

<p align="justify">After that, I created road and its node.</p>

![nodes](https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/6174641c-4dcb-4fb9-b77e-a303089e9e8f)

![road update](https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/44b5def7-ff20-4139-97a7-bb456d36011e)

<p align="justify">After the saving, I checked the database on "PostgreSQL" and done.</p>

![after saving 2](https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/fa18dcc3-9940-4c4f-ac55-96a8a0381523)

![after saving](https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/3439c204-72bf-4283-9b91-d1e851185259)

<p align="justify">Finally, I started the client and check the shortest path.</p>

## <p align="center"> Before
![before](https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/8ed812ea-b683-4ec6-8825-241d1439a120)
## <p align="center"> After
<img width="1440" alt="after" src="https://github.com/GMT-352/final-project-individual-alperencatak/assets/118128475/c78db56f-45c5-4e22-841c-a2b2be9ecdc3">
