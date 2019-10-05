# DeLorean
Back to the future to estimate cars prices

## About the project

**Delorean** is a machine learning project developed during the Ironhack Data Analysis bootcamp.

> Wait a minute, Doc. Ah... Are you telling me that you built a time machine... out of a DeLorean? (Marty McFly, 1985)

### Prerequisites

Install the needed libraries for the project:

```
pip3 install pandas
pip3 install numpy
pip3 install re
```

### Source

The project uses an uploaded dataset for the competition in Kaggle:

- [Kaggle](https://www.kaggle.com/c/datamad0819-vehicles/data) - Original source

### Files structure

- **main.ipynb**: Jupyter file with the project

Folders:

- data: exchange files (.csv)
- libraries: custom Python libraries
- stumbles: pieces of code that incite suicide

### Dataset info

Fields include:

- *Id*
- *city*
- *price*
- *year* - Year of manufacturing
- *manufacturer* - Manufacturer of vehicle
- *make* - Model of vehicle
- *condition* - Vehicle condition
- *cylinders* - Number of cylinders
- *fuel* - Type of fuel required
- *odometer* - Miles traveled
- *title_status* - Title status (e.g. clean, missing, etc.)
- *transmission* - Type of transmission
- *drive* - Drive of vehicle
- *size* - Size of vehicle
- *type* - Type of vehicle
- *paint_color* - Color of vehicle
- *lat* - Latitude of listing
- *long* - Longitude of listing
- *county_fips* - Federal Information Processing Standards code
- *county_name* - County of listing
- *state_fips* - Federal Information Processing Standards code
- *state_code* - letter state code
- *state_name* - State name
- *weather* - Historical average