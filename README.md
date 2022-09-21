# exceptions

spring data jpa:
1. org.springframework.orm.jpa.JpaSystemException: 
    i. ids for this class must be manually assigned before calling save(): => Your saving object entity without setting primary key
    ii. nested exception is org.hibernate.loader.custom.NonUniqueDiscoveredSqlAliasException: => Selecting duplicates columns
