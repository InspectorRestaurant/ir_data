# ir_data
Data infrastructure for InspectorRestaurant

This repository provisions a [MongoDB](https://www.mongodb.com/) server, a [Mongo-Express](https://github.com/mongo-express/mongo-express) admin interface, and a [Jupyter](http://jupyter.org/) notebook server.

## Getting Started

### Prerequisites
- Docker + Docker-Compose (version?)

### Run the services
```
docker-compose up
```

### Getting the data
The inspection CSV datafiles are available from the following locations (links will auto-download CSV files):
- [New York State Inspection Data](https://health.data.ny.gov/api/views/2hcc-shji/rows.csv?accessType=DOWNLOAD)
- [New York City Inspection Data](https://data.cityofnewyork.us/api/views/43nn-pn8j/rows.csv?accessType=DOWNLOAD)

### License
[MIT License](http://opensource.org/licenses/MIT).
