# dns_spoofer
this program is an example of how to redirect the target from facebook.com to our local web server apache2 or our web site.
how to use 
pip install netfilterqueue
servive apache2 start 
python dns_spoofer.py
now in other terminal 
iptables -I FORWARD -j NFQUEUE --queue-num 0
after you have completed your task 
iptables --flush

