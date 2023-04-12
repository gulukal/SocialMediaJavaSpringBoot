# SETTINGS TO BE USED IN THE APPLICATION

## Google Cloud

### Google Cloud Storage

1- Login to Cloud Storage and create a new bucket . \
2- Define a new authority for access from IAM & Admin \
3- Creating a KEY file for the relevant user by entering the details  \
4- We can keep this file in the root folder of the application or in a different location.
5- A variable that specifies the path of this file is also defined for System Environment.
Key: GOOGLE_APPLICATION_CREDENTIALS
Value: /home/user/xxxx.json\
6- Necessary settings are made in the application.yml file. (OPTIONAL)
Used for manual authorization. It is not necessary.
spring:
    cloud:
        gcp:
            project-id: "endless-gamma-191414"
            credentials:
            scopes: https://www.googleapis.com/auth/devstorage.read_write
  \



deneme 1
deneme 2
gulukal

