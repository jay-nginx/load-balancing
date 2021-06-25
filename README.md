# load-balancing
This is the supporting GitHub link for the YouTube tutorial on configuring NGINX/Plus as Load Balancer


## I have commented out all the load-balancing methods, so the default, round-robin would work with this configuration as is. 

While Loop which I used to extract and print a specific value from the header:

    while true; do curl -sI <load-balancer-ip:port> | tr -d '\r' | sed -En 's/^Custom-Header: (.*)/\1/p'; sleep 1; done



##### Useful Links:
* [NGINX Plus - Load Balancing](https://www.nginx.com/products/nginx/load-balancing)
* [NGINX Plus - Technical Documents - HTTP Load Balancing](https://docs.nginx.com/nginx/admin-guide/load-balancer/http-load-balancer/)
* [NGINX - Technical Docs - Upstream Directive](http://nginx.org/en/docs/http/ngx_http_upstream_module.html)



## Built With

* [Ubuntu](https://ubuntu.com/) - My favourite Linux OS for testing
* [NGINX Plus](https://www.nginx.com/free-trial-request/) - NGINX Plus Trial


## Author

* **Jay Desai** - *Other Repos* - [jay-nginx](https://github.com/jay-nginx)




