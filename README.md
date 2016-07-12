# OneAgent

A MySQL plugin to export linux performance metrics as status variables, including CPU/network/memory/disk space/disk IO, also some metrics of InnoDB internal data structure.

The plugin cannot be compiled as dynamic plugin libray, it can only be compiled as a static linked plugin. Please put the code into $MYSQL_SRC/plugin/oneagent , and then run cmake to compile the MySQL from the source code.

- Linux OS performance: http://www.onexsoft.com/zh/oneagent-linux-load-plugin.html
- MySQL Space Usage: http://www.onexsoft.com/zh/oneagent-server-space-usage.html
- InnoDB Perf Metrics: http://www.onexsoft.com/zh/oneagent-innodb-key-metrics.html


# Contact

Please submit a issue or send mail to flou(@)onexsoft.com
