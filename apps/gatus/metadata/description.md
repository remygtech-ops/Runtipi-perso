# Gatus

A status dashboard configured with a YAML file: define endpoints, conditions (status code, response time, certificate expiry...) and alerts.

## Configuration

A sample file is installed at `runtipi/app-data/gatus/data/config/config.yaml`. Edit it, then restart the app. See the [Gatus documentation](https://github.com/TwiN/gatus#configuration) for all options. History is kept in SQLite under `data/storage`.
