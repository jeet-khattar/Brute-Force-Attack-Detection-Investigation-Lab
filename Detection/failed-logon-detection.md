Detection objective -
Detect repeated Windows failed logon attempts that may indicate brute-force activity.

Data source - 
Windows Security Event Log

Event -
Event ID: 4625

Detection threshold -
5 or more failed logon events
within 1 minute

Alert type -
Real-time

Trigger -
Once

Action -
Add to Triggered Alerts
