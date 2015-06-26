# ansible-datadog-postgresql

Installs Datadog agent monitoring for PostgreSQL

## Configuration

- `postgresql_databases`: An array of dictionaries. Dictionary must contain at least one attribute, `name`, containing the name of the database.
- `datadog_postgresql_monitor_tables`: An array of tables to monitor
- `datadog_postgresql_user`: The username of the account that you provisioned for DataDog's agent
- `datadog_postgresql_password`: The password of the account that you provisioned for DataDog's agent

## Author

Jason Berlinsky (http://www.jasonberlinsky.com/)
