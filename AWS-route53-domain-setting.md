# AWS route53 domain setting

step

1. Register a domain with [GoDaddy][GoDaddy]
2. Create Hosted Zone on AWS route53
3. Select the Hosted Zone
4. Create Record Set, enter IP address on value and save
5. copy all the Value with NS record set
6. go to [GoDaddy][GoDaddy], select your domain and go to DNS manager
7. change nameserver to custom (wait the setup finish)
8. all the Value with NS record set need to enter (do not enter the last dot)

ref

- http://stackoverflow.com/questions/12433420/how-to-move-a-domain-from-godaddy-to-aws-route-53
- http://10buildaworld.info/2016/07/08/aws-domain-name-%E8%A8%AD%E5%AE%9A/

[GoDaddy]: https://tw.godaddy.com/

