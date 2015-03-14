_common\_schema_ is a framework for MySQL server administration.

**common\_schema 2.2 [released](http://code.openark.org/blog/mysql/common_schema-2-2-better-queryscript-isolation-tokudb-table_rotate-split-params)**

**common\_schema 2.1 [released](http://code.openark.org/blog/mysql/common_schema-2-1-released-advanced-improved-split-persistent-script-tables-more-schema-analysis-and-ahem-charts)**

**common\_schema 2.0.0-alpha [released](http://code.openark.org/blog/mysql/common_schema-2-0-0-alpha-rdebug-gpl)**, and includes [rdebug](http://common-schema.googlecode.com/svn/trunk/common_schema/doc/html/rdebug.html): Debugger and Debugging API for MySQL Stored Routines!

_common\_schema_ provides with:
  * A function library (text functions, security routines, execution and flow control, more...)
  * A set of informational and analysis views (security, schema design, processes, transactions, more...)
  * [QueryScript](http://common-schema.googlecode.com/svn/trunk/common_schema/doc/html/query_script.html) interpreter, allowing for server side scripting.
  * [rdebug](http://common-schema.googlecode.com/svn/trunk/common_schema/doc/html/rdebug.html): a debugger and debugging API for MySQL stored routines (alpha)

It introduces SQL based tools which simplify otherwise complex shell and client scripts, allowing the DBA to be independent of operating system, installed packages and dependencies.

It is a self contained _schema_, compatible with all MySQL >= 5.1 servers. Installed by importing the schema into the server, there is no need to configure nor compile. No special plugins are required, and no changes to your configuration.

_common\_schema_ has a small footprint (under 1MB).

```
  "The common_schema is to MySQL as jQuery is to javaScript"
  # Baron Schwartz, High Performance MySQL, 3rd Edition
```

**[Documentation](http://common-schema.googlecode.com/svn/trunk/common_schema/doc/html/introduction.html)**: a thorough guide to routines, views, the QueryScript language. Also available for [download](http://code.google.com/p/common-schema/downloads/list)

**[Bug reports](http://code.google.com/p/common-schema/issues/list)**

**[Announcements](http://code.openark.org/blog/tag/common_schema)** on developer's blog

#### Requirements ####
_common\_schema_ supports MySQL 5.1, 5.5, 5.6. It supports Percona Server & MariaDB.

_common\_schema_ enables features, upon installation, according to available server features.

On some versions you may need to set `stack_size = 256K` in your MySQL configuration file (256K is the default value as of MySQL 5.5)

#### License ####

_common\_schema_ 2.0 is licensed under the GPL license. Older versions are released under the New BSD License.