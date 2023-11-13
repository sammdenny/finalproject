# What is the impact of poverty on education in the City of Bradford

## Research question
What is the impact of poverty on education in the City of Bradford, specifically, how does socioeconomic deprivation affect school engagement, and school performance in Bradford. 

## Background
Access to, and engagement with, high quality education is a significant predictor of long-term life outcomes. Young people who disengage from education have an increased risk of future criminal activity, unemployment, substance misuse and poor health (Klasson, Stewart & Lapshina, 2021) <a href="#ref1">[1]</a>. 

School disengagment can refer to a range of different things, including school refusal, poor attendance, school exclusion or becoming NEET (Not in Education, Employment or Training) at 16. I have chosen to look at absence rates for pupils as a measure of school engagement, as poor attendance can be an 'early warning signal' of more serious disengagement and wider negative reprocussions (Kearney et al., 2023) <a href="#ref3">[3]</a>. 

Socioeconomic status has been shown to impact educational outcomes. As part of the Longitudinal Study of Young People in England (LSYPE) the progress of over 15,000 individuals was measured from birth through to their early 20s. This research showed that an attainment gap between children from the poorest backgrounds and their better off peers was already evident at the age of 5, and widened substantially by the time they were in secondary school (Goodman et al., 2010) <a href="#ref2">[2]</a>. Seventy-five percent of young people in the least deprived quintile gained 5 good GCSEs, compared to only 21% of the poorest quintile. 

For this assignment, I will compare school absences for pupils who are eligible for free school meals (FSM) with pupils who are not eligible. In England, children are eligible for FSM if their parent or carer is receiving social benefits <a href="#ref4">[4]</a>. FSM eligibility is frequently used as an indicator of socioeconomic disadvantage for school-aged children (for example, Allen and Vignoles, 2007) <a href="#ref5">[6]</a>. 

I have chosen to look at Bradford as it is an area with increasing challenges around school attendance. In the 2021/22 academic year 28.6% of Bradford students were persistently absent (missing 10 sessions or more), compared to 22.5% Nationally. Further to this, Bradford's absence rate has more than doubled since 2018/19 (14.1%; Newman, 2023) <a href="#ref4">[5]</a>. 

### Hypothesis 1: Bradford students who are eligible for FSM will have higher rates of 'overall absence', 'unauthorised absence', 'persistent absence' (10 sessions or more) and 'severe absence' (50 sessions or more) during the 2021/22 academic year, than students who are not eligible for FSM. 

I will also consider absence rates at the school level as one aspect of school performance, and see how these relate to overall school performance. I will use Ofsted rating as a measure of overall school performance. The Office for Standards in Education, Children's Services and Skills (Ofsted) is primarily responsible for assessing the quality of education and care provided by schools across the UK. There is a 4-point scale for Ofsted ratings - grade 1: outstanding, grade 2: good, grade 3: requires improvement and grade 4: inadequate. The rating that a school recieves from Ofsted can have a big impact on whether parents choose to enroll their children, on staff morale, and even on the funding that the school receives. 

Finally I will explore the relationship between school performance and the level of deprivation in the local area. For this I will use Indices of Multiple Deprivation (IMD), which give an indication of the level of deprivation in small areas relative to the rest of the UK. I will then use a spatial visualisation to show this relationship. 

### Hypothesis 2: Bradford schools with higher absence rates, and lower Ofsted ratings will be located in and around the most deprived (lower super output) areas of Bradford City. 


## Open Data Sources
Absence data by pupil characteristic and Bradford schools data, including Ofsted ratings and postcode, have been retrieved from the Northern Data Hub <a href="#ref6">[7]</a>. 

Absence data by school have been retrieved from the UK Government's 'Explore Education Statistics' website <a href="#ref7">[8]</a>.

Spatial data for the Bradford Lower Super Output Areas (LSOAs), and for the Bradford school postcodes have been retrieved from the Office for National Statistics (ONS) Open Geography Portal <a href="#ref7">[8]</a>. 

#### Notes on retrieving spatial data
I initially downloaded the Bradford LSOA spatial data based on filtering by the Bradford OSLAUA (E08000032) however, when I merged it with the Bradford schools data there were 30 school postcodes missing from the ONS dataset. Instead, the shape file for the Bradford LSOAs that I have used was obtained using the map zoom function on the ONS website to retrieve a larger dataset. When merging this new file with the Bradford schools data there was a match for 100% of school postcodes. 


## References

<p><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8685215/#:~:text=School%20problems%20during%20childhood%20and,and%20school%20dropout%20(17)">[1]</a> Klassen, J. A., Stewart, S. L., and Lapshina, N. 2021. School Disengagement and Mental Health Service Intensity Need Among Clinically Referred Students Utilizing the interRAI Child and Youth Mental Health Assessment Instrument. <i>Frontiers in psychiatry</i>, 12.</p>

<p><a href="https://www.jrf.org.uk/sites/default/files/jrf/migrated/files/poorer-children-education-full.pdf">[2]</a> Chowdry, H., Crawford, C., Dearden, L., Joyce, R., Sibieta, L., Sylva, K. and Washbrook, E., 2010. Poorer children’s educational attainment: how important are attitudes and behaviour. <i>Joseph Rowntree Foundation</i>, pp.1-72.</p>

<p><a href="https://www.frontiersin.org/articles/10.3389/feduc.2023.1253595/full">[3]</a> Kearney, C.A., Dupont, R., Fensken, M. and Gonzalvez, C. 2023. School attendance problems and absenteeism as early warning signals: review and implications for health-based protocols and school-based practices. <i>Frontiers in Education</i>. 8. </p>

<p><a href="https://explore-education-statistics.service.gov.uk/find-statistics/school-pupils-and-their-characteristics">[4]</a> UK Government. 2023. Schools, pupils and their characteristics: Academic year 2022/23. [Online]. [Accessed 12 October 2023]. Available from: https://explore-education-statistics.service.gov.uk/find-statistics/school-pupils-and-their-characteristics </p>

<p><a href="https://www.thetelegraphandargus.co.uk/news/23404540.almost-30-per-cent-pupils-persistently-absent-bradford-schools/">[5]</a> Newman, R. 2023. Almost 30 per cent of pupils persistently absent at Bradford schools. [Online]. [Accessed 13 October 2023]. Available from: https://www.thetelegraphandargus.co.uk/news/23404540.almost-30-per-cent-pupils-persistently-absent-bradford-schools/</p>

<p><a href="https://www.tandfonline.com/doi/full/10.1080/03054980701366306?casa_token=6SEt_25VLtoAAAAA%3AjaCLjzy7UOchJYXlhUjfp42k6jGEehIczK9S5WqHSggLZwua1yxenu6pwSVM69D9Oua0R7W6NUku">[5]</a> Allen, R. and Vignoles, A. 2007. What should an index of school segregation measure?. <i>Oxford Review of Education</i>. 33(5), pp.643-668</p>

<p><a href="https://datahub.bradford.gov.uk/ebase/datahubext.eb?search=Bradford+Council+census+results+2021&ebd=0&ebp=10&ebz=2_1697028992340">[6]</a> Northern Data Hub</p>

<p><a href="https://explore-education-statistics.service.gov.uk/find-statistics/pupil-absence-in-schools-in-england/2021-22">[7]</a> UK Government. 2023. Pupil absence in schools in England: Academic year 2021/22. [Online]. [Accessed 13 October 2023]. Available from: https://explore-education-statistics.service.gov.uk/find-statistics/pupil-absence-in-schools-in-england/2021-22 </p>

<p><a href="https://geoportal.statistics.gov.uk">[8]</a> Office for National Statistics (ONS) Open Geography Portal</p>
