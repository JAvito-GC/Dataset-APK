# Dataset-APK

This script was designed to read  more than 17,000 different APKS (Android Malware files). 
Once you have the API key supplied by the University of Luxembourg (AndroZoo), it requires a manual download, using a CSV file with as many entries as there are apks in the dataset, as an example:
curl -O --remote-header-name -G -d apikey=${APIKEY} -d sha256=${SHA256} \
https://androzoo.uni.lu/api/download
