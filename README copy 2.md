For the upload I used a simple postgres server with a Simple Create table script. Working mainly on the front end it was a script that I have used in the past with ease. Used a simple schema as not to get to deviated.

In regards to how I would optimize the loading, I would have and spent time attempting to paginate the data on load through the server. I knew it was going to be an issue when I peeked in on the CSV with the data size. I was not successful at having it work and moved the code to another page to work on at a later time. I need to learn better on how to either stream it on different page load or only pull the data when a different table with minimum of 25 rows. As for the interesting of the data into the database. The load of the file was not enough to bog down at any point but with larger data sets I would look at building up individual tables with advertisers and a different one with the SKUs and products.

Having a limited background in backend architecture and frameworks, I did enjoy working through the process of building it up.

Server-PostgreSQL
backend- node.js express server
frontend- React
