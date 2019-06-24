# 100 Days Of Code - Log

### Day 1: Jun 20, 2019

**Today's Progress**: Use spaceship operator for first time.
```
$direction = $end<=>$start;
for($i=0; $i=$end; $i+=$direction) {
  ...
}
```
**Thoughts**: Should take advantage all the cool stuff php 7.x has to offer

### Day 2: Jun 21, 2019

**Today's Progress**: Reduced an sql query by removing unused columns from sub SELECT.

**Thoughts**: Table views and functions don't give any speed advantage. Only useful to keep the big queries in the db.

### Day 3: Jun 22, 2019

**Today's Progress**: Avoid some XSS injections in the database.

**Thoughts**: Cannot trust any data, either they come from the client or your db.

### Day 4: Jun 23, 2019

**Today's Progress**: Check for json format and dont modify the data when is posted.

**Thoughts**: Always use hmlentities() for html print. Escape quotes for tag props (href, src, ...)
