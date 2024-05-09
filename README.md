# Online Clinic System

![GitHub](https://img.shields.io/github/license/Piyushhbhutoria/OnlineClinicSystem)
![GitHub repo size](https://img.shields.io/github/repo-size/Piyushhbhutoria/OnlineClinicSystem)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FPiyushhbhutoria%2FOnlineClinicSystem.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FPiyushhbhutoria%2FOnlineClinicSystem?ref=badge_shield)

> **Feel Free To Contribute.**

## This Repo is Online Clinic System DBMS Project using PHP7.x, PHPmyadmin, mySQL5.x

Features

1. Admin, Customer, Doctor login
2. Sessions
3. Dynamic header
4. Book doctor and test Appointment
5. Online Report

## Features for Client

1. Can book an Appointment.
2. Can Delete an Appointment.
3. Can update Profile info.
4. Can update Password.

## Features for Doctors

1. Can Look for Appointment.
2. Can Delete an Appointment.
3. Can update basic Profile info.
4. Can update Password.

## Features for Admin

1. Can see current status for no. of Appointments.
2. Can upload Report.
3. Can update Doctor and test details.
4. Can update Password.

## Setup

Change credentials in config.php.

```php
<?php $con = mysqli_connect("localhost","user","password","database") or die(mysqli_error()); ?>
```

Open PHPmyadmin create a database named project.  
Import the project.sql file in database folder.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FPiyushhbhutoria%2FOnlineClinicSystem.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FPiyushhbhutoria%2FOnlineClinicSystem?ref=badge_large)