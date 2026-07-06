# M4-BD

# Riwi Supply 

It is a Sales and Billing Management database, also known in the business world as the Revenue Cycle. These purchases are made by multiple Colombian companies through suppliers, who are responsible for marketing and distributing the products.

# Technologies used
- DBDiagram
- Docker Desktop
- pgadmin 4
- VISUAl STUDIO CODE

# Database engine used:
- postgres
  
# Explanation of normalization process.
- 1NF: The file was already normalized in this way because it already had atomic values ​​and no duplication in attributes.
- 2NF: I separated the entities to eliminate partial dependencies.
- 3NF: Transitive dependencies are eliminated, allowing each table to store only information specific to its entity.

# Entity Relationship Model.
<img width="1200" height="1098" alt="MER" src="https://github.com/user-attachments/assets/d0d1c3c7-653c-46ad-ada2-32c369bcf356" />


# Instructions to create the database.
- First I activated the database in Docker. Once the server was active, I opened pgAdmin 4. Since I already had a server group, I created a server. Inside, I created the server, and in the public schema, I created the tables with their attributes.

# Instructions to load data.
- First I saved the Excel file as a CSV file and exported it in pgAdmin 4.

# Developer information:
Camila Isabel Marrugo Tamara
Clan: Magdalena.
