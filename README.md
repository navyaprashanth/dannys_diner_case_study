# dannys_diner_case_study
This case study was taken from [8 weeks sql challenge](https://8weeksqlchallenge.com/case-study-1/)
<img width="1080" height="1080" alt="dannys_diner" src="https://github.com/user-attachments/assets/d87b84ce-40ad-4fc5-bc03-0801c34170f6" />

**Introduction**

Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen.

Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant has captured some very basic data from their few months of operation but have no idea how to use their data to help them run the business.

**Problem Statement**

Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.

Danny has provided you with a sample of his overall customer data due to privacy issues - but he hopes that these examples are enough for you to write fully functioning SQL queries to help him answer his questions!

Danny has shared with you 3 key datasets for this case study:
1. [sales](https://github.com/user-attachments/files/22178895/dannys_diner_sales.csv)
2. [menu](https://github.com/user-attachments/files/22178920/dannys_diner_menu.csv)
3. [members](https://github.com/user-attachments/files/22178940/dannys_diner_members.csv)

**Case Study Questions**
1. What is the total amount each customer spent at the restaurant?

Syntax:
<img width="784" height="415" alt="Screenshot 2025-09-06 004240" src="https://github.com/user-attachments/assets/eb52411f-0cd5-4a72-865d-d451fab51f23" />

Answer:
A- 76, B- 74, C- 36
  
2. How many days has each customer visited the restaurant?

Syntax: 
<img width="844" height="232" alt="Screenshot 2025-09-06 004904" src="https://github.com/user-attachments/assets/726372bc-4d0c-4ef4-9a24-ad55a770e29b" />

Answer: A-4, 
        B-6, 
        C- 2

3. What was the first item from the menu purchased by each customer?

   Syntax:
   <img width="745" height="527" alt="Screenshot 2025-09-06 131900" src="https://github.com/user-attachments/assets/52bf9ab7-2652-4423-8dfc-ce0b035460ee" />

Answer: A bought Sushi and Curry on his/her first purchase,
        B bought Curry on his/her first purchase,
        C bought Ramen on his/her first purchase.

4. What is the most purchased item on the menu and how many times was it purchased by all customers?
   
   Syntax:
   <img width="686" height="419" alt="Screenshot 2025-09-06 132412" src="https://github.com/user-attachments/assets/14ddb4a0-855d-41d5-8d8f-99e4c582d3af" />

Answer: Ramen- 8

5. Which item was the most popular for each customer?

   Syntax: 
   <img width="740" height="570" alt="Screenshot 2025-09-06 132842" src="https://github.com/user-attachments/assets/224e37ac-2711-4bfc-9dff-7c84c737d2ed" />

Answer:A bought Ramen 3 times,
       B bought Curry, Ramen and Sushi each 2 times,
       C bought Ramen 3 times
  
6. Which item was purchased first by the customer after they became a member?
   
  Syntax:
<img width="467" height="485" alt="Screenshot 2025-09-06 141832" src="https://github.com/user-attachments/assets/661a2688-9933-48b7-9073-d3fe46950272" />

Answer: A- Curry, 
        B- Ramen

7. Which item was purchased just before the customer became a member?

Syntax: <img width="556" height="538" alt="Screenshot 2025-09-06 142412" src="https://github.com/user-attachments/assets/e972c6a4-66dd-4aea-b074-e52e38087d91" />

Answer: A- Ramen,
        B- Sushi
        
8. What is the total items and amount spent for each member before they became a member?

   Syntax:<img width="393" height="282" alt="Screenshot 2025-09-06 142920" src="https://github.com/user-attachments/assets/848c9c3d-ddb8-4700-850b-92d367221824" />

Answer: B- $62,
        A- $61
   
9. If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
    
    Syntax: <img width="363" height="343" alt="Screenshot 2025-09-06 143143" src="https://github.com/user-attachments/assets/750564e7-38c0-47cf-804e-ff1590a95692" />

Answer: A- 860 points,
        B- 940 points,
        C- 360 points
    
