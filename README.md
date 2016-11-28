# XML Configuraton

1. Add bean definitions to src/main/resources/application-context.xml in order to 
wire up a NumberReaderImpl and JdbcNumberStorer.

   Notice that there are already bean definitions for a JdbcTemplate and a DataSource
   to an in-memory database. No need for you to set up a database server
   
2. Add a bean definition for a ConsoleReadNumberReporter and wire it into
the NumberReaderImpl via setter injection