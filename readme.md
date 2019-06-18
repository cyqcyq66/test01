create table student(
id int primary key auto_increment,
name varchar(32) not null,
age int unsigned not null,
sex enum("w","m"),
score float default 0.0)

create table interest(
id int primary key auto_increment,
name varchar(32) not null,
hobby set("sing","dance","draw"),
course char,
price decimal(6,2),
comment text);




