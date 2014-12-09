Instructions

- create your database.
- import the database.sql.gz file into your database
- create a folder in your htdocs or public_html directory.
- extract site_files.zip into that directory
- edit the file sites\default\settings.php at line 215 to reflect your DB setup.
- remember to edit your host file and your vhost setup
- reset apache.
- visit the URL you setup in vhost and host file.
- if it produces a 500 Internal Server error, just refresh it again. This appears sometimes when the htaccess file is regenerating.
