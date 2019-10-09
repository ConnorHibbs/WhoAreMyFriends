# Who Are My F.R.I.E.N.D.S?

## Desciption
David Crane and Marta Kauffman, the creators of the classic TV sitcom F.R.I.E.N.D.S, are looking to revive the show as a Netflix Original. They are looking to hire the original *writers* and *directors* of the show, but Netflix has restricted them to only those that had a cummulative episode rating above the average for the show. They are looking for help to determine who to hire back (and in what order).

As Netflix is losing streaming rights to the show, they have restricted which episodes can be used to determine which creative minds to hire. They will provide you with a limited selection of episodes which they think are most representative of the show. Your task is to find the names of the geniuses you want on your staff (following Netflix's rules) and what their average episode score is.

## Assumptions:
  * "Cummulative Episode Rating" = avg(every _individual_ rating for episodes they worked on)

## Input: 
  * A single collection of data, in JSON notation.

## Output:
  * The names you want to hire, one on each line.
  * List should be sorted by average episode rating (highest on top), and then by names alphabetically in case of a tie
  * Ratings should be rounded to 2 decimal places

## Example Output (from entire data set, *001.in*):
```
Joe Regalbuto 9.10
Suzie V. Freeman 9.10
Brian Caldirola 9.00
Amy Toomin Straus 8.94
Jill Condon 8.94
Kevin Bright 8.77
Michael Borkow 8.75
Zachary Rosenblatt 8.72
Chris Brown 8.68
Pamela Fryman 8.68
Greg Malins 8.65
Michael Lembeck 8.63
Andrew Tsao 8.60
Betsy Borns 8.60
David J. Lagana 8.60
Richard Goodman 8.60
Tracy Reilly 8.60
Vanessa McCarthy 8.60
Scott Silveri 8.59
David Schwimmer 8.58
Alexa Junge 8.58
Pang-Ni Landrum 8.57
Brian Boyle 8.56
James Burrows 8.54
```