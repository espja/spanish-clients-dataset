# Synthetic dataset containing Spanish people data

The Spanish Clients Synthetic Dataset is a dataset built with Spanish demographical data. It also includes a variation including duplicates and errors.

All datasets are **utf-8** encoded and **comma** separated. They have been divided in two due to file size restrictions in github.

# Original Dataset

It can be found in the files named clients_dataset_*.csv.

The original dataset contains random clients generated following the demographic data available at *[Instituto Nacional de Estadística](https://www.ine.es/)*. It contains the following fields:
| FIELD| DESCRIPTION  |
|--|--|
|KEY  | Unique key |
|PROVINCE|Province Code|
|PROVINCE_NAME| Province name|
| STREET | Street name |
|BRITH_YEAR| Birth year|
|City| City |
|EMAIL | Email|
|POSTAL_CODE| Postal code|
|SEX|Sex(m/f)|
|BIRTH_DATE |Birth Date (DD/MM/YYYY)|
|NAME| Name|
|LAST NAME| Last name|
|SECOND LAST NAME| Second last name|
|Phone| 9-digit Phone number|
|DNI| National ID code|


The fields generated following a real world distribution are: 
Province/Province_name, Birth year, City, postal code, sex, name, last name, second last name. 

Streets are assigned randomly depending on the town but don't follow a frequency distribution. 

More information about how the data was generated here. 



## Dataset with errors and duplicates

It can be found in the files named ds_w_errors_duplicates_*.csv.

This dataset has been generated for entity resoluytion purposes. It contains 10% of duplicated clients and a 20% artificially generated mistakes rate. Clients containing errors can have from 1 to 5 errors randomly. Each client's errors are stated at the *ERROR* column. 

Some names are modified by their hipocorism to simulate data variations, the original name is saved in the ORIGINAL_NAME column. 



