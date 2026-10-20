# Atlas Industrie –- network architecture repository
Design of the Atlas Industrie network, the fictitious company of the
"Advanced Network Architectures" course. One folder per object type; the addressing plan is authoritative in`data/vlans.yml`
.
Local check:`python3 scripts/check_vlans.py` from the repository root.


## IPv6 Addressing

Unique Local Address (ULA) prefix: `fd73:6878:cdda::/48`

This prefix is reserved for the Atlas Industrie network
and will be reused throughout the project sessions.
