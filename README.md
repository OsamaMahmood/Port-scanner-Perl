# Port-scanner-Perl

Author: Osama Mahmood Site: http://securitytraning.com

This is only for educational Purposes use it on your own risk

Perl Compiler installed on windows on Linux Perl is installed by default

 I use activeperl from Activestate. It can be downloaded from the following url

http://www.activestate.com/activeperl

Compatibility: Windows , Linux or any device running python

It is a simple port scanning script which can be very handy while doing a penetration testing on a website it is quick and provide accurate information.

Linux Command Usage : perl portscan.pl

In the above given code the following line connects to remote server on specific port number

$socket = IO::Socket::INET->new(PeerAddr => $target , PeerPort => $port , Proto => 'tcp' , Timeout => 1);


If you want to report a problem related to this tool or if you want to request a new feature, feel

free to mail me on (osama.mahmood40@gmail.com)
