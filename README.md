#CIMongoDB - Codeigniter-mongodb-library

Wiki：https://fifths.github.com/mongodb-library-for-codeigniter.html

#Methods

##Insert Method
* `insert` Insert a new document into a collection

##Select Method
* `select` Get select fields from returned documents
* `where` OR `get_where` Where section of the query
* `where_in` Where something is in an array of something
* `where_in_all` Where something is in all of an array of * something
* `where_not_in` Where something is not in array of something
* `where_or` Where something is based on or
* `where_gt` Where something is greater than something
* `where_gte` Where something is greater than or equal to something
* `where_lt` Where something is less than something
* `where_lte` Where something is less than or equal to something
* `where_between` Where something is in between to something
* `where_between_ne` Where something is in between and but not equal to something
* `where_ne` Where something is not equal to something
* `like` Where something is search by like query
* `order_by` Order the results
* `limit` OR `offset` Limit the number of returned results
* `count` Document Count based on where query
* `find_one` Retrieve single document from collection

##Update Method
* `set` Sets a field to a value
* `unset_field` Unsets a field
* `addtoset` Adds a value to an array if doesn't exist
* `push` Pushes a value into an array field
* `pop` Pops a value from an array field
* `pull` Removes an array by the value of a field
* `rename_field` Rename a field
* `inc` Increments the value of a field
* `mul` Multiple the value of a field
* `max` Updates the value of the field to a specified value if the specified value is greater than the current value of the field
* `min` Updates the value of the field to a specified value if the specified value is less than the current value of the field.
* `update` Update a single document in a collection

##Delete Method
* `delete` Delete a single document in a collection

##DB Method
* `switch_db` Switch to a different database

##Extra Helper
* `date` Create or convert date to MongoDB based Date
* `timestamp` Create or convert Timestamp to MongoDB based Timestamp