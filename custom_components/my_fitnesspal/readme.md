# Swedish recycling station component
This custom component checks the recycling station (återvinningsstation). 
Check https://www.ftiab.se/173.html to search for your specifc recycling station. You will need the unique id of the station when configuring the component.

## Usage
Copy the all files from "swedish_recycling" to folder `custom_component/swedish_recycling` folder under config root

The component will create a binary_sensor with the state on if the date you shoose in `use_as_state` is today. The rest of the properties will show as attributes. You can only choose one of the options as state in `use_as_state`

## Configuration
```yaml
binary_sensor:
  - platform: swedish_recycling
    entities:                           
      matfors:                        # name of entity
          station_id: '10421'         # unique station id
          use_as_state: 'NextCarton'  # what to display as state, can only choose one here
```
|property|description|
|---|---|
|station_id|unique id, please se [here](https://www.ftiab.se/173.html) to find the id of your station
|use_as_state|**Use one of the following:** LastCleaning, NextCleaning, LastColoredGlass, NextColoredGlass, LastGlass, NextGlass, LastCarton, NextCarton, LastMetal, NextMetal, LastPlastic, NextPlastic, LastPapers, NextPapers
|   |   |

