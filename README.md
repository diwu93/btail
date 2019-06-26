# btail

Finding the last N lines of the outputs of `bpeek`, a gadget for openlava, aim to make work efficient.

# Usage

```shell
btail [-f] [-q queue_name | -m host_name | -J job_name
        | job_ID | "job_ID[index_list]"] [-h | -V] [-n lines]

Description:

   -n N,           prints the last N lines instead of the last 10.
   -f,             displays the output of the job using the command
                     tail -f.
   -q queue_name,  operates on your most recently submitted job in
                     the specified queue.
   -m host_name,   operates on your most recently submitted job that
                     has been dispatched to the specified host.
   -J job_name,    operates on your most recently submitted job that
                     has the specified job name.
   job_ID | "job_ID[index_list]",
                   operates on the specified job.
   -h,             prints comand usage to stdout and exits.
   -V,             prints btail version to stdout and exits.
```

