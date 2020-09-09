mkdir v2ray-agent &&
cd v2ray-agent &&
curl https://raw.githubusercontent.com/ymlsn/v2go/master/install.sh -o install.sh &&
chmod +x install.sh &&
sed -i 's/\r//' install.sh && bash install.sh
