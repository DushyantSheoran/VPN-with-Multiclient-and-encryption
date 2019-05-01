VPN with MultiClient Support

• Implemented TLS/SSL based VPN in linux OS to provide secure extension of private network to an insecure world like internet.
• Tested in linux environment by analyzing telnet, SSH traffic and along with tunnel breaking test, it also provides multi-client support     by using PIPES.
• The host checking capability along with x509 certificate verification enhances VPN security by 20% resulting in 100% secure system.
• It provides integrity, authentication, confidentiality and transparency using Public Key Infrastructure(PKI) , AES Encryption,             Decryption…


To run the server:
$ sudo ./vpnserver

To run the client:
First change the SERVER_IP in vpnclient.c to match with the server's ip.
$ sudo ./vpnclient

Note: You also need to configure the TUN interfaces on both sides and set up routings. See the lab description for instructions.
