- ALTER TABLE pages ADD COLUMN category varchar(20) DEFAULT NULL
- ALTER TABLE pages ADD COLUMN author varchar(200) DEFAULT '' AFTER content;
- ALTER TABLE pages ADD COLUMN substanceGroup varchar(20) DEFAULT '' AFTER author;