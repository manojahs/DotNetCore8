

![image](https://github.com/user-attachments/assets/b8d6659a-a61b-450c-8abf-a7198735da6a)

Endpoints are routes that handle HTTP requests (e.g., GET /api/weather).

Appsetting.json
----------------
"ConnectionStrings": {
  "MyConnectionString": "Server=.;Database=NZWalksDb;Trusted_Connection=true;TrustServerCertificate=true"}
}


Run EF Core Migration
--------------------
add-migration "name"
update-database
