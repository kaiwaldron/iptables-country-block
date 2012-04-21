iptables-country-block
======================

Add iptable rules to drop packets to/from cidr blocks by country. This uses cidr
block lists compiled by ipdeny.com (see http://www.ipdeny.com/ipblocks/)

A cautionary note: This can result in a large number of iptables rules and
performance may suffer as a result.

## Usage
./iptables-country-block [whitespace separated list of 2 character iso counry codes]
