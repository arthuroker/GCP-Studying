
*Watermarks*

Timestamps that keep track of progress in your pipeline

If a step fails or stalls, then the watermark fails to advance

Late-arriving data - determine which window data belongs to, and ensure calculations are accurate

*Event time and processing time* - the system processes data based on when the event occurred (event time) and tracks progress with watermarks, even if the data arrives later (processing time) 

*Triggers*

Conditions that decide when the aggregated results of data should be emitted

Especially important in unbounded/streaming data pipelines

