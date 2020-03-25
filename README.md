# MuniCern
Hack36 2019 Project

Tech Stack: HTML, CSS, flask, openpyxl, bootstrap

MuniCern is a webapp that provides a public interface to post their issues to the Municipality which can look into them.
Dashboard shows all the issues currently open (fetching them from an excel file) and adds new issues
New issue is first checked. If at least 40% of it is similar to an existing issue,
it is discarded and the matching issue is suggested, else it gets added to the database.

Further functionality planned:
upvoting and commenting
a number of upvotes or comments which cross a threshold would push the issue into highlights indicating a primiary concern.
