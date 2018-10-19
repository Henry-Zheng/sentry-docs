---
# This file is automatically generated from the API using `api-docs/generate.py`
# Do not manually this file.
{
  "api_path": "/api/0/projects/{organization_slug}/{project_slug}/files/dsyms/", 
  "authentication": "required", 
  "description": "Retrieve a list of debug information files for a given project.", 
  "example_request": "", 
  "example_response": "", 
  "method": "GET", 
  "parameters": null, 
  "path_parameters": [
    {
      "description": "the slug of the organization the file belongs to.", 
      "name": "organization_slug", 
      "type": "string"
    }, 
    {
      "description": "the slug of the project to list the DIFs of.", 
      "name": "project_slug", 
      "type": "string"
    }
  ], 
  "query_parameters": null, 
  "sidebar_order": 5, 
  "title": "List a Project's Debug Information Files", 
  "warning": null
}
---