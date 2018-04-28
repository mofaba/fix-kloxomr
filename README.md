# fix-kloxomr
small fix for kloxomr by musatafa ramadhan

change log:
04.29.2018
1.1 reconfigure port listen when using reverseproxy & webcache to handle ssl
    webfront(nginx, hiawatha, lighttpd) 80,443 >> webcache (varnish, ats) 8080 >> backend (apache) 30080,30443
1.2 fix new varnish config using varnish.params
