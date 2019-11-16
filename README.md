Objective
=========

To investigate cloud technologies and determine which is appropriate for
your scenario.

Background
==========

Let’s assume for a minute that you have been put in charge of migrating
your existing data warehouse to the cloud. You have narrowed down the
possibilities to two AWS technologies: Amazon Athena or Redshift on RDS
in either case, you will also need to backup the raw data on Amazon S3.
(For this exercise, you have eliminated the need for Redshift Spectrum
and have decided to use Amazon’s On-demand Pricing.)

For this exercise, we’ll make the following assumptions.

-   First, don’t worry about how to structure the data in S3 or anything
    crazy like that. Just assume you’ll need to use these technologies
    together.
-   Your current data warehouse contains 1 TB of data.
-   Your data warehouse grows by 1 Gb a day.
-   You need to query the equivalent of the entire system once a day.
-   Since you only need to query the database once a day and loading the
    data into the database is assumed to require negligible compute
    power, you require more storage than you do compute.

To Turn-in
==========

Turn in a write up in Canvas with the following.

-   Describe the differences between the three technologies mentioned
    here.
    -   Amazon S3
    -   Amazon Athena
    -   Amazon Redshift
-   Describe the differences in pricing for each.
-   Work out how long you could use Athena before it makes sense to
    shift to Redshift.
-   Assume you need to query the database every hour and repeat the
    question above.

You can turn the assignment in any format you desire. This assignment
will be setup in R Studio Cloud if you want to use R Markdown. (Note
that a visualization would be nice for the last two questions.)
