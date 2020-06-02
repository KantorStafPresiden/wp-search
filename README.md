# WP Search

## Installation
Clone the repo
```shell script
git clone https://github.com/KantorStafPresiden/wp-search
```
Rename the sample config file
```shell script
mv config/sample_config.json config/config.json
```
Edit MySQL connection info
```shell script
"Username": "db user",
"Password": "db password",
"Name": "db name",
"Hostname": "db host",
```
Change the binary permission (for linux)
```shell script
chmod +x wpsearch_linux_amd64
```
Run the application in background (for linux)
```shell script
./wpsearch_linux_amd64 &
```
Access the page on browser
