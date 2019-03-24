# SMSPushTX

Simple PushTX server to push Groestlcoin transactions via SMS (using Nexmo).

You can use either base64 or hex encoded raw transactions.

## Instructions
* git clone https://github.com/Groestlcoin/smspushtx
* pip install -r requirements.txt
* nano server.sh (change 0.0.0.0 to ip address of server)
* ./server.sh
* In Nexmo Settings: set Default SMS Setting > HTTP Method to `POST-JSON`
* In Nexmo Numbers: set SMS Inbound Webhook URL to `http://IpAddressOfServer/smspushtx`
