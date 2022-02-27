## Get started

unzip the folder
```bash
cd aws-mwaa-local-runner
```


### Step one: Building the Docker image

Build the docker image using the following command:
```bash
./mwaa-local-env build-image
```

### Step two: Running Apache Airflow

Run Apache Airflow using one of the following database backends.

#### Local runner

Runs a local Apache Airflow environment that is a close representation of MWAA by configuration.

```bash
./mwaa-local-env start
```

To stop the local environment, Ctrl+C on the terminal and wait till the local runner and the postgres containers are stopped.

### Step three: Accessing the Airflow UI

By default, the `bootstrap.sh` script creates a username and password for your local Airflow environment.

- Username: `admin`
- Password: `test`

#### Airflow UI

- Open the Apache Airlfow UI: <http://localhost:8080/>.


Trigger the DAG tutorail to run the test

### Credentials to S3 to check the files in S3 bucket:
Link to the AWS console: https://162120721992.signin.aws.amazon.com/console
username:checkS3
password:Checkings3
