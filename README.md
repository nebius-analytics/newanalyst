# Test Assignment for Analyst in Nebius

Dear Candidate,

Thank you for your application!

We’re pleased to invite you to complete our test assignment. You are welcome to use any tools available, including AI. We also encourage you to try out our Nebius AI Studio — our HR team will share a $10 promo code with you. Deadline is 72 hours from the moment you recieve the task. Please send the result to email provided by our HR team.


## 1. “How are our sales going?”

Analyze the sales pipeline of a fictional organization. Imagine the CEO comes to you and asks “How are our sales going?”.
 * Provide a concise report on the current situation.

 * Design a Sales Pipeline Dashboard for regular use by the CEO. What key metrics would you include? If you choose to develop an actual dashboard or data app, that would be a strong bonus. You may use any tool or framework you prefer.

 * What additional data would you like to collect, and why?

Data is stored in postgres database. How to connect to it:
1. Download certificate
```
mkdir -p ~/.postgresql
curl "https://storage.eu-north1.nebius.cloud/msp-certs/ca.pem" \
  -o ~/.postgresql/root.crt
chmod 0600 ~/.postgresql/root.crt
```
2. Check the connection. Password will be provided by our HR team.
```
psql "host=public-rw.postgresql-e00d4dv1bw48m5zd8p.backbone-e00g4teqcpmz03de0b.msp.eu-north1.nebius.cloud \
  port=5432 \
  sslmode=verify-full \
  dbname=sales \
  user=sales-analyst"
```
If you have problems with connecting to DB please contact our HR team.

## 2. Conversion to first GPU conumption
Now, imagine yourself as an analyst at Nebius. The CPO approaches you and asks: “How can we increase conversion from registration to first GPU consumption for Individual users?”

Propose an action plan for how you would approach this task. Consider the following:

 * What hypotheses do you have? 

 * What metrics would you track and measure to check these hypotheses?

