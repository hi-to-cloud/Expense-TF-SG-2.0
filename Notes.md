Don't want to allow-all(0.0.0.0/0) to SG

Don't want to allow VPC CIDR(100.0.0.0/16) as a source

The best way is to pick SG as a source
Ex: MySql 3306 expense-dev-be
allow traffic on 3306 from the instances that are attached to expense-dev-be SG

![image](./SG.drawio.svg)