# spanish-clients-dataset

The Spanish Clients Dataset is a public dataset built with Spanish demographical data. It also includes some variations including duplicates and siblings.

All datasets are **utf-8** encoded and **comma** separated.

# Original Dataset

The original dataset contains random clients generated following the demographic data available at *[Instituto Nacional de Estadística](https://www.ine.es/)*. It contains the following fields:
| FIELD| DESCRIPTION  |
|--|--|
|KEY  | Unique key |
|PROVINCE|Province Code|
|PROVINCE_NAME| Province name|
| STREET | Street name|
|BRITH_YEAR| Birth year|
|City| City 
|....

More information about how the data was generated here. 



## Dataset with errors and duplicates

This dataset has been generated for [master data management](https://en.wikipedia.org/wiki/Master_data_management) purposes. It contains 10% of duplicated clients and a 20% error rate. Clients containing errors can have from 1 to 5 errors randomly. Each client's errors are stated at the *ERROR* column. 

## Dataset with errors, duplicates and siblings

A dataset was generated simulating that 5% of clients where siblings. This means they share some information like Last name and second last name, and in some cases the address and birth date. 

