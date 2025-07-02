# internee-cloud-internship-task-4
# Task 4: Cloud Monitoring and Log Analysis

## 🎯 Objective
Monitor the Internee.pk cloud-hosted system for performance and security.

## ✅ Tools Used
- AWS CloudWatch
- EC2 (Ubuntu)
- CloudWatch Agent

## 📋 Key Metrics Monitored
- CPU Usage
- Memory Utilization
- Disk Usage
- EC2 Instance Metrics
- Custom Log File: `/var/log/test.log`

## 🔔 Alerts Setup
- Created CloudWatch Alarm on CPUUtilization (threshold: 10%)
- Email notifications configured for critical usage

## 🧩 Configuration Files
- `cloudwatch-agent-config.json` – agent metrics config
- `log-config.json` – custom log collection config for log file

## 🖼️ Sample Output
- Metrics visible in AWS CloudWatch > Metrics > EC2
- Logs collected in CloudWatch Logs > Log Groups > MyAppLogs

## 📌 Status
✅ Task 4 completed successfully
