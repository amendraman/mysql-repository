-- MySQL Administrator dump 1.4
--
-- ------------------------------------------------------
-- Server version	5.1.73-community


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8 */;

/*!40014 SET @OLD_UNIQUE_CHECKS=@@UNIQUE_CHECKS, UNIQUE_CHECKS=0 */;
/*!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 */;
/*!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' */;


--
-- Create schema aadharmuleproject
--

CREATE DATABASE IF NOT EXISTS aadharmuleproject;
USE aadharmuleproject;

--
-- Definition of table `aadhar`
--

DROP TABLE IF EXISTS `aadhar`;
CREATE TABLE `aadhar` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `fullname` varchar(45) NOT NULL DEFAULT '',
  `phonenumber` int(10) unsigned NOT NULL DEFAULT '0',
  `address` varchar(45) NOT NULL DEFAULT '',
  `username` varchar(45) NOT NULL DEFAULT '',
  `password` varchar(45) NOT NULL DEFAULT '',
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `aadhar`
--

/*!40000 ALTER TABLE `aadhar` DISABLE KEYS */;
/*!40000 ALTER TABLE `aadhar` ENABLE KEYS */;

--
-- Create schema bankbalance
--

CREATE DATABASE IF NOT EXISTS bankbalance;
USE bankbalance;

--
-- Definition of table `bank`
--

DROP TABLE IF EXISTS `bank`;
CREATE TABLE `bank` (
  `username` varchar(45) NOT NULL DEFAULT '',
  `password` varchar(45) NOT NULL DEFAULT '',
  `balance` int(10) unsigned NOT NULL DEFAULT '0'
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `bank`
--

/*!40000 ALTER TABLE `bank` DISABLE KEYS */;
INSERT INTO `bank` (`username`,`password`,`balance`) VALUES 
 ('Anand','Anand',1000);
/*!40000 ALTER TABLE `bank` ENABLE KEYS */;

--
-- Create schema campusmind
--

CREATE DATABASE IF NOT EXISTS campusmind;
USE campusmind;

--
-- Definition of table `campus`
--

DROP TABLE IF EXISTS `campus`;
CREATE TABLE `campus` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(45) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `campus`
--

/*!40000 ALTER TABLE `campus` DISABLE KEYS */;
INSERT INTO `campus` (`id`,`name`) VALUES 
 (1,'akshatha');
/*!40000 ALTER TABLE `campus` ENABLE KEYS */;

--
-- Create schema employeecrud
--

CREATE DATABASE IF NOT EXISTS employeecrud;
USE employeecrud;

--
-- Definition of table `employee`
--

DROP TABLE IF EXISTS `employee`;
CREATE TABLE `employee` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(45) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=7 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `employee`
--

/*!40000 ALTER TABLE `employee` DISABLE KEYS */;
INSERT INTO `employee` (`id`,`name`) VALUES 
 (1,'rocky'),
 (2,'sendo'),
 (3,'suraj'),
 (4,'mahesh'),
 (5,'shubham'),
 (6,'sachin');
/*!40000 ALTER TABLE `employee` ENABLE KEYS */;

--
-- Create schema fullfledgedaadharproject
--

CREATE DATABASE IF NOT EXISTS fullfledgedaadharproject;
USE fullfledgedaadharproject;

--
-- Definition of table `aadharinfo`
--

DROP TABLE IF EXISTS `aadharinfo`;
CREATE TABLE `aadharinfo` (
  `ID` int(11) NOT NULL AUTO_INCREMENT,
  `FullName` varchar(100) NOT NULL,
  `PhoneNumber` int(11) NOT NULL,
  `BirthMark` varchar(100) NOT NULL,
  `Username` varchar(100) NOT NULL,
  `Pass` varchar(100) NOT NULL,
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `aadharinfo`
--

/*!40000 ALTER TABLE `aadharinfo` DISABLE KEYS */;
/*!40000 ALTER TABLE `aadharinfo` ENABLE KEYS */;


--
-- Definition of table `address`
--

DROP TABLE IF EXISTS `address`;
CREATE TABLE `address` (
  `ID` int(11) NOT NULL,
  `State` varchar(100) NOT NULL,
  `District` varchar(100) NOT NULL,
  `PostalCode` int(11) NOT NULL,
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `address`
--

/*!40000 ALTER TABLE `address` DISABLE KEYS */;
/*!40000 ALTER TABLE `address` ENABLE KEYS */;


--
-- Definition of table `familydetails`
--

DROP TABLE IF EXISTS `familydetails`;
CREATE TABLE `familydetails` (
  `ID` int(11) NOT NULL,
  `FatherName` varchar(30) NOT NULL,
  `MotherName` varchar(30) NOT NULL,
  `MartialStatus` varchar(30) NOT NULL,
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `familydetails`
--

/*!40000 ALTER TABLE `familydetails` DISABLE KEYS */;
/*!40000 ALTER TABLE `familydetails` ENABLE KEYS */;

--
-- Create schema mulecampusmind
--

CREATE DATABASE IF NOT EXISTS mulecampusmind;
USE mulecampusmind;

--
-- Definition of table `campusmind`
--

DROP TABLE IF EXISTS `campusmind`;
CREATE TABLE `campusmind` (
  `mid` int(11) NOT NULL,
  `name` varchar(30) DEFAULT NULL,
  `leadname` varchar(30) DEFAULT NULL,
  PRIMARY KEY (`mid`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `campusmind`
--

/*!40000 ALTER TABLE `campusmind` DISABLE KEYS */;
INSERT INTO `campusmind` (`mid`,`name`,`leadname`) VALUES 
 (1,'Rocky','sendo'),
 (2,'Pooja','kausalya'),
 (3,'vidit','abhiskek'),
 (4,'ragini','kaushalya');
/*!40000 ALTER TABLE `campusmind` ENABLE KEYS */;

--
-- Create schema muleflightdatabase
--

CREATE DATABASE IF NOT EXISTS muleflightdatabase;
USE muleflightdatabase;

--
-- Definition of table `american`
--

DROP TABLE IF EXISTS `american`;
CREATE TABLE `american` (
  `ID` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `code` varchar(45) NOT NULL,
  `price` int(11) NOT NULL,
  `departureDate` varchar(45) NOT NULL,
  `origin` varchar(45) NOT NULL,
  `destination` varchar(45) NOT NULL,
  `emptySeats` int(11) NOT NULL,
  `planeId` int(10) unsigned NOT NULL,
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `american`
--

/*!40000 ALTER TABLE `american` DISABLE KEYS */;
INSERT INTO `american` (`ID`,`code`,`price`,`departureDate`,`origin`,`destination`,`emptySeats`,`planeId`) VALUES 
 (1,'ER38sd',400,'2016/03/20','MUA','SFO',0,1),
 (2,'ER45if',346,'2016/02/11','MUA','LAX',52,2);
/*!40000 ALTER TABLE `american` ENABLE KEYS */;


--
-- Definition of table `plane`
--

DROP TABLE IF EXISTS `plane`;
CREATE TABLE `plane` (
  `pID` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `type` varchar(45) NOT NULL,
  `totalSeats` int(10) unsigned NOT NULL,
  PRIMARY KEY (`pID`) USING BTREE
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `plane`
--

/*!40000 ALTER TABLE `plane` DISABLE KEYS */;
INSERT INTO `plane` (`pID`,`type`,`totalSeats`) VALUES 
 (1,'Boeing 737 ',150),
 (2,'Boeing 777',300);
/*!40000 ALTER TABLE `plane` ENABLE KEYS */;

--
-- Create schema muleflightdatabase2
--

CREATE DATABASE IF NOT EXISTS muleflightdatabase2;
USE muleflightdatabase2;

--
-- Definition of table `american`
--

DROP TABLE IF EXISTS `american`;
CREATE TABLE `american` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `code` varchar(45) NOT NULL,
  `price` int(10) unsigned NOT NULL,
  `departureDate` varchar(45) NOT NULL,
  `origin` varchar(45) NOT NULL,
  `destination` varchar(45) NOT NULL,
  `emptySeats` int(10) unsigned NOT NULL,
  `planeType` varchar(45) NOT NULL,
  `totalSeats` int(10) unsigned NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=5 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `american`
--

/*!40000 ALTER TABLE `american` DISABLE KEYS */;
INSERT INTO `american` (`id`,`code`,`price`,`departureDate`,`origin`,`destination`,`emptySeats`,`planeType`,`totalSeats`) VALUES 
 (1,'ER38sd',400,'20/03/2018','MUA','SFO',0,'Boeing 737',150),
 (2,'ER45if',345,'22/03/2018','MUA','LAX',10,'Boeing 777',300),
 (3,'Erfj64k',500,'24/03/2018','SFO','LAX',8,'Boeing 878',200),
 (4,'ERjfh3',340,'26/03/2018','SFO','MUA',70,'Boeing 737',180);
/*!40000 ALTER TABLE `american` ENABLE KEYS */;

--
-- Create schema mulepolldb
--

CREATE DATABASE IF NOT EXISTS mulepolldb;
USE mulepolldb;

--
-- Definition of table `employees`
--

DROP TABLE IF EXISTS `employees`;
CREATE TABLE `employees` (
  `no` int(11) NOT NULL,
  `dob` date NOT NULL,
  `first_name` varchar(14) NOT NULL,
  `last_name` varchar(16) NOT NULL,
  `gender` varchar(1) NOT NULL,
  `hire_date` date NOT NULL,
  PRIMARY KEY (`no`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `employees`
--

/*!40000 ALTER TABLE `employees` DISABLE KEYS */;
INSERT INTO `employees` (`no`,`dob`,`first_name`,`last_name`,`gender`,`hire_date`) VALUES 
 (1011,'1985-09-02','Chava','Puckett','F','2008-10-12'),
 (1012,'1971-12-03','Christopher','Tillman','M','2006-11-01'),
 (1013,'1975-07-31','Judith','David','F','2010-11-20'),
 (1014,'1957-08-03','Neil','Ford','F','2008-09-04'),
 (1015,'1977-01-09','Daryl','Wolfe','M','2007-09-14');
/*!40000 ALTER TABLE `employees` ENABLE KEYS */;


--
-- Definition of table `roles`
--

DROP TABLE IF EXISTS `roles`;
CREATE TABLE `roles` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `emp_no` int(11) DEFAULT NULL,
  `role` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=5 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `roles`
--

/*!40000 ALTER TABLE `roles` DISABLE KEYS */;
INSERT INTO `roles` (`id`,`emp_no`,`role`) VALUES 
 (1,1011,'Sr. Developer'),
 (2,1012,'Office Manager'),
 (3,1013,'Secretary'),
 (4,1014,'Engineer');
/*!40000 ALTER TABLE `roles` ENABLE KEYS */;

--
-- Create schema mulesoaporchard
--

CREATE DATABASE IF NOT EXISTS mulesoaporchard;
USE mulesoaporchard;

--
-- Definition of table `leads`
--

DROP TABLE IF EXISTS `leads`;
CREATE TABLE `leads` (
  `leadid` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `leadname` varchar(45) NOT NULL,
  `leadlocation` varchar(45) NOT NULL,
  PRIMARY KEY (`leadid`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `leads`
--

/*!40000 ALTER TABLE `leads` DISABLE KEYS */;
INSERT INTO `leads` (`leadid`,`leadname`,`leadlocation`) VALUES 
 (1,'Vivek','kalinga'),
 (2,'abhishek','kalinga'),
 (3,'puneet','kalinga');
/*!40000 ALTER TABLE `leads` ENABLE KEYS */;


--
-- Definition of table `minds`
--

DROP TABLE IF EXISTS `minds`;
CREATE TABLE `minds` (
  `mindid` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `mindname` varchar(45) NOT NULL,
  `mindtrack` varchar(45) NOT NULL,
  PRIMARY KEY (`mindid`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `minds`
--

/*!40000 ALTER TABLE `minds` DISABLE KEYS */;
INSERT INTO `minds` (`mindid`,`mindname`,`mindtrack`) VALUES 
 (1,'Tanvi','java'),
 (2,'Rocky','EAI'),
 (3,'Shubham','EAI');
/*!40000 ALTER TABLE `minds` ENABLE KEYS */;


--
-- Definition of table `track`
--

DROP TABLE IF EXISTS `track`;
CREATE TABLE `track` (
  `trackid` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `track` varchar(45) NOT NULL,
  PRIMARY KEY (`trackid`)
) ENGINE=InnoDB AUTO_INCREMENT=7 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `track`
--

/*!40000 ALTER TABLE `track` DISABLE KEYS */;
INSERT INTO `track` (`trackid`,`track`) VALUES 
 (1,'Java'),
 (2,'EAI'),
 (3,'SDAT'),
 (4,'WebTech'),
 (5,'DA'),
 (6,'DS');
/*!40000 ALTER TABLE `track` ENABLE KEYS */;

--
-- Create schema orcharddb
--

CREATE DATABASE IF NOT EXISTS orcharddb;
USE orcharddb;

--
-- Definition of table `campusmind`
--

DROP TABLE IF EXISTS `campusmind`;
CREATE TABLE `campusmind` (
  `mid` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(45) NOT NULL,
  `track` varchar(45) NOT NULL,
  PRIMARY KEY (`mid`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `campusmind`
--

/*!40000 ALTER TABLE `campusmind` DISABLE KEYS */;
INSERT INTO `campusmind` (`mid`,`name`,`track`) VALUES 
 (1,'Rocky','EAI'),
 (2,'Tanvi','Java'),
 (3,'Sendo','WebTech');
/*!40000 ALTER TABLE `campusmind` ENABLE KEYS */;


--
-- Definition of table `lead`
--

DROP TABLE IF EXISTS `lead`;
CREATE TABLE `lead` (
  `l_id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `l_name` varchar(45) NOT NULL,
  `t_id` int(10) unsigned NOT NULL,
  PRIMARY KEY (`l_id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `lead`
--

/*!40000 ALTER TABLE `lead` DISABLE KEYS */;
/*!40000 ALTER TABLE `lead` ENABLE KEYS */;


--
-- Definition of table `minds`
--

DROP TABLE IF EXISTS `minds`;
CREATE TABLE `minds` (
  `m_id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `m_name` varchar(45) NOT NULL,
  `t_id` int(10) unsigned NOT NULL,
  PRIMARY KEY (`m_id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `minds`
--

/*!40000 ALTER TABLE `minds` DISABLE KEYS */;
/*!40000 ALTER TABLE `minds` ENABLE KEYS */;


--
-- Definition of table `track`
--

DROP TABLE IF EXISTS `track`;
CREATE TABLE `track` (
  `t_id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `t_name` varchar(45) NOT NULL,
  PRIMARY KEY (`t_id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `track`
--

/*!40000 ALTER TABLE `track` DISABLE KEYS */;
/*!40000 ALTER TABLE `track` ENABLE KEYS */;

--
-- Create schema restdatabase
--

CREATE DATABASE IF NOT EXISTS restdatabase;
USE restdatabase;

--
-- Definition of table `person`
--

DROP TABLE IF EXISTS `person`;
CREATE TABLE `person` (
  `ID` int(10) unsigned NOT NULL,
  `FULL_NAME` varchar(255) NOT NULL,
  `AGE` int(10) unsigned NOT NULL,
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data for table `person`
--

/*!40000 ALTER TABLE `person` DISABLE KEYS */;
INSERT INTO `person` (`ID`,`FULL_NAME`,`AGE`) VALUES 
 (1,'Rocky',22),
 (2,'Vidit',23),
 (3,'Shubham',22);
/*!40000 ALTER TABLE `person` ENABLE KEYS */;

--
-- Create schema rollbackdatabase
--

CREATE DATABASE IF NOT EXISTS rollbackdatabase;
USE rollbackdatabase;

--
-- Definition of table `info`
--

DROP TABLE IF EXISTS `info`;
CREATE TABLE `info` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `Country` varchar(45) NOT NULL DEFAULT '',
  `Year` int(10) unsigned NOT NULL DEFAULT '0',
  `Population` int(10) unsigned NOT NULL DEFAULT '0',
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=9 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `info`
--

/*!40000 ALTER TABLE `info` DISABLE KEYS */;
INSERT INTO `info` (`id`,`Country`,`Year`,`Population`) VALUES 
 (1,'India',2018,3123),
 (2,'Srilanka',2018,2123),
 (3,'Malaysia',2017,3123),
 (4,'Syria',2018,234),
 (6,'Lebanon',2018,345),
 (8,'Lakshadweep',2018,343);
/*!40000 ALTER TABLE `info` ENABLE KEYS */;

--
-- Create schema soapwsdlimplinmuleandconsume
--

CREATE DATABASE IF NOT EXISTS soapwsdlimplinmuleandconsume;
USE soapwsdlimplinmuleandconsume;

--
-- Definition of table `leads`
--

DROP TABLE IF EXISTS `leads`;
CREATE TABLE `leads` (
  `leadid` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `leadname` varchar(45) NOT NULL,
  `leadtrack` varchar(45) NOT NULL,
  PRIMARY KEY (`leadid`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `leads`
--

/*!40000 ALTER TABLE `leads` DISABLE KEYS */;
INSERT INTO `leads` (`leadid`,`leadname`,`leadtrack`) VALUES 
 (1,'Abhishek','java'),
 (2,'Vivek','java'),
 (3,'nitish','Webtech');
/*!40000 ALTER TABLE `leads` ENABLE KEYS */;


--
-- Definition of table `minds`
--

DROP TABLE IF EXISTS `minds`;
CREATE TABLE `minds` (
  `mindid` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `mindname` varchar(45) NOT NULL,
  `track` varchar(45) NOT NULL,
  PRIMARY KEY (`mindid`)
) ENGINE=InnoDB AUTO_INCREMENT=103 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `minds`
--

/*!40000 ALTER TABLE `minds` DISABLE KEYS */;
INSERT INTO `minds` (`mindid`,`mindname`,`track`) VALUES 
 (100,'Rocky','EAI'),
 (101,'Ragini','DS'),
 (102,'Vidit','EAI');
/*!40000 ALTER TABLE `minds` ENABLE KEYS */;


--
-- Definition of table `track`
--

DROP TABLE IF EXISTS `track`;
CREATE TABLE `track` (
  `trackid` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `track` varchar(45) NOT NULL,
  PRIMARY KEY (`trackid`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;

--
-- Dumping data for table `track`
--

/*!40000 ALTER TABLE `track` DISABLE KEYS */;
INSERT INTO `track` (`trackid`,`track`) VALUES 
 (1,'Java'),
 (2,'Webtech'),
 (3,'DS');
/*!40000 ALTER TABLE `track` ENABLE KEYS */;




/*!40101 SET SQL_MODE=@OLD_SQL_MODE */;
/*!40014 SET FOREIGN_KEY_CHECKS=@OLD_FOREIGN_KEY_CHECKS */;
/*!40014 SET UNIQUE_CHECKS=@OLD_UNIQUE_CHECKS */;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
