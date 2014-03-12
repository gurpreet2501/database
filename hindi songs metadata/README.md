
### Meta data of हिन्दी songs (~1,53,409 tracks and ~21,272 albums)


#### Tables:  albums, artists, tracks 


#### Albums Table

| Field | Type         | Null | Key | Default | Extra          |
|-------|:------------:|:----:|:----|:-------:|:--------------:|
| id    | int(11)      | NO   | PRI | NULL    | auto_increment |
| title | varchar(500) | NO   |     | NULL    |                |
| year  | smallint(5)  | NO   |     | NULL    |                |
| hash  | varchar(15)  | NO   |     | NULL    |                |


#### Albums Table

| Field     | Type         | Null | Key | Default | Extra          |
|-----------|:------------:|:----:|:---:|:-------:|:--------------:|
| id        | int(11)      | NO   | PRI | NULL    | auto_increment |
| album_id  | int(11)      | NO   |     | NULL    |                |
| title     | varchar(500) | NO   |     | NULL    |                |
| artist_id | int(11)      | NO   |     | NULL    |                |
| time      | varchar(50)  | NO   |     | NULL    |                |

#### Artists Table


| Field | Type         | Null | Key | Default | Extra          |
|-------|:------------:|:----:|:---:|:-------:|:--------------:|
| id    | int(11)      | NO   | PRI | NULL    | auto_increment |
| name  | varchar(200) | NO   |     | NULL    |                |
