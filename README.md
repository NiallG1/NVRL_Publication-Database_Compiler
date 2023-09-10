# NVRL_Publication-Database_Compiler
Script for Publication database.
The goal of this project was to create a database containing all of the papers published by the National Virus Reference Lab (NVRL) of Ireland.
This database would then be automatically updated on a monthly basis from pubmed, and an email containing the names and authors of that months publications
circulated to all staff on a mailing list. This was accomplished using two seperate scripts, one handling the pulling and formatting all the publication data, and 
a second script which pushes that data to the database, and then pulls the relevant data for the automated emails.
