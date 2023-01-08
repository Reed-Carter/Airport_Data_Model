# Airport Data Model

#### By Reed Carter

#### A Data Warehousing Exercise 

## Technologies Used

* github
* python
* pandas
* jupyterlab
* BigQuery

## Description

In this repo, an ETL pipeline was developed in order to normalize airline ticket information into facts and dimension tables and loads the tables into a bigquery dataset. A diagram of the ETL diagram and the ERD of the data warehouse can be found below.



[<img src="./images/ETL_pipeline_diagram.png"/>](./images/ETL_pipeline_diagram.png)
[<img src="./images/data_warehouse_ERD.png" width='700'/>](./images/data_warehouse_ERD.png)


## Setup/Installation Requirements

* Clone this repository to your desktop
* Navigate to the top level directory
* Run 'pip install -r requirements.txt' to install all the requirements so that main.py can run correctly
* Open load_dims.ipynb and run all cells
* Open load_facts.ipynb and run all cells

## Known Bugs

* no known bugs

## License

MIT License

Copyright (c) [2022] [Reed Carter, Chloe Le, Phil Kendall]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.