# pandas-challenge
Pandas-Challenge
#### Code Source: PyCitySchoolstarter
###### All formating: district_summary["Total Students"] = district_summary["Total Students"].map("{:,}".format)
###### district_summary["Total Budget"] = district_summary["Total Budget"].map("${:,.2f}".format)
###### Code to calculate the passing rate: per_school_passing_math = school_students_passing_math / per_school_counts * 100
###### per_school_passing_reading = school_students_passing_reading / per_school_counts * 100
###### overall_passing_rate = school_students_passing_math_and_reading / per_school_counts * 100
###### Code to calculate the data by separate grade: ninth_graders = school_data_complete[(school_data_complete["grade"] == "9th")]
###### tenth_graders = school_data_complete[(school_data_complete["grade"] == "10th")]
###### eleventh_graders = school_data_complete[(school_data_complete["grade"] == "11th")]
###### twelfth_graders = school_data_complete[(school_data_complete["grade"] == "12th")]
###### And establishment of bins in the school size DataFrame
###### To clean the data: math_scores_by_grade.index.name = None

#### Code Source: Xpert Learning Assistant
###### Use of the .reset_index to put the data in each library to transform into the different DataFrames
###### Use of the float() function on calculate the averages
###### Modification in declaring the keys on the dictionaries, with the reset index
###### The use of this code to transform the datatype so the school_summary DataFrame didn't run into issues when using the pd.cut() function
