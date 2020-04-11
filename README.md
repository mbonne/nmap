# nmap
 Collection of nmap related scripts

to install nmap on macOS:
`brew install nmap`

## nmapssl
Runs a couple nmap scripts to check TLS versions and Cipher suites supported, Port scan, Traceroute, and guesses OS.
Script is essenially this: `nmap --script ssl-cert,ssl-enum-ciphers -A -T4 --traceroute "$1"`
includes sanity checks using DNS.
