# tor-relay
tor relay instructions

command line instructions

## start/stop/reload tor service

    /bin/systemctl stop  tor.service
    /bin/systemctl start  tor.service
    /bin/systemctl reload  tor.service

## check if service running

    ps aux | grep tor

## edit torrc

    vim /etc/tor/torrc

## watch log file

    tail -f /var/log/tor/notices.log

## fix /var/lib/tor permission issue

    chmod 700 -R /var/lib/tor
