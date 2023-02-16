* LINQ methods **never** modify the input collections.
* LINQ methods return **IEnumerable<T>** - this means we can chain LINQ methods, as they also take IEnumerable<T> as input.
* LINQ uses deferred execution - query is only run when variable is used; we can run it, change the collection, run it again and it is a new query. LINQ queries are queries, not data.  Calling `ToList()` materializes the query.

Methods
* Where
* OrderBy
* Count
* All/Any
* Sum
* First/Last
* Distinct
* Grouping*
* Join*
* Include*
