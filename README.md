# SchoolDistrictAnalysis
Overview of the school district analysis: As per a school district query, the objective of this analysis is to disaggregate the math performance and reading scores of the entire district schools in a presentable way for a broad meeting. However, the board review panel suspected possible cheating at Thomas High School’s 9th grade and asked for reanalysis by excluding that specific result. 

# Results:

## How is the district summary affected?
Original Analysis:![image](https://user-images.githubusercontent.com/100442163/161381965-dee665d9-179c-45bc-a720-1ed479942cca.png)

Adjusted Analysis:![image](https://user-images.githubusercontent.com/100442163/161381990-e9b87a83-460e-4dd5-a975-eea9cbb01fb9.png)
When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set. The change was less than a 1% difference and the numbers would still round to the same whole number.

## How is the school summary affected?
Thomas High School started with a 91% overall passing rate in the original analysis. It was a concern to the school board as being too high. After calculating the total number of 10th – 12th-grade students as the new denominator, the rest of the testing data was adjusted accordingly.
Original Analysis:  
![image](https://user-images.githubusercontent.com/100442163/161382023-b314ba52-5cd7-4492-8da0-159b329b9aa1.png)
Adjusted Analysis: 
![image](https://user-images.githubusercontent.com/100442163/161382027-7fd2f670-742c-4abf-9842-7e1237780627.png)
Removing the 9th-grade students from the data set had a huge impact by dropping from 91% to 65% the overall passing rate.

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board review panel.
Original Analysis:  
![image](https://user-images.githubusercontent.com/100442163/161382055-a865be5a-66fb-436d-86c4-6a1925b0c08b.png)
After adjusting the 9th-grade data, Thomas High School ranked in the exact middle of 15 campuses at 8th from the bottom.
Adjusted Analysis: 
![image](https://user-images.githubusercontent.com/100442163/161382065-90f8277d-cc5d-40f3-970b-f89a3734cf9c.png)

## How does replacing the ninth-grade scores affect the following:
Adjusted Averages using the Math and Reading Scores
In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th-grade tests. Now the scores have been replaced with null values and show up in Python programming as NaN in the following charts.
Adjusted Average Math Scores: 
![image](https://user-images.githubusercontent.com/100442163/161382122-2f0ee3c0-8d8e-40b3-abf0-5f6b70e5cc18.png)
Adjusted Average Reading Scores:
![image](https://user-images.githubusercontent.com/100442163/161382133-63a41810-db0c-4998-8027-c14599c8d78a.png)

## Scores by school spending
Thomas High School falls in the $630-$644/student spending range. However, the hundredths place was needed to see the nominal changes.
Original Analysis:
![image](https://user-images.githubusercontent.com/100442163/161382149-86e156e1-62ea-4ba6-9cd1-1417bf6fa5ff.png)
Adjusted Analysis:  
![image](https://user-images.githubusercontent.com/100442163/161382159-7460d54c-46f6-4020-afee-5fc247cb3576.png)
There was very little spending impact by changing the 9th grade scores.

## Scores by school size
Thomas High School is defined as a medium sized school. The hundredths place was needed to see the nominal changes.
Original Analysis:![image](https://user-images.githubusercontent.com/100442163/161382176-d2259494-590c-4f2a-b696-537381447a3c.png)
Adjusted Analysis:![image](https://user-images.githubusercontent.com/100442163/161382186-17ec307b-8854-4cfb-90ab-1c31a37c9493.png)
There was very little impact by campus size due to changing the 9th grade scores.

## Scores by school type
Thomas High School is a charter school type. The hundredths place was needed to see the nominal changes.
Original Analysis:  ![image](https://user-images.githubusercontent.com/100442163/161382199-14e2648c-39f7-4539-b440-87affe837288.png)
Adjusted Analysis:  ![image](https://user-images.githubusercontent.com/100442163/161382209-651969c4-24ed-44e7-acc9-0e56bc0418a1.png)
There was very little impact by school type by changing the 9th-grade scores.

# Summary: 
The suggested adjustments recommended by the board review panel impact the overall results following ways:
1.	The overall passing rate for Thomas High School dropped dramatically from 91% to 65%.
2.	Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.
3.	The exclusion of Thomas High School’s 9th-grade math and reading results from the entire district board results did negligible effects. 

