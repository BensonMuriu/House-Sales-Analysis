
# House Sales prediction in King county

 A real estate agency helps complete a real estate agency that helps
homeowners buy and/or sell homes. 

Business problem: A stakeholder  would like to know on how to increase the value of their homes.
 
Business question: The business question is how renovations might increase the value of their homes and by what amount? 


## Requirements
The system requires to use a jupyter notebook file having two to 
three models of the sytem that predicts house prices. To run the notebook 
file you will require to have pre-installed Anaconda environment.

A presentation of the results found after predicting should be well placed
for the stakeholders
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`Anaconda environment`




## Data 

The project uses King County house sales found in the data folder as `kc_house_data.csv` to show data of home owners who jave listed their homes for sale. The `column_names.md` file in the data folder describes the columns used in the data for better understanding.
The original dataset includes sales data for 21,597 homes with 20 different features, which include:

`date` -Date house was sold

`price `- Sale price (prediction target

`bedrooms` - Number of bedrooms

`bathrooms` - Number of bathrooms

`sqft_living` - Square footage of living space in the home

`sqft_lot` - Square footage of the lot

`floors` - Number of floors (levels) in house

`waterfront` - Whether the house is on a waterfront

`view` - Number of times house has been viewed

`condition` - How good the overall condition of the house is. Related to maintenance of house

`grade` - Overall grade of the house. Related to the construction and design of the house

`sqft_above` - Square footage of house apart from basement

`sqft_basement` - Square footage of the basement

`yr_built` - Year when house was built

`yr_renovated` - Year when house was renovated

`zipcode` - ZIP Code used by the United States Postal Service
## Acknowledgements

 - [Seaborn documentation](https://seaborn.pydata.org/#:~:text=Seaborn%20is%20a%20Python%20data,attractive%20and%20informative%20statistical%20graphics.)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [kc_county_data](https://kingcounty.gov/depts/assessor/Reports/area-reports/2016/~/media/depts/Assessor/documents/AreaReports/2016/Residential/034.ashx) 
 


## Authors

- [@BensonMuriu](https://github.com/BensonMuriu/)


## Run Locally

Clone the project

```bash
  git clone https://github.com/BensonMuriu/Phase-2-project
```

Go to the project directory

``` 
  cd Phase-2-project
```

Install dependencies

```bash
  conda install ipykernel
```

Start the server

```bash
  source activate `env`
```

