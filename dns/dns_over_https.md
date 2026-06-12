## DNS over HTTPS (DoH)

HTTPS encrypts data bi-rectionally - both requests and responses or vice versa.

Without DNS over HTTPS, DNS lookups will happen before HTTPS starts, in plain text.<br>
DoH fixes that by encrypting DNS requests too.

DoH can centralize DNS traffic to a few big providers, reducing user control.<br>
In a browser using a default DoH provider like Google or Cloudflare, all DNS requests go through them, so they could see any domain (not URL but mere domain) that the user visits.<br>
Some people consider that a privacy violation if not a security problem.
