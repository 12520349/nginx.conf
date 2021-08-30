Lệnh tạo file key:
pi@raspberrypi:~/ssl/textsms.net $ cat certificate.crt ca_bundle.crt  certificate.crt


##########################################################################################################################################


zerossl.com




##########################################################################################################################################

C:\nginx-1.18.0>nginx -s stop

C:\nginx-1.18.0>start nginx


##########################################################################################################################################









Lưu ý: chrome-you-connection-to-this-site-is-not-fully-secure
22

I think you get that message when you use https, but Google Chrome cannot correctly verify your certificate chain. You might want to make sure you have followed the instructions on that end fully, and that all certificates are installed correctly.

If/when you have, this is how you can check that every request uses https:

Open the website on Google Chrome
Press F12
Open the network tab
Press f5 to reload everthing
There it has all the information you should need. Hover over a request to check whether it uses http or https
