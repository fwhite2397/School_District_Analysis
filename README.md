# School_District_Analysis
Module 4 school district analysis

# Overview
After submitting test score results to schoolboard, they discovered that one school had fradulent data that they would like removed to cleanse the data.
The school in question was Thomas High School, in which the school board requested that the math and reading scores be removed for all 9th grade students, for that High School.
This will provide the school board a accurate representation of how the school performed in comparison with the others.

# Results
In order to remove the 9th grade group from the data, we replaced their scores with Nan, using the numpty class object nan method.
This was done in conjuction with the data frame's loc function that allowed us to look up the specific data we wanted to updated. 
Once the data was updated, it did produce slighlty different results that the original data set.

Since we are no longer using the data from Thomas High's 9th grade class, our total student population was reduced by 461 students. This impacted the overall total averages, counts as well as the number specific for that school. 

Here are the original number across the district:
<img width="854" alt="image" src="https://user-images.githubusercontent.com/95976771/149720853-6065c56f-cbf0-4334-bbc9-ee1e24a8ed77.png">


Here are the new numbers across district, after the students were removed. Not a lot of difference is reflected:
<img width="847" alt="image" src="https://user-images.githubusercontent.com/95976771/149720942-355c8a5e-912e-4e2b-916b-6318592833b3.png">


Here are the overall number for Thomas High School, prior to the correction:
<img width="841" alt="image" src="https://user-images.githubusercontent.com/95976771/149721276-11557334-6b20-490d-9f6a-7dd3a040c443.png">


And after the correction:
![image](https://user-images.githubusercontent.com/95976771/149721367-bd2be83d-065b-4cd2-9558-26f9ee8c420c.png)


Overall, the numbers changes slightly but Thomas High still remained in the top 5 amongst all the schools.
