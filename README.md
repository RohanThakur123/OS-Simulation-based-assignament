# OS-Simulation-based-assignament
Other name of this algorithm is Shortest-Process-Next (SPN).
Shortest-Job-First (SJF) is a non-preemptive discipline in which waiting job (or process) with the smallest estimated run-time-to-completion is run next. In other words, when CPU is available, it is assigned to the process that has smallest next CPU burst.
The SJF scheduling is especially appropriate for batch jobs for which the run times are known in advance. Since the SJF scheduling algorithm gives the minimum average time for  a given set of processes, it is probably optimal.
The SJF algorithm favors short jobs (or processors) at the expense of longer ones.
The obvious problem with SJF scheme is that it requires precise knowledge of how long a job or process will run, and this information is not usually available.
The best SJF algorithm can do is to rely on user estimates of run times.
In the production environment where the same jobs run regularly, it may be possible to provide reasonable estimate of run time, based on the past performance of the process. But in the development environment users rarely know how their program will execute.
Like FCFS, SJF is non preemptive therefore, it is not useful in timesharing environment in which reasonable response time must be guaranteed.
