# Google-Login

Before you use this, you have to do some setting in your Local System 

- Copy this file to your openSLL folder cacert.pem
- Go to Setting of your local server wamp or other one add this two ling inside PHP.ini
      curl.cainfo="‪Traget to openssl folder\openssl\cacert.pem"
      openssl.cafile="Traget to openssl folder\extras\openssl\cacert.pem"
      
restar your local server
