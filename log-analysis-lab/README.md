# Log Analysis Lab

## Objective

Practice basic log inspection and log analysis using standard Linux command line tools.

## Scenario

A simple log file is created to simulate login activity.  
The objective is to identify suspicious entries such as failed login attempts.

## Tools Used

- cat
- grep

## Example Commands

List log contents:

cat system.log

Search failed login attempts:

grep failed system.log

Search admin login activity:

grep admin system.log
