[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5501307.svg)](https://doi.org/10.5281/zenodo.5501307)

# covid-texas-data

Archive data files from the [Texas COVID-19 Data website](https://www.dshs.state.tx.us/covid-19-coronavirus-disease-2019/texas-covid-19-data) and organized by date (`YYYY-MM-DD`). Texas DSHS briefly stopped regular data releases for many files in August 2022, but resumed in mid-December 2022.

## My Visualizations

* [Texas COVID-19 Hospital Resource Usage](https://covid-texas.csullender.com/)
* [Texas COVID-19 Vaccine Tracker](https://covid-texas.csullender.com/vaccine/)

## Data Files Overwritten Weekly by Texas DSHS

_These files are overwritten weekly (on Wednesdays) during the dashboard update process so retaining past versions is the only way to access historical values for certain metrics._

* [Accessible Dashboard Data](AccessibleDashboardData/): Excel file containing the underlying data currently displayed on the [COVID-19 Dashboard](https://www.dshs.state.tx.us/coronavirus/cases.aspx). Data are displayed on multiple tabs and include daily and cumulative case and fatality data, estimated recoveries, statewide hospital data.
* [Accessible Vaccine Dashboard Data](AccessibleVaccineDashboardData/): Excel file containing the underlying data currently displayed on the [COVID-19 Vaccine in Texas Dashboard](https://tabexternal.dshs.texas.gov/t/THD/views/COVID-19VaccineinTexasDashboard/Summary).

## Data Files Overwritten Monthly by Texas DSHS

_These files are overwritten monthly (on the 15th) during the update process so retaining past versions is the only way to access historical values for certain metrics._

* [Case and Fatality Demographics Data](CaseAndFatalityDemographicsData/): Excel file containing demographics data for COVID-19 fatalities and confirmed cases.

### Data Files Updated Weekly by Texas DSHS

_These files are amended weekly (on Wednesdays) with the latest numbers but retroactive changes can result in past values being silently updated._

* Confirmed Cases
  * [Confirmed Cases over Time by County](ConfirmedCasesOverTimeByCounty/)
  * [New Confirmed Cases over Time by County](NewConfirmedCasesOverTimeByCounty/)
* Probable Cases
  * [Probable Cases over Time by County](ProbableCasesOverTimeByCounty/)
  * [New Probable Cases over Time by County](NewProbableCasesOverTimeByCounty/)
* [Fatalities over Time by County](FatalitiesOverTimeByCounty/)
* [Combined Hospital Data over Time by Trauma Service Area (TSA)](HospitalDataOverTimeByTSA/)

## No Longer Being Updated by Texas DSHS

* [Texas Vaccine Provider Data](TexasVaccineProviderData/): CSV file containing the underlying data currently displayed on the [COVID-19 Vaccine Provider Dashboard](https://tdem.maps.arcgis.com/apps/webappviewer/index.html?id=3700a84845c5470cb0dc3ddace5c376b) (Last updated 2021-06-10)
* [Estimated Active Cases over Time by County](EstimatedActiveCasesOverTimeByCounty/) (Last updated 2022-01-13)
* [Cumulative Tests by Type by County](CumulativeTestsByTypeByCounty/) (Last updated 2022-04-06)
* [Cumulative Tests over Time by County](CumulativeTestsOverTimeByCounty/) (Last updated 2022-04-06)
* [COVID-19 Vaccine Administration Data by ZIP Code](VaccineAdministrationByZipCode/) (Last updated 2022-11-28)
