
*What is message batching*

Used to optimize throughput by grouping multiple messages together before publishing

May introduce latency as messages wait to be batched

Not good for when messages need to be delivered immediately

To programmatically disable batching, set the value of max messages to 1

