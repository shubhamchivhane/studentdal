One to one mapping


1 .first create table 


CREATE TABLE `book_type` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `bookrtype` varchar(45) NOT NULL,
  `description` varchar(45) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=latin1;



CREATE TABLE `book_details` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `bookid` varchar(45) NOT NULL,
  `bookname` varchar(45) NOT NULL,
  `price` varchar(45) NOT NULL,
  `comments` varchar(45) NOT NULL,
  `noofcopies` int(11) NOT NULL,
  `book_type` int(11) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=5 DEFAULT CHARSET=latin1;


2. Topic cover here is:

annotation:  controller, service,repository, autowired ,pathvariable,onetoone mapping

modelmap, modelandview, 


