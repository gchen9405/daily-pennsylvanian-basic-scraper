In the GitHub Actions workflow file, the cron expression under schedule is used to trigger the workflow at a scheduled time—in this case, 8 PM specifically. "0 20 ***" means that 
the workflow will run at the 0th minute of the 20th hour (8 PM) every single day. This cron schedule will automatically trigger the workflow without any manual push request being made.
This will allow my scraper to collect the text from the DP's front page everyday without requiring me to monitor or intervene. 
I will modify this expression to run twice a day instead of just once. 
