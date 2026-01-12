# RoR Reimagined

Data mod that reimagines the Return of Rome expansion with counter, regional and unique units for the "Return of Rome"
mode in Age of Empires 2: Definitive Edition.

Requires the UI mod at https://github.com/LucioDavid/RoR_Reimagined_UI

## String Modding - `.txt`

Techs and Units/Buildings have usually 5 **strings**:

1. Hotkey name: ID may be unrelated to the others
2. Ingame name: `main name ID`
3. Tech Tree name: `main name ID` + `10000` (it seems that only Techs follow this rule)
4. Short description: `main name ID` + `1000`
5. Long description (extended tooltip): `main name ID` + `21000`

They have also an **extra ID**:

1. Help String ID: `main name ID` + `100000`

## Tech Tree Modding - `.json`

Tech Tree Node snippet with commentaries:

```Json
        {
          "Age ID": 3,
          "Building ID": 12,
          "Draw Node Type": "UnitTech",
          "Help String ID": 405504, // Calculated from base name string ID + 100000
          "Link ID": 7,
          "Link Node Type": "Unit",
          "Name": "Elite Slinger", // Only for reference
          "Name String ID": 314355, // `Tech Tree name`; used only on the Tech Tree
          "Node ID": 2341, // Unit's ID in the `.dat` file
          "Node Status": "ResearchedCompleted",
          "Node Type": "UnitUpgrade", // Only the base unit is of type 'Unit'
          "Picture Index": 135, // Defined at '...\modes\Pompeii\widgetui\icons.json'
          "Prerequisite IDs": [
            0,
            0,
            0,
            0,
            0
          ],
          "Prerequisite Types": [
            "None",
            "None",
            "None",
            "None",
            "None"
          ],
          "Trigger Tech ID": 191,
          "Use Type": "Unit"
        },
```

## Hotkey Modding - `.json`

Hotkey snippet with commentaries:

```Json
            {
               "data_name": "STABLE_CREATE_SWORD_HORSEMAN", // Only for reference
               "name_string_id": 19127, // `Hotkey name` string
               "defaults_list": [
                  {
                     "name": "classic",
                     "key": "R"
                  },
                  {
                     "name": "definitive",
                     "key": "W"
                  },
                  {
                     "name": "high definition",
                     "key": "F"
                  },
                  {
                     "name": "left handed",
                     "key": "U"
                  }
               ],
               "string_index_list": [
                  16746 // Used to bind this hotkey definition with the Unit/Tech etc. that is going to use it.
               ]
            },
```