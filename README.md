HBase-Spring
============

Use spring to reduce operate HBase, just like JdbcTemplate, we sealed some method from HBase, for example, HBase's original public Result get(get) method, we instead it by public <T> T get(String row, T t), etc.
