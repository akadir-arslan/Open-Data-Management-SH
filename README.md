# Open-Data-Management-Schleswig-Holstein

## Project Description

This repository demonstrates the use of Python for data management, focusing on RDF files, SPARQL queries, and the CKAN Action API. The project is based on data sets from the [Open-Data Schleswig-Holstein portal](https://opendata.schleswig-holstein.de).

The primary goal is to develop Python programs that explore linked data using RDF files, execute SPARQL queries, and interact with the CKAN API to access various data resources from the portal.

## Project Structure

### Files and Outputs

- **`schulen_sh.jsonld`**: RDF data for schools in JSON-LD format.
- **`kiel_polizeidienststellen.json`**: SPARQL query result for police stations in Kiel.
- **`kriminalpolizeistelle_sh.json`**: SPARQL query result for Criminal Investigation Departments ("Kriminalpolizeistelle").
- **Various JSON files**: Outputs of CKAN Action API queries, including organizations, packages, groups, resources, licenses, tags, and organization details.

### Python Scripts

1. **RDF File Processing**:
   - Downloaded RDF files for schools and police stations.
   - Demonstrated the use of RDFLib to parse RDF data and convert it to JSON-LD format.

2. **SPARQL Queries**:
   - Queried RDF data to extract information about police stations located in Kiel.
   - Additional query for Criminal Investigation Departments ("Kriminalpolizeistelle") in Schleswig-Holstein.

3. **CKAN Action API**:
   - Explored the Open-Data Schleswig-Holstein portal using CKAN API endpoints.
   - Queried for organizations, packages (datasets), groups, resources, licenses, tags, and detailed information about the "Kunsthalle Kiel" organization.

## How to Run

1. Ensure you have Python installed on your system.
2. Install the required packages:
   ```bash
   pip install rdflib urllib
## Additional Notes
- The outputs of all queries are saved as JSON files for easy access and readability.
- The output for Question-2 is saved as a JSON-LD file, as required by the project instructions.