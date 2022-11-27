# gsuite-cli-py

Thist script is just to extract informations from Google Suite email accounts.
User needs enough rights to parse the information.


## Usage
```
./gs_users_list.py -c credentials.json -au user@domain.ext
./gs_users_list.py -c credentials.json -au user@domain.ext, user2@domain2.ext2
```

cat credentials.json 
```
{
  "type": "service_account",
  "project_id": "corporate-XxXxX",
  "private_key_id": "XxX",
  "private_key": "-----BEGIN PRIVATE KEY-----\nXxXxX\nXxXxXX\n-----END PRIVATE KEY-----\n",
  "client_email": "gsuitescripts@corporate-XxX.iam.gserviceaccount.com",
  "client_id": "XxX",
  "auth_uri": "https://accounts.google.com/o/oauth2/auth",
  "token_uri": "https://accounts.google.com/o/oauth2/token",
  "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
  "client_x509_cert_url": "https://www.googleapis.com/robot/v1/metadata/x509/gsuitescripts%40corporate-XxX.iam.gserviceaccount.com"
}

```
