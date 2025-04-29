SUMMARY
================================================================================

These files contain anonymous ratings of different profiles

RATINGS FILE DESCRIPTION
================================================================================

All ratings are contained in the files "ratings.dat" and "ratings-Train.dat" are in the
following format:

UserID,ProfileID,Rating

- UserID is user who provided rating
- ProfileID is user who has been rated
- UserIDs range between 1 and 135,359
- ProfileIDs range between 1 and 220,970 (not every profile has been rated)
- Ratings are on a 1-10 scale where 10 is best (integer ratings only)
- Only users who provided at least 20 ratings were included
- Users who provided constant ratings were excluded

USERS FILE DESCRIPTION
================================================================================

User gender information is in the file "gender.dat" and is in the following
format:

UserID,Gender

- Gender is denoted by a "M" for male and "F" for female and "U" for unknown

