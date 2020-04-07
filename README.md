# Automate RDS Aurora Snapshots for disaster recovery

This repository contains a solution for implementing disaster recovery for Aurora database clusters by automating the process of cluster snapshot creation and copying to different AWS Regions. This process can be triggered on an ad hoc basis or on a defined schedule using either AWS Systems Manager Maintenance Windows or an Amazon CloudWatchevent rule, which uses an Automation document as a target based on your RTO and RPO requirements.

![Architecture](diagram.png)

This solution can be deployed by using this [template](SSM_automation_execute_script_CFN.yaml).

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

