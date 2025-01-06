# -Data-Analysis-Project-in-Excel

1.Data Cleaning

  Remove duplicate values
  
  Table shows Male as M and Female as F, use "Find AND Replace"  to convert them into Female and male
  Find Age using Birth year,month,day (used "=Date" function and current date "=Today()" function and take the difference using "=yearfrac" function)

  Next look at number format,in gdp_country shows it given in text insted of number format to check that we add 1st cell and second cell we got "#value" error insted of sum so we come to conclution it because of ","and "$" signs.So we remove them using "Find AND Replace" (ctrl+h).then formate values with a comma seperator and without decimals.

  2.Data analysis 
  
  (#discriptive statistic is remain )
  
  data analysis using pivot table 

  Top 10 richest people :
  choose personName and the final worth as fields and use value filter to filter top 10
  
 
  ![Screenshot 2025-01-06 213445](https://github.com/user-attachments/assets/a5bb36a8-72d4-4aa7-abb8-7748bb42d5d1)


   counting bilioners by age:

  copy and paste the previous table and drag raws and columns and add age to rows the value become sume of age filter it as age for more sense.
  


  ![Screenshot 2025-01-06 214210](https://github.com/user-attachments/assets/7f77bb42-d2cd-412f-86cd-f733fe9477bd)

 Then group age with 10 value gap from 30 to 100 by right click and choosing group option.
 
 
  ![Screenshot 2025-01-06 214721](https://github.com/user-attachments/assets/9e5e5882-9656-496e-bf38-dd0fae70deed)
![Screenshot 2025-01-06 214524](https://github.com/user-attachments/assets/7f21f324-fe06-40af-94e5-7253921cd9c6)


3. Data Visualization

Insert slicers for catergory,selfMade,Gender and make connections to the pivote tables using "Report connections".![Screenshot 2025-01-06 223316](https://github.com/user-attachments/assets/65ba7e0e-85fd-4b96-998e-c27e08b51554)

 Make cluster  column by using recomanded charts in "insert" for two pivot tables to depict "TOP 10 RICH LIST" AND "BILLIONERS BY AGE![Screenshot 2025-01-06 225005](https://github.com/user-attachments/assets/d85c8d75-5280-4a9c-85b2-fd77de463dc1)
"

