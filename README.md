# JDBC_Assignment3
Uppgift med SQL-kod och JAVA-kod

SQL-code:

MANAGE DATABASE sqlandjava;

CREATE TABLE `sqljava`.`owners`(
`owner_id`INT NOT NULL,
`person_id`INT NOT NULL,
`car_id`INT NOT NULL,
PRIMARY KEY(`owner_id`));

INSERT INTO `sqljava`.`owners`(`owner_id`,`person_id`,`car_id`)VALUES('1','2','3');
INSERT INTO `sqljava`.`owners`(`owner_id,`person_id`,`car_id`)VALUES('2','1','4');
INSERT INTO `sqljava`.`owners`(`owner_id`,`person_id`,`car_id`)VALUES('3','3','2');
INSERT INTO `sqljava`.`owners`(`owner_id`,`person_id`,`car_id`)VALUES('4','4','1');

GRANT SELECT ON sqlandjava.owners TO user@localhost;

