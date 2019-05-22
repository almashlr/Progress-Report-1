# Progress-Report-1
Week 3 deliverable for final project
Deliverable. Due Prior to Week 3 Live Seminar.
Goal: Identify and initially investigate a Good Dataset. Propose a “Data Science” Problem to solve using this data and subsequent analytics. (Find a data set that interests you!): How do the last words of someone set to die reflect their values and beliefs or lived experiences?
o Finding data sets: https://www.kaggle.com/mykhe1097/last-words-of-death-row-inmates

 Scope. 1 – 2 pages.
Sections
o Introduction: This dataset includes information on criminals executed by Texas Department of Criminal Justice from 1982 to November 8th, 2017. In Furman v Georgia in 1972, the Supreme Court considered a group of consolidated cases, whereby it severely restricted the death penalty. However, like other states, Texas adjusted its legislation to address the Court's concern and once again allow for capital punishment in 1973. Texas adopted execution by lethal injection in 1977 and in 1982, the starting year of this dataset, the first offender was executed by this method.


 Introduce problem. When faced with imminent death, and allowed one final opportunity to speak, people's words may refelct values or beliefs from lived experiences, a sense of justice or sense making, reparations, or other areas of life. This data may help in understanding what values are reflected in people's final words. Since many people may not know their final hour, this data may prove valuable in determining what are the most important thoughts or feelings when one knows he or she will die. Are there any simiilarities in death row inmates final thoughts? What is the relationship or correlation to the final thoughts and race, ethnicity, crimes, or victims?
 Motivate your approach. o Data
 How is data acquired? This dataset is derived from the database by Texas Department of Criminal Justice which can be found in this link: http://www.tdcj.state.tx.us/death_row/dr_executed_offenders.html .
 Format of Data
 Describe data / variables:
The dataset consists of 545 observations with 21 variables. They are: 
- Execution: The order of execution, numeric. 
- LastName: Last name of the offender, character. 
- FirstName: First name of the offender, character. 
- TDCJNumber: TDCJ Number of the offender, numeric. 
- Age: Age of the offender, numeric. 
- Race: Race of the offender, categorical : Black, Hispanic, White, Other. 
- CountyOfConviction: County of conviction, character. 
- AgeWhenReceived: Age of offender when received, numeric. 
- EducationLevel: Education level of offender, numeric. 
- Native County: Native county of offender, categorical : 0 = Within Texas, 1= Outside Texas. 
- PreviousCrime : Whether the offender committed any crime before, categorical: 0= No, 1= Yes. 
- Codefendants: Number of co-defendants, numeric. 
- NumberVictim: Number of victims, numeric. 
- WhiteVictim, HispanicVictim, BlackVictim, VictimOtherRace. FemaleVictim, MaleVictim: Number of victims with specified demographic features, numeric. 
- LastStatement: Last statement of offender, character.
 If possible at this point, load data and create some supporting displays /
visualizations. (This may not be possible yet if you plan to “scrape” your data.)
