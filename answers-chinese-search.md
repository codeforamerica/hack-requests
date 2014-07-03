Hack Request: Implement Chinese Search
======

Answers uses Postgres full text search which supports English and Spanish by default. Unfortunately, to be able to search Chinese content, Postgres would need to use either a custom dictionary or extension. Heroku does not support using either of these.

Possible Solution
-----------------

Use a different hosting service than Heroku. We need more flexibility with our Postgres configuration. Other suggestions are welcome.
