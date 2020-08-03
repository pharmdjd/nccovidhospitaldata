# nccovidhospitaldata
												
These data are compiled daily from the North Carolina DHHS COVID-19 Hospitalization Dashboard at: https://covid19.ncdhhs.gov/dashboard/hospitalizations

Preferred Acknowledgment: Hilary Campbell, PharmD, JD at the Duke-Margolis Center for Health Policy. My effort is partially funded by NCDHHS.

Contact hilary.campbell@duke.edu with questions	

Data incomplete between 6/24-6/29 (posting dates) due to changes in how data distributed/compiled.

FIELDS:

survey_date
Day the hospitals reported this day's data

survey_day_of_week
Day of the week hospitals reported. Weekends have lower response rates.

dhhs_posted_date
Day NCDHHS posted this data (from previous day's reports)

dhhs_posted_day_of_week
Day of the week that NCDHHS posted the data

total_pct_reporting
Percentage of hospitals that responded on this day

total_covid_census
Total number of hospitalized COVID-19 patients reported by hospitals on this day	

total_inpt_full_beds
Total number of inpatient beds in use by patients (for any indication) as reported by hospitals on this day.

total_inpt_empty_beds
Total number of inpatient beds that are staffed and available as reported by hospitals on this day.

NOTE: hospitals adjust staffing levels from day to day, so this number may decrease for a variety of reasons related to staffing decisions and hospital demand, it may not always mean hospitals are "running out" of beds. This also means the total number of "reported beds" (full + empty) isn't a reliable metric for calculating an adjusted covid census to take into account the variable hospital reporting rate.

total_inpt_unreportedunstaffed
Total number of acute beds that are either unstaffed in hospitals that reported that day, or contained in hospitals that did not report that day (so staffing is unknown).

total_icu_full
Total number of ICU beds in use by patients (for any indication) as reported by hospitals on this day.

total_icu_empty
Total number of ICU beds that are staffed and available as reported by hospitals on this day.

total_icu_unreportedunstaffed
Total number of ICU beds that are either unstaffed in hospitals that reported that day, or contained in hospitals that did not report that day (so staffing is unknown).

total_pts_on_vent
Total number of ventilators that are in use by patients (for any reason) as reported by hospitals that day

total_empty_vents
Total number of ventilators not currently in use, as reported by hospitals that day

total_vents_in_hosp
Total number of ventilators in hospitals (both in use and not currently in use) as reported by hospitals that responded that day.

UPDATE July 22nd, 2020

The DHHS hospitalization dashboard updated over the weekend.

The licensed total of beds (empty, full, and unreported/unstaffed) changed with the update. Acute licensed total was 21,222 and is now 25,309. ICU licensed total was 3,223 and is now 3,462.

UPDATE August 3rd, 2020

The past dashboard data changes daily due to, I'm assuming, additional processing steps at NCDHHS. I'll update the whole time series every day to reflect these changes. The fields affected are: total_covid_census, total_icu_covid, total_confirmed_admitted_24hours, and total_suspected_admitted_24hours.
