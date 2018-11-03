# Systronix_tcp_udp_helper
Generic helper lib including header parsing and creation, messages in and out, return code parsing, for TCP and UDP.
 This is just a placeholder at the moment ...which may remind me to get back to this. Soon I hope.
## Related libraries
We are using the WIZnet W5500 and WIZ850io parts. See also the Systronix repositories [W5500_test](https://github.com/systronix/W5500_Test) and [Ethernet2](https://github.com/systronix/Ethernet2)
### Header Creation
There is very little information about writing your own headers from scratch. On the server end, everyone uses existing tools like Apache and doesn't much think about it. In the embedded space that doesn't work. There's very little documentation I have found and no tutorials about how to write your own headers for even the simplest applications such as a temperature server. Browsers don't agree on how to handle many things which adds to the fun. Grrr. If I'm wrtong and you know of great resources for these things please contact me and/or join this repo and add to the wiki or related Google Docs.
