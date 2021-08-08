# dns_spoofer
this program is an example of how to redirect the target from any site to our local web server apache2 or our web site.
how to use 
pip install netfilterqueue
servive apache2 start 
edit the code by changing domain name on line 10   and  your ip on line 12
python dns_spoofer.py
now in other terminal 
iptables -I FORWARD -j NFQUEUE --queue-num 0
after you have completed your task 
iptables --flush

