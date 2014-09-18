#xl2db2xl
##Description
Perl script to download an ~~xls~~ html table file, parse it, store it in an sqlite database, then create a spreadsheet to email from the data
##HowTo
###Use
Rename config.example to config and change the two settings to your own  

Install the following cpan modules:  
-DBI  
-HTML::TableExtract  
-File::Fetch  
-DateTime  
-Config::Simple  
-Data::Dumper  
-File::Slurp  
-Spreadsheet::WriteExcel  

