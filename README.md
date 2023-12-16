# Summary
The dataset is from Cyberchase TV Show. Cyberchase is an animated, educational kid’s television series, aired by the United States’ Public Broadcasting Service (PBS) since 2002. Originally designed to “show kids that math is everywhere and everyone can be good at it,” the world of Cyberchase centers on Jackie, Matt, and Inez as they team up with Digit—a “cybird”—to stop Hacker from taking over Cyberspace and infecting Motherboard.
Along the way, the quartet learn math, science, and problem-solving skills to thwart Hacker in his attempts.
In a database called cyberchase.db, using a table called episodes, chase answers to PBS’s questions about Cyberchase’s episodes thus far.

In 1.sql, write a SQL query to list the titles of all episodes in Cyberchase’s original season, Season 1.

In 2.sql, list the season number of, and title of, the first episode of every season.

In 3.sql, find the production code for the episode “Hackerized!”.

In 4.sql, write a query to find the titles of episodes that do not yet have a listed topic.

In 5.sql, find the title of the holiday episode that aired on December 31st, 2004.

In 6.sql, list the titles of episodes from season 6 (2008) that were released early, in 2007.

In 7.sql, write a SQL query to list the titles and topics of all episodes teaching fractions.

In 8.sql, write a query that counts the number of episodes released in the last 6 years, from 2018 to 2023, inclusive.

In 9.sql, write a query that counts the number of episodes released in Cyberchase’s first 6 years, from 2002 to 2007, inclusive.

In 10.sql, write a SQL query to list the ids, titles, and production codes of all episodes. Order the results by production code, from earliest to latest.

In 11.sql, list the titles of episodes from season 5, in reverse alphabetical order.

In 12.sql, count the number of unique episode titles.


# The Schema of the table

id, which uniquely identifies each row (episode) in the table

season, which is the season number in which the episode aired

episode_in_season, which is the episode’s number within its given season

title, which is the episode’s title

topic, which identifies the ideas the episode aimed to teach

air_date, which is the date (expressed as YYYY-MM-DD) on which the episode “aired” (i.e., was published)

production_code, which is the unique ID used by PBS to refer to each episode internally
