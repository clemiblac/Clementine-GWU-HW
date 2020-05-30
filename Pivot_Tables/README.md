# Top Songs Pivot Summary

Pivot tables are exceptionally helpful when dealing with datasets that are large in scale, but contain enough similarities between data points to find commonalities. For this analysis, I took a 5000 row spreadsheet containing data on the top 5000 songs from 1901 onwards and used pivot tables to uncover which artists have the most songs in the top 5000, what they are, and what year they came out.

## Steps for Analysis

* I selected all of the data within my worksheet and then created a new pivot table.

* I made a pivot table that can be filtered by 'year' and contains two rows: 'artist' and 'name'.

  * I selected to present all of an artist's songs such that the songs are listed underneath the artist's name.

* I then updated the pivot table to contain values for:

  * How many songs an artist has in the top 5000.
  * The sum of the final_score of their songs.

*  I then sorted the pivot table by descending sum of the final_score.
