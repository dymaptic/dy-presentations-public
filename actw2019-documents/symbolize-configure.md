## Symbolize bike data

In `Contents`, click `Portland Bike Data` and `Change Style` and select the following:

1. Choose an attribute to show: `BicycleStatus`
2. Select a drawing style:
    - In Types (Unique symbols) click Options and set the following:
        - Set color for neutral roads:
            - To the left of the `Neighborhood Street`, click the `Change Symbol` line
            - Add `#7570b3` in the hexadecimal color box
            - Click Ok to close the window.
            - Do the same for `Shared Lane` and `Other`
        - Set color for calm roads:
            - To the left of the `Designated Bikelane`, click the `Change Symbol` line
            - Add `#1b9e77` in the hexadecimal color box
            - Click Ok to close the window.
            - Do the same for `Neighborgood Greenway`, `Off-street Path or Trail` and `Protected Bikelane`
        - Set color for busy roads roads:
            - To the left of the `Highway`, click the `Change Symbol` line
            - Add `#d95f02` in the hexadecimal color box
            - Click Ok to close the window.
        - Click Ok > Done

## Configure popups

In `Contents`, click on `Portland Bike Data` > More Options ... > Configure Pop-up and set the following:

- Popup-Title: {BicycleStatus}
- Click Configure Attributes:
    - Uncheck all of the fields (Hint: At the top, select and unselect the Display checkbox.)
    Check the following and set the Field Alias:
        - {StreetName} Street Name
        - {RoadTypeOSM} Road Type in OSM
        - {Elevation} Elevation     
        - {OneWay} One Way
    - Use the up and down arrows to re-order the fields.
- Click OK
- Click on some `Portland Bike Data` features to view the styled pop-up.

## Publish web app
- Click `Save As` to save your map
- Click `Share`
    - Click `CREATE A WEB APP`
