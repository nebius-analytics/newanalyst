# Test Assignment for Analyst in Nebius

Dear candidate, 
We are pleased to recieve your application!

We offer you to complete our test assignment. You are allowed to use all the tools available, including AI. We encourage you to try our Nebius AI Studio, HR will share a $10 promocode with you. 


## 1. "How our sales are going?"
Analyze sales pipeline of some fictional organization. Imagine CEO came to you and asked "How our sales are going?".

 * Provide a laconic report on the current situation. 
 * Design a Sales Pipeline Dashboard that will be used by CEO on regular basis. What metrics you suggest to include there? If you develop an actual dashboard / data app it will be a great plus. You can use any tool / framework you prefer.
 * What additional data you would like to collect and why?

Data is stored in postgres database. How to connect to it:
1. Download certificate
```
mkdir -p ~/.postgresql
curl "https://storage.eu-north1.nebius.cloud/msp-certs/ca.pem" \
  -o ~/.postgresql/root.crt
chmod 0600 ~/.postgresql/root.crt
```
2. Check the connection. Password will be provided by HR.
```
psql "host=public-rw.postgresql-e00d4dv1bw48m5zd8p.backbone-e00g4teqcpmz03de0b.msp.eu-north1.nebius.cloud \
  port=5432 \
  sslmode=verify-full \
  dbname=sales \
  user=sales-analyst"
```
If you have problems with connecting to DB please contact our HR.

## 2. "How can we increase conversion from tenant to customer?"
Now imagine yourself as analyst in Nebius. CEO comes and asks "How can we increase conversion from registration to entering card details?". Propose an action plan how you are going to deal with this task. What hypotheses do you have? What metrics would you like to measure?
