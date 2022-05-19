---
title: "Automation with autosys"
mathjax: true
layout: post
categories:
    - tutorial
---

## Requirements and SETUP

TODO


## Script Automation

# Step 1. Create the file to be automatized

I wrote a python file and rename it with .wrk

**test.wrk**

```python

# https://docs.python.org/3/library/argparse.html

import configparser, sys

sql_file = sys.argv[1]
csv_file = sys.argv[2]

```



# Step 2. Create the jil file to specify which command should be run at which frequency

**JOBNAME.jil**

```
insert_job: JOB_NAME	    job_type: CMD or B
command: python test.wrk    $SQL_DIR/test.sql $OUTPUT_DIR/test.csv
machine:
owner:
permission: gx, ge, mx, me
date_conditins: 1
days_of_weeks: mo, tu, we, th, fr, sa, su	    # days when to run script
start_min: 00,05,10,15,20,25,30,35,40,45,50,55	    # minutes when to run
run_windows: "00:00-23:55"			    # hours when to run
description: "file description"
std_out_file: "*.log"
std_err_file: "*.err"
max_run_alarm: 5			# alarm if job not finished in 5 min
alarm_if_fail: 1
profile: "~/.bash_profile"
alarm_if_terminated: 0
timezone: US/Eastern
```

# Step 2.5: Update the job


**JOBNAME.jil**

```
update_job: JOB_NAME
command: python newcommand.wrk
```

**jil < JOBNAME.jil**


# Step 3: activate the job

```bash
jil < JOBNAME.jil	    # create the job
autorep -q -j JOBNAME	    # see the job
sentevent -E STARTJOB -J JOBNAME
```





# Ressources

- [Autosys Guide by Tracedynamics](https://www.tracedynamics.com/autosys/)
- [autorep commands](https://techdocs.broadcom.com/us/en/ca-enterprise-software/intelligent-automation/autosys-workload-automation/12-0-01/reference/ae-commands/monitor-and-report-on-workload/autorep-command-report-job-machine-and-variable-information.html)
- [sentevent commands](https://techdocs.broadcom.com/us/en/ca-enterprise-software/intelligent-automation/autosys-workload-automation/12-0-01/reference/ae-commands/control-workload/sendevent-command-change-the-executable-status-of-a-job.html)
- [How to write JIL file](https://autosys-tutorial-beginner.blogspot.com/2015/09/chapter-2-working-with-jil.html)
- [Autosys commands](https://www.techndata.com/useful-autosys-commands/)




