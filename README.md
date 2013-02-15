Made by Val Gorbunov

This is a work in progress file designed for analyzing db-templ files.
At the moment this creates a report.log file that gives statistics
on how many times "add", "time" and "close" commands are used
within a db-templ file. It also has a logic system that warns about
suspicious format/combination of those commands, alerting the user
to investigate possible mistakes.
