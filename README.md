# School_District_Analysis
### Analsysis of student grades

## Post Cheating Scandal Analysis
Due to the manipulation of grades by Thomas High school many of the metrics from last year need to be reviewed. Wide scale cheating or grade manipulation took place in the Thomas Hig School 9th grade class. All of the scrers for reaidng and math had to be removed. As such Thomas Overall ranking has been greatly affected.

## Changes due to grading adjustments after the scandal
### Results of removing Thomas High 9th grade scores and precentages

* Thomas school ranking
  * Thomas previously ranked as 2 place in overall percaentage of students passing Math and Reading. After the 9th grades artificially pumped grades Thomas fell 6 spots to 8th place. 	
* Top five standing
  * Thomas High dropped out of the top 5 in percentage of students passing math to last place. While Thomas high passing reading percentage actually icreased with removing the 9th grade data.
* Math and reading scores by grade
  * Math and Reading scores were replaced by NaN and therefore were not counted for or against the school
* Scores by school spending
* Passing percentage of the school in the $630-644 dropped greatly.
    * Passing math percent dropped 7%
    * Passing reading percent dropped by 20%
* Scores by school size
  * Passing percentage of the schools in the medium size range dropped greatly.
    * Passing math percent dropped 7%
    * Passing reading percent dropped by 10%
* Scores by school type
	    * Schools were not impacted when looking at the type of school.
* School district summary
 * Wasn’t effected much at all. Nothing note worthy
* School summary
  * No school other than Thomas High school was affected. Thomas High school grades are drastically lower.

      
## Overall Analysis 
Overall analysis of the data revealed some possibly surpsing information. The success (ie the grades and passing percentage) of the students were not not directly linked or effected by funds spent on the students. School size had a much greater impact on the student and their education. On average the small and medium schools preformed relatively close to each other with a high overall passing rate. Large schools on the other hand faired poorly overall. Teacher to student ratio may come into play as well as demographics and class environment. Unfortuantely that additional data was not available for this analysis. Charter schools also faired greatly better than the Public schools. This may be due to the lack of standardized testing or quality of teachers. Testing data and teacher demographics/education were made available for this assessment.

## Data Deliverables
Summary of all elements can be found by running the attached Jupyter Notebook. Selct Run All and scroll to the bottom of the code. All relevane data will be listed and available to the user.

### The follwing are the names of each item-

* type_summary_df - Summary of scores and passing rate based on type of school
* size_summary_df - Summary of scores and passing rate based on size of school
* spending_summary_df - Summary of scores and passing rate based on spending per student
* per_school_summary_df - Summary of scores and passing by school
* distirict_summary_df - Summary of scores and passing by district
* school_summary_df - Overall information of each school 
* top_5 - Top 5 perfroming schools
* bottom_5 _ Bottom 5 performing schools
* math_scores_df - Math scroes by school
* reading_scores_df - Reading scores by school


