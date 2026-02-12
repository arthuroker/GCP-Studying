
Scripts the execute automatically when a VM instance is stopped

Useful for ensuring that applications can clean up, save data, or gracefully close processes

Useful with preemptible instances, which can be reclaimed by GCP at any time

*Script time limit*

90 seconds for on-demand by user

30 seconds for preemptions


*Creating and using scripts*

1. Write script in any exe file type (bash, python)
2. Add script to instance metadata
3. VM is stopped, either by you or Google
4. Clean-up through shutdown script automatically triggered


