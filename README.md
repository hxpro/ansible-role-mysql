hxpro.mysql
===========

Install
 - MySQL Server 8.0 Community Edition on CentOS 7 / 9 Stream

Requirements
------------

TODO

Role Variables
--------------
  - mysql_bind_address
  - mysql_binlog_cache_size
  - mysql_binlog_format
  - mysql_concurrent_insert
  - mysql_datadir
  - mysql_expire_logs_days
  - mysql_innodb_buffer_pool_size
  - mysql_innodb_file_per_table
  - mysql_innodb_flush_method
  - mysql_innodb_force_recovery
  - mysql_innodb_log_file_size
  - mysql_innodb_thread_concurrency
  - mysql_join_buffer_size
  - mysql_key_buffer_size
  - mysql_log_bin
  - mysql_log_error
  - mysql_log_slave_updates
  - mysql_long_query_time
  - mysql_low_priority_updates
  - mysql_max_allowed_packet
  - mysql_max_allowed_packet
  - mysql_max_connections
  - mysql_max_heap_table_size
  - mysql_myisam_sort_buffer_size
  - mysql_net_write_timeout
  - mysql_old_passwords
  - mysql_open_files_limit
  - mysql_pid_file
  - mysql_port
  - mysql_query_cache_limit
  - mysql_query_cache_size
  - mysql_query_cache_type
  - mysql_read_buffer_size
  - mysql_read_rnd_buffer_size
  - mysql_server_id
  - mysql_skip_name_resolve
  - mysql_slow_query_log
  - mysql_slow_query_log_file
  - mysql_socket
  - mysql_sort_buffer_size
  - mysql_sql_mode
  - mysql_symbolic_links
  - mysql_sync_binlog
  - mysql_table_open_cache
  - mysql_thread_cache_size
  - mysql_tmpdir
  - mysql_tmp_table_size
  - mysql_transaction_isolation
  - mysql_user

Dependencies
------------

 - hxpro.epel

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: hxpro.mysql }

License
-------

WTFPL

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
