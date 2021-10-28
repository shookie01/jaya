# jaya
 createdb movie_library
CREATE TABLE movies (
  title            TEXT NOT NULL,
  primary_director TEXT,
  actor_name  TEXT,
  year_released    INT,
);

INSERT INTO movies (title,  primary_director, actor_name, year_released, )
VALUES ('Dr. Strange', ' Scott Derrickson', 'Benedict Cumberbatch', 2005);
