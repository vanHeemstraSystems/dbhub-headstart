dbhub-headstart
# DBHub - Headstart

Based on "DBHub.io" at https://dbhub.io/

Based on "DBHub.io in GitHub" at https://github.com/sqlitebrowser/dbhub.io

This is an Open Source, free to use Cloud service, which can be hosted on premise as well to manage SQLite databases.

![Screenshot 2021-05-28 105015](https://user-images.githubusercontent.com/12828104/119957695-988e4580-bfa2-11eb-8cd2-86cbe09e7676.png)

## 100 - Sample Databases

See https://database.guide/2-sample-databases-sqlite/

### 100 - Chinook database

See https://github.com/lerocha/chinook-database

![Screenshot 2021-05-28 110307](https://user-images.githubusercontent.com/12828104/119959602-6da4f100-bfa4-11eb-9945-da6270e383bb.png)

See [Introduction to chinook SQLite sample database](https://www.sqlitetutorial.net/sqlite-sample-database/)

![sqlite-sample-database-color](https://user-images.githubusercontent.com/12828104/119960694-8530a980-bfa5-11eb-884f-2c18c8542760.jpg)

There are 11 tables in the chinook sample database.

 - ```employees``` table stores employees data such as employee id, last name, first name, etc. It also has a field named ReportsTo to specify who reports to whom.
 - ```customers``` table stores customers data.
 - ```invoices``` & ```invoice_items``` tables: these two tables store invoice data. The invoices table stores invoice header data and the invoice_items table stores the invoice line items data.
 - ```artists``` table stores artists data. It is a simple table that contains only the artist id and name.
 - ```albums``` table stores data about a list of tracks. Each album belongs to one artist. However, one artist may have multiple albums.
 - ```media_types``` table stores media types such as MPEG audio and AAC audio files.
 - ```genres``` table stores music types such as rock, jazz, metal, etc.
 - ```tracks``` table stores the data of songs. Each track belongs to one album.
 - ```playlists``` & ```playlist_track``` tables: playlists table store data about playlists. Each playlist contains a list of tracks. Each track may belong to multiple playlists. The relationship between the playlists table and tracks table is many-to-many. The playlist_track table is used to reflect this relationship.

### 200 - Northwind database

See https://github.com/jpwhite3/northwind-SQLite3/blob/master/Northwind.Sqlite3.create.sql
