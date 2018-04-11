This is a quick and dirty readme for this database.

It was written as a fun exercise after my friends and I realized we may have planned too many drinks with orange juice for our fruity drinks night.
The database is in a state I would consider ready for testing, although no professional eyes have judged it. 
It is populated with what I believe to be reasonable constraints and a well structured table system. There are no indices, this is intentional 
  because there also aren't really queries for it yet. Inclusion of indices may well be done after statistics are gained through test use and 
  stored procedures are written.
  
If I were to expand it at all, I would include one new table and, on the recipe table, three new columns.

The new table would be basically an enumeration, containing differnt units for measurement. Cup, kg, gram, oz, lbs, slice, whole, half. etc.
The new columns would be: Unitless numerator, unitless denominator, and a foreign key to the measurement types table described just above.
  Combined, this would give the ability to accurately portray the amounts of each ingredient in a recipe.
