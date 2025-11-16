# Prescription Management

The Prescription Management (PM) allows consumers to create, read, search and update prescriptions.

## Configuration

Below properties using to configuring application, they provided in form of application property and OS environment variable.

| Property | Environment Variable | Description |
|----------|----------------------|-------------|
|`spring.datasource.url`|`SPRING_DATASOURCE_URL`|DBMS URL, includes DB name|
|`spring.datasource.username`|`SPRING_DATASOURCE_USERNAME`|Username for DB|
|`spring.datasource.password`|`SPRING_DATASOURCE_PASSWORD`|DB user's password|
|`app.hospital.management.url`|`APP_HOSPITAL_MANAGEMENT_URL`|Hospital Management application URL|

### Component Tests

For component tests there is `ctest` profile to use.
