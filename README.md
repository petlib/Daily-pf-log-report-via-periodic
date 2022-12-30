# Daily-pf-log-report-via-periodic
Get latest pf log records in your periodic security e-mail.

Drop script "591.pf-log-report" in /usr/local/etc/periodic/security

Disable this report with this line in /etc/periodic.conf.local:
security_pf_log_report_enable="NO"

Change daily interval to weekly with this line in /etc/periodic.conf.local:
security_pf_log_report_period=weekly
