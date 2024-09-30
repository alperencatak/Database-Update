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

![1](https://github.com/user-attachments/assets/8a38031e-4808-407c-b390-bc5c7c23c4ef)

<p align="justify">Then, I searched the deficiency or updateable thing. I found this road. This road existing in the provider OpenStreetMap but not exist in this project.</p>

![2](https://github.com/user-attachments/assets/23781214-581c-4827-831e-1e2c6f7f96b0)

<p align="justify">After that, I created road and its node.</p>

![3](https://github.com/user-attachments/assets/02d3da91-ff09-420c-8f69-82a0237e559a)

![4](https://github.com/user-attachments/assets/e0186b68-e84c-4a80-8702-12dfde26c4f2)

<p align="justify">After the saving, I checked the database on "PostgreSQL" and done.</p>

![5](https://github.com/user-attachments/assets/b283456f-91dc-4886-b0cf-29ec535396ff)

![6](https://github.com/user-attachments/assets/e8f34d28-2c1a-4888-a89d-497420016376)

<p align="justify">Finally, I started the client and check the shortest path.</p>

## <p align="center"> Before
![7](https://github.com/user-attachments/assets/d9965d77-8f66-415a-8674-8f9d873ae67a)
## <p align="center"> After
<img width="1440" alt="8" src="https://github.com/user-attachments/assets/9ae6cde5-41dc-4775-8351-d08995ed53cd">
