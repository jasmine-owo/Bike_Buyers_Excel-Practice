This is an Excel Practice credited to 'Alex The Analyst' Excel Tutorials.

Provided with the bike buyers dataset, I created a Dashboard to gain insights from the pattern of bike buyers. These are the steps in our Excel Project:

### Data Cleaning
1. Remove all duplicates
- We used data tool to remove duplicates.
- Outcome: 26 duplicate rows removed
- 1001 unique rows remain

2. Find and Replace
In the Marital Single Column:
- Replace ‘M’ to ‘Married’
- Replace ’S’ to ‘Single’

In the Gender Column:
- Replace ‘F’ to ‘Female’
- Replace ‘M’ to ‘Male’

3. Fix the format of Income to currency

4. Add a column to group the age interval
=if(L2>54,"Old", if(L2>=31,"Middle Age”,if(L2<31,"Adolescent","Invalid")))

### Pivot Table
We created three pivot tables for data exploration: Average Income Per Perchase, Customer Commute and Customer Age Brackets. Three plots are shown below:

<img width="573" alt="Screenshot 2022-10-27 at 17 04 08" src="https://user-images.githubusercontent.com/108580837/198341472-e759ad87-5503-4a99-a06d-ab11902d16c4.png">
It is observed that with a greater income, it is more favorable for the customers to perchase a bike. With our collected data, average income of male is higher than female.


<img width="575" alt="Screenshot 2022-10-27 at 17 04 14" src="https://user-images.githubusercontent.com/108580837/198342339-6628426f-c18f-4e07-afdc-8c9f6b32eb2a.png">
It is surprised that customers with a shorter commute distance are more likely to perchase a bike. The reason behind might be for a larger commute distance, people tends to travel by other transportation for convenience.

<img width="574" alt="Screenshot 2022-10-27 at 17 04 21" src="https://user-images.githubusercontent.com/108580837/198343032-d8a3a982-73c2-4b51-8824-24168e43787c.png">
As we have divided the age of the customers into three groups, it is found that there are more purchase in the middle age group (31-54 years old).

### Dashboard
All the graphs are displayed nicely in the Dashboard with three slicers: Marital Status, Region and Education.
