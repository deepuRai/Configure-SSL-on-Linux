# Configure-SSL-on-Linux
Confugure SSL certificate on Linux system (Centos &amp; Ubuntu)



#Step 1:- 
Install mod ssl and openssl module 

  yum install mod_ssl openssl/apt-get install mod_ssl openssl

#Step2 :- 
Generate below files for SSL (Please check with SSL provider)

SSLCertificateFile i.e. .crt file
SSLCertificateKeyFile i.e. .key file 
SSLCACertificateFile i.e. .intermediate.crt file

#Step3 :-

Configure Virtual host. Please see attached file Virtual_host_conf_SSL.txt


#Step 4:- 

Restart Apache


#Free SSL Certificate

If you want to have free ssl certificate then please visit below link for more details :- 

http://www.9lessons.info/2017/01/activate-free-ssl-certificate-for-your.html


