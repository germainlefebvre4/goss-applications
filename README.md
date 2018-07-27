# Goss Applications
Goss files for Applicaitons Sanity Checks

## Run your Sanity Checks

You generally store your applications gossfiles in `/var/goss/gossfiles/`.

Runyour  sanity checks
```
goss --gossfile /var/goss/gossfiles/app.yaml validate -f documentation
```
or
```
goss --gossfile /var/goss/gossfiles/app.yaml validate -f tap
```
