# FreeBSD-Tweet-Twitter-API
1. Creating The Twitter Go Project

root@ns3:~ # cd /var
root@ns3:/var # mkdir -p twitter
root@ns3:/var # cd twitter
root@ns3:/var/twitter #

root@ns3:/var/twitter # chmod +x main.go
root@ns3:/var/twitter # chmod +x .env

root@ns3:/var/twitter # pkg install bash

root@ns3:/var/twitter # go mod init freeBSDtwitter
root@ns3:/var/twitter # go mod tidy

root@ns3:/var/twitter # go build

[root@ns3 /var/twitter]# ./freeBSDtwitter "Test: Hello world from golang"

[root@ns3 /var/twitter]# ./freeBSDtwitter "FreeBSD SSO:  Drupal and GitHub integration With Drupal OAuth Client:  https://youtu.be/YPsulDziw2U"

For more information:

https://www.unixwinbsd.site/2024/02/freebsd-tweets-send-post-tweet-using.html
