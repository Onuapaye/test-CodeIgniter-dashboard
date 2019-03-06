# test-CodeIgniter-dashboard
This project is meant to test CodeIgniter dashboards and to realise a proof of concept

Subset of real user stories

- As the webite super admin, I want to be able to classify information present in the goal-payment table based on the users goal creation date and
the goal end date so that i can sum the amount raised by customers in the set duration and know exactly what to refund to the user

Here, 3 main database tables are involved
1. users table
2. payment_goal table
4. goal_plan table

Based on the goal creation date, it's status(0= inactive & 1= active) and it's end date, we should be able to obtain the user
registered to a goal(using user_id) in the goal_plan table and then query the goal_payment table for transactions made during this period(goal creation & goal end date).

Format of data to be presented

customer name, goal plan title, goal creation date, goal end date, sum of amount during the goal period, goal target set by user



NB:

The db file is attached with sample information... Feel free to play with it as much as you want

