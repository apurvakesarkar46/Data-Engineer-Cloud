# Cloud, Linux, Database, and IAM Practical Portfolio

This repository contains documentation, configurations, and hands-on exercises covering SQL databases, Linux system administration, AWS cloud infrastructure, IAM access policies, and Azure resource management.

---

## Table of Contents
1. [SQL Database Practice](#1-sql-database-practice)
2. [Linux Directory and File Management](#2-linux-directory-and-file-management)
3. [AWS EC2 Virtual Machine Management](#3-aws-ec2-virtual-machine-management)
4. [AWS S3 & Custom IAM Policies](#4-aws-s3--custom-iam-policies)
5. [Azure Resource Management](#5-azure-resource-management)

---

## 1. SQL Database Practice
* **Database & Table Setup**: Created a database named `practical` and an `employees` table with attributes: `emp_id` (primary key), `emp_name`, `department`, and `salary`[cite: 1].
* **Data Population**: Inserted 8 employee records spanning IT, HR, Finance, and Sales departments[cite: 1].
* **Querying Data**: Wrote and executed a query using a subquery and `MAX(salary)` to retrieve the **Second Highest Distinct Salary** (`75,000`) from the table[cite: 1].

---

## 2. Linux Directory and File Management
* **Environment**: Connected and verified an Amazon Linux 2023 instance[cite: 1].
* **Directory Navigation**: Created and navigated into a new directory named `LinuxTask` using `mkdir` and `cd` commands[cite: 1].
* **File Operations**: 
  * Created blank text files (`file1.txt` and `file2.txt`) utilizing the `touch` command[cite: 1].
  * Verified absolute file paths and directory structures utilizing the `realpath` utility[cite: 1].

---

## 3. AWS EC2 Virtual Machine Management
* **Instance Provisioning**: Successfully launched and configured an Amazon EC2 `t3.micro` instance named `practical` in the `eu-north-1b` availability zone[cite: 1].
* **Instance Monitoring**: Monitored core instance attributes, including public/private IPv4 addresses, DNS names, and system status checks[cite: 1].

---

## 4. AWS S3 & Custom IAM Policies
* **S3 Storage**: Created a general-purpose Amazon S3 bucket named `apurva-s3-practice-2026` in the `us-east-1` region[cite: 1].
* **Custom IAM Policy (`S3ReadOnlyPolicy`)**: Designed and attached a customer-managed IAM policy to the `apurva` user[cite: 1].
* **Policy Configuration**: Configured explicit JSON permissions granting `s3:ListBucket` and `s3:GetObject` strictly scoped to the `apurva-s3-practice-2026` bucket and its contents[cite: 1].

---

## 5. Azure Resource Management
* **Resource Group Creation**: Configured and deployed a new resource group named `Pratical-rg` under an *Azure for Students* subscription[cite: 1].
* **Region Allocation**: Provisioned the resource group within the *Indonesia Central* region for centralized resource organization[cite: 1].
