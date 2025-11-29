# Load Balancer Project (ALU)

## Files
- `0-custom_http_response_header` - installs Nginx and sets the `X-Served-By` header with the server hostname.
- `1-install_load_balancer` - installs HAProxy and configures a roundrobin load balancer for two web servers.

## Usage

1. Ensure server hostnames:
