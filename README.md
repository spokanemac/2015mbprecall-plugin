# 2015mbprecall-plugin
Watchman Monitoring Plugin that reports if a computer qualifies for the 2015 MacBook Pro Battery Recall Repair Extension Program

If it is eligible, a one-time alert (200) is sent.

Ineligible exits 0.

Errors generate a warning (20)

# Installation

Copy files to `/Library/MonitoringClient/Plugins/`

Plugin will write a flag to disk upon successful completion.
