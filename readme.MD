# Blueprint Repo
A Repo to show source controlled blueprints updated by automation.

### Directory structure
- blueprint_src - container folder that holds all source controlled blueprints
    - each subfolder is the blueprint id
    - each commit message is prepended with blueprint name for logical mapping convenience
- blueprint_id_mapping.json
    - a top level reference of all blueprints being maintained in repo
    - blueprint id is key in the JSON table, with the blueprint name as value
    - automation process that commits new blueprints will update this table



