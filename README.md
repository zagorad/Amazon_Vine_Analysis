# Amazon_Vine_Analysis

## Analysis Overview
The purpose of this project was to analyze Amazon five star reviews from paid vine members vs the non-vine members to determine any bias. Additionally, to perform the analysis we used PySpark to perform the ETL process and connect to AWS RDS instance to load the transformed data into pgAdmin.

## Results

**Total number of reviews:**

  •	Paid Vine Members: 170

  •	Non-Vine Members:37,840

![Total numbers of paid reviews](https://user-images.githubusercontent.com/118132063/226527730-89d47f29-d78e-45da-9bb2-749f740abb24.png)


![Total numbers of unpaid reviews](https://user-images.githubusercontent.com/118132063/226528320-8446eea2-f7bf-43a8-9ef6-e9ce6a8acb32.png)


**Total number of five-star reviews:**

  •	Paid Vine Members: 65

  •	Non-Vine Members:20,612

![Paid five star reviews](https://user-images.githubusercontent.com/118132063/226529350-43f65468-7f01-4171-a708-edca3b26fc75.png)

![image](https://user-images.githubusercontent.com/118132063/226529320-2e45b071-0da8-4673-a448-393ecb33d102.png)

**Total percent of five-star reviews:**

•	Paid Vine Members: 38.23%

•	Non-Vine Members: 54.47%

![Paid five start review percentage](https://user-images.githubusercontent.com/118132063/226530006-88ca3b11-6efa-45cd-9a8f-d0123288d1d8.png)

![Unpaid five star review percentage](https://user-images.githubusercontent.com/118132063/226530058-f2bda11e-bf8a-47ba-9331-62cac2f3c1ed.png)

## Summary 
From the analysis it doesn’t seem as there is a positive bias from the paid vine members with 38.23% of the reviews being five star versus the 54.47% from the non-vine members. Additional analysis that could be performed is to compare vine-members reviews vs the non-vine members. 

