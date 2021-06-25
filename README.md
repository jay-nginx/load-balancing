# load-balancing
This is the supporting GitHub link for the YouTube tutorial on configuring NGINX/Plus as Load Balancer


## I have commented out all the load-balancing methods, so the default, round-robin would work with this configuration as is. 

While Loop which I used to extract and print a specific value from the header:
while true; do curl -sI <load-balancer-ip:port> | tr -d '\r' | sed -En 's/^Custom-Header: (.*)/\1/p'; sleep 1; done





