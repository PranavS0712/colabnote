

hdlfscli -cert C:\Users\I513656\client.crt -key C:\Users\I513656\client.key -cacert C:\Users\I513656\ca.crt -k -s https://0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729.files.hdl.prod-eu20.hanacloud.ondemand.com -filecontainer 0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729  ls




hdlfscli -cert <PATH>\client.crt -key <PATH>\client.key -k -s <REST API Endpoint> -config myconfig -dump-config ls


hdlfscli -cert "%cert%" -key "%key%" -cacert "%cacert%" -k -s "%api_endpoint%" -filecontainer "%filecontainer%" -config hdlfscli_config.json  %command% 


hdlfscli -cert C:\Users\I513656\client.crt -key C:\Users\I513656\client.key -cacert C:\Users\I513656\ca.crt -k -s https://0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729.files.hdl.prod-eu20.hanacloud.ondemand.com -filecontainer 0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729 -config myconfig -dump-config ls


hdlfscli -cert C:\Users\I513656\\client.crt -key C:\Users\I513656\\client.key -k -s https://0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729.files.hdl.prod-eu20.hanacloud.ondemand.com -config myconfig -dump-config ls


hdlfscli -cert client.crt -key client.key -k -s https://0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729.files.hdl.prod-eu20.hanacloud.ondemand.com -config myconfig -dump-config ls


hdlfscli -config myconfig upload C:\Users\I513656\Downloads\TPCH /rawdata/tpch_data/TPCH


hdlfscli -cert client.crt -key client.key -cacert ca.crt -k -s https://0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729.files.hdl.prod-eu20.hanacloud.ondemand.com -filecontainer 0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729  ls




cat ca.crt DigiCertGlobalRootCA.crt DigiCertSHA2SecureServerCA.crt > combined-ca-bundle.crt


hdlfscli -cert client.crt -key client.key -cacert ca.crt -k -s https://0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729.files.hdl.prod-eu20.hanacloud.ondemand.com  -filecontainer 0bc4e9cc-a5a1-4a45-bea8-aeb11ef56729 cat /pythontut/First