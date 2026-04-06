# AWS Auto Scaling Group Project

## Overview

This project demonstrates how to create an Auto Scaling Group in AWS using a Launch Template and Load Balancer.

## Architecture

* EC2 instances (Amazon Linux 2)
* Auto Scaling Group (min:1, max:3)
* Application Load Balancer

## Steps Performed

1. Created EC2 instance
2. Created Launch Template
3. Configured Auto Scaling Group
4. Attached Load Balancer
5. Configured scaling policy
6. Tested scaling using stress tool

## Output

Traffic is distributed across multiple instances automatically.
