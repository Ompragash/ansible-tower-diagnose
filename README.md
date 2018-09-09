# ansible-tower-diagnose

_tower-diagnose_ tool pulls all the details from Anisble Tower using REST API endpoint and stores the output in a text file with their respective endpoint.

## Requirements

- tower-diagnose requires python 2.7+
- Install dependencies by executing the below command
```
pip install -r requirements.txt
```

## Getting started

- Edit _config.ini_ by passing Tower url, username and password.
- Now, execute tower_diagnose script like below
```
./tower_diagnose
```
- After execution it'll return bzip2 type tar file in the below format
```
tower-diagnose-%Y-%m-%d-%H-%M-%S.tar.bz2
```
- Unpack the newly created tar file and check for Tower endpoint details.


