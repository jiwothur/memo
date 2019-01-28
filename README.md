# DB Schema

      CREATE TABLE topic(
            id INT(11) NOT NULL AUTO_INCREMENT,
            title VARCHAR(30) NOT NULL,
            description TEXT NULL,
            created DATETIME,
            PRIMARY KEY(id)
        );
