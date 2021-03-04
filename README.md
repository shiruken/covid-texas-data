# covid-texas-data

Archive data files from the [Texas COVID-19 Data website](https://www.dshs.state.tx.us/coronavirus/additionaldata/) and organize by date (`YYYY-MM-DD`).

#### My Visualizations
* [Texas COVID-19 Hospital Resource Usage](https://covid-texas.csullender.com/)
* [Texas COVID-19 Vaccine Tracker](https://covid-texas.csullender.com/vaccine/)

### Data Files Overwritten Daily by Texas DSHS

_These files are overwritten daily during the dashboard update process so retaining past versions is the only way to access historical values for certain metrics._

* [Accessible Dashboard Data](AccessibleDashboardData/): Excel file containing the underlying data currently displayed on the [COVID-19 Dashboard](https://www.dshs.state.tx.us/coronavirus/cases.aspx). Data are displayed on multiple tabs and include daily and cumulative case and fatality data, estimated recoveries, statewide hospital data.
* [Accessible Vaccine Dashboard Data](AccessibleVaccineDashboardData/): Excel file containing the underlying data currently displayed on the [COVID-19 Vaccine in Texas Dashboard](https://tabexternal.dshs.texas.gov/t/THD/views/COVID-19VaccineinTexasDashboard/Summary).
* [Texas Vaccine Provider Data](TexasVaccineProviderData/): CSV file containing the underlying data currently displayed on the [COVID-19 Vaccine Provider Dashboard](https://tdem.maps.arcgis.com/apps/webappviewer/index.html?id=3700a84845c5470cb0dc3ddace5c376b).
* [Case and Fatality Demographics Data](CaseAndFatalityDemographicsData/): Excel file containing demographics data for COVID-19 fatalities and confirmed cases. Updated weekly on Friday.
* [COVID-19 Vaccine Administration Data by ZIP Code](VaccineAdministrationByZipCode/): Excel file containing vaccine administration data based on recipient ZIP Code. Updated weekly on Monday.

### Data Files Updated Daily by Texas DSHS

_These files are amended daily with the latest numbers but retroactive changes can result in past values being silently updated._

* Confirmed Cases
  * [Confirmed Cases over Time by County](ConfirmedCasesOverTimeByCounty/)
  * [New Confirmed Cases over Time by County](NewConfirmedCasesOverTimeByCounty/)
* Probable Cases
  * [Probable Cases over Time by County](ProbableCasesOverTimeByCounty/)
  * [New Probable Cases over Time by County](NewProbableCasesOverTimeByCounty/)
* [Fatalities over Time by County](FatalitiesOverTimeByCounty/)
* [Estimated Active Cases over Time by County](EstimatedActiveCasesOverTimeByCounty/)
* Testing
  * [Cumulative Tests by Type by County](CumulativeTestsByTypeByCounty/)
  * [Cumulative Tests over Time by County](CumulativeTestsOverTimeByCounty/)
* [Combined Hospital Data over Time by Trauma Service Area (TSA)](HospitalDataOverTimeByTSA/)
