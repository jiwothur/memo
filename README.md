# DB Schema

      CREATE TABLE topic(
            id INT(11) NOT NULL AUTO_INCREMENT,
            title VARCHAR(30) NOT NULL
            description TEXT NULL,
            created DATETIME,
            author_id INT(11),
            PRIMARY KEY(id)
        );
