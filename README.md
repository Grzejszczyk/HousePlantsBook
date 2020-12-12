# HousePlantsBook
This is application which can help user to manage all activities aroud houseplants.

#### One user can has few plantation.
User should separate plantations if they are on separated areas / environment.

#### All profiled plants can has own:
- ###### Main Data:
```
- Name (PL, EN, Latin),
- Description,
- Date acquisition,
- Thumbnail,
- Galery (see how growing),
- List of activities: (watering, fertigation, transplantations etc.)
- Place (insolation),
- neighboring plants (allelopathy)
```
- ###### Reminders about watering and other cases:
```
- Action name for plant:
- Cyclic action (true / false)
- DateTime for action (if cyclic true -> list of actions)
- Description of action
```
###### Galery
```
- Table with thumbnails
- Normal size photo (Name, Description, DateTaime for picture)
```
###### TimeLine for each plant
```
- Actions
- Photos (thumbnails)
- Issues, remarks, other observations
```