# U.S. Cities in GeoJSON format

List of cities in the United States converted to GeoJSON

Use db_import.geojson to import to MongoDB.
Make sure to include --jsonArray at the end of your mongoimport command.

Example:

mongoimport -h [[DB_HOST]] -port [[PORT]] -d [[DB_NAME]] -c [[COLLECTION]] -u [[USER]] -p[[PASSWORD]] --file db_import.geojson --jsonArray
