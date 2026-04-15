
Potentially millions of predictions requests to the endpoint every day

*Sampling rate* - the proportion of prediction requests that are logged and analyzed for model monitoring

*Considerations for lowering the sampling rate*

*Saves cost* - requires less compute and storage

*Monitoring less accurate* - especially with smaller and lower volume endpoints

*Frequency*

Determines when the monitoring analysis runs

Specified in cron notation

Asterisk in place means "every" for that time interval

(Minute)(Hour)(Day of Month)(Month)(Day of Week)

*Sampling rate + frequency*

How quickly you'll detect drift/skew

How reliably you'll detect it

Your monitoring costs

Finance examples - high for both

High volumne recommendation 