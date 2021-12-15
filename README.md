# data-512-project
UW Data 512 Project A4 - A7 
Project goal:Analyze Covid confirmed cases and PCR Tests data and find relation between these varaibles. 

License and terms of use:
All the data used for this analysis is publicly avialble and included their source details in data decsription below.

Data sources:
* Covid confirmed cases: Aggregate COVID-19 case counts and rates by date of report. Counts include both confirmed and probable cases, and a person is counted as a case only once.
  * Data Source: COVID-19 Aggregate Cases Current Daily County Health | PA Open Data Portal
  * License: Public Domain U.S. Government
  * Attributes:
      * Jurisdiction: Pennsylvania County of residence 
      * Date: Case reported date
      * New Cases: Number of new confirmed and probable cases first reported to the Department of Health on that date
      * 7-day Average New Cases: Rolling 7-day average of new confirmed and probable cases
      * Cumulative cases: Cumulative confirmed and probable cases reported through that date
      * Population (2019): Most current population data available
      * New Case Rate: Number of new confirmed and probable cases reported that date per 100,000 population

*	Covid test volume: Daily aggregates of COVID-19 PCR test results reported to the Department of Health. It includes tests with positive, negative, and inconclusive results. If the same test result (identified by having the same patient, collection date, and result) was reported more than once (either accidentally or reported by both the ordering facility and the performing lab), it is counted only once in this data. Only tests performed on Pennsylvania residents are included.
  * Data Source: COVID-19 PCR Test Counts March 2020 - Current Statewide Health | PA Open Data Portal
  * License: Public Domain U.S. Government
  * Attributes:
    * Date: The date the test result was reported to department of Health
    * New PCR Tests: Number of deduplicated PCR test results for Pennsylvania residents reported to the department of Health
* Covid death volume:
  * Data Source: COVID-19 Aggregate Death Data Current Daily County Health | PA Open Data Portal
  * License: Public Domain U.S. Government
  * Attributes: aggregate death data. Data set has additional columns like 7 day average, cumulative numbers, rate. I am not using those.
    * County Name:
    * Date of Death:
    * New Deaths: 
* Masking policy information- masking mandates by county
  * Citation: Data can be cited as: CDC, COVID-19 Community Intervention & Critical Populations Task Force, Monitoring & Evaluation Team, Mitigation Policy Analysis Unit, the CDC, Center for State, Tribal, Local, and Territorial Support, Public Health Law Program, and Max Gakh, Assistant Professor, School of Public Health, University of Nevada, Las Vegas, “U.S. State and Territorial Orders Requiring Masks in Public,” (August 15, 2021).
* Mask compliance survey - mask compliance survey
  * Citation: “The New York Times and Dynata”
