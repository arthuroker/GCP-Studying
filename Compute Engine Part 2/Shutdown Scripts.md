
Scripts the execute automatically when a VM instance is stopped

Useful for ensuring that applications can clean up, save data, or gracefully close processes

Useful with preemptible instances, which can be reclaimed by GCP at any time

*Script time limit*

90 seconds for on-demand by user

30 seconds for preemptions


*Creating and using scripts*

1. Write script in any exe file type