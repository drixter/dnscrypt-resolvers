
# *** THIS LIST IS FOR OLD DNSCRYPT-PROXY VERSIONS ***

Version 2 of the list is for dnscrypt-proxy <= 2.0.42 users.

If you are running up-to-date software, replace `/v2/` with `/v3/` in the sources URLs
of the `dnscrypt-proxy.toml` file (relevant lines start with `urls = ['https://...']`
and are present in the `[sources]` section).

THIS LIST IS AUTOMATICALLY GENERATED AS A SUBSET OF THE V3 LIST. DO NOT EDIT IT MANUALLY.

If you want to contribute changes to a resolvers list, only edit files from the `v3` directory.

--

## adguard-dns-family

Adguard DNS with safesearch and adult content blocking

sdns://AQIAAAAAAAAAFDE3Ni4xMDMuMTMwLjEzMjo1NDQzILgxXdexS27jIKRw3C7Wsao5jMnlhvhdRUXWuMm1AFq6ITIuZG5zY3J5cHQuZmFtaWx5Lm5zMS5hZGd1YXJkLmNvbQ


## cisco-familyshield

Block websites not suitable for children (DNSCrypt protocol)

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

Currently incompatible with DNS anonymization.

sdns://AQEAAAAAAAAADjIwOC42Ny4yMjAuMTIzILc1EUAgbyJdPivYItf9aR6hwzzI1maNDL4Ev6vKQ_t5GzIuZG5zY3J5cHQtY2VydC5vcGVuZG5zLmNvbQ


## cisco-familyshield-ipv6

Block websites not suitable for children (IPv6)

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

sdns://AgAAAAAAAAAADDE0Ni4xMTIuNDEuMyBUDrXp92r0ml9Aq9cu3mXf2w_ugmc61w74ZllxOxR-Vxxkb2guZmFtaWx5c2hpZWxkLm9wZW5kbnMuY29tCi9kbnMtcXVlcnk


## cleanbrowsing-adult

Blocks access to all adult, pornographic and explicit sites. It does
not block proxy or VPNs, nor mixed-content sites. Sites like Reddit
are allowed. Google and Bing are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AQMAAAAAAAAAEzE4NS4yMjguMTY4LjEwOjg0NDMgvKwy-tVDaRcfCDLWB1AnwyCM7vDo6Z-UGNx3YGXUjykRY2xlYW5icm93c2luZy5vcmc


## cleanbrowsing-adult-ipv6

Blocks access to all adult, pornographic and explicit sites. It does
not block proxy or VPNs, nor mixed-content sites. Sites like Reddit
are allowed. Google and Bing are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AQMAAAAAAAAAFVsyYTBkOjJhMDA6MTo6MV06ODQ0MyC8rDL61UNpFx8IMtYHUCfDIIzu8Ojpn5QY3HdgZdSPKRFjbGVhbmJyb3dzaW5nLm9yZw


## cleanbrowsing-family

Blocks access to all adult, pornographic and explicit sites. It also
blocks proxy and VPN domains that are used to bypass the filters.
Mixed content sites (like Reddit) are also blocked. Google, Bing and
Youtube are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AQMAAAAAAAAAFDE4NS4yMjguMTY4LjE2ODo4NDQzILysMvrVQ2kXHwgy1gdQJ8MgjO7w6OmflBjcd2Bl1I8pEWNsZWFuYnJvd3Npbmcub3Jn


## cleanbrowsing-family-ipv6

Blocks access to all adult, pornographic and explicit sites. It also
blocks proxy and VPN domains that are used to bypass the filters.
Mixed content sites (like Reddit) are also blocked. Google, Bing and
Youtube are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AQMAAAAAAAAAFFsyYTBkOjJhMDA6MTo6XTo4NDQzILysMvrVQ2kXHwgy1gdQJ8MgjO7w6OmflBjcd2Bl1I8pEWNsZWFuYnJvd3Npbmcub3Jn


## cloudflare-family

Cloudflare DNS (anycast) with malware protection and parental control - aka 1.1.1.3 / 1.0.0.3

sdns://AgMAAAAAAAAABzEuMC4wLjMAGWZhbWlseS5jbG91ZGZsYXJlLWRucy5jb20KL2Rucy1xdWVyeQ


## cloudflare-family-ipv6

Cloudflare DNS over IPv6 (anycast) with malware protection and parental control

sdns://AgMAAAAAAAAAFlsyNjA2OjQ3MDA6NDcwMDo6MTExM10AGWZhbWlseS5jbG91ZGZsYXJlLWRucy5jb20KL2Rucy1xdWVyeQ


## dnsforfamily

(DNSCrypt Protocol) Block adult websites, gambling websites, malwares and advertisements.
It also enforces safe search in: Google, YouTube, Bing, DuckDuckGo and Yandex.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of December 2020 2.7 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 3 years now.

Warning: This server is incompatible with anonymization.

Provided by: https://dnsforfamily.com

sdns://AQIAAAAAAAAADDc4LjQ3LjY0LjE2MSATJeLOABXNSYcSJIoqR5_iUYz87Y4OecMLB84aEAKPrRBkbnNmb3JmYW1pbHkuY29t


## dnsforfamily-doh

(DoH Protocol) Block adult websites, gambling websites, malwares and advertisements.
It also enforces safe search in: Google, YouTube, Bing, DuckDuckGo and Yandex.
Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.
As of December 2020 2.7 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 3 years now.

Provided by: https://dnsforfamily.com

sdns://AgIAAAAAAAAADTk1LjIxNy4yMTMuOTSgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984YZG5zLWRvaC5kbnNmb3JmYW1pbHkuY29tCi9kbnMtcXVlcnk


## dnsforfamily-doh-no-safe-search

(DoH Protocol) Block adult websites, gambling websites, malwares and advertisements.
Unlike other dnsforfamily DNSCrypt servers, this one does not enforces safe search. So Google, YouTube, Bing, DuckDuckGo and Yandex are completely accessible without any restriction.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of December 2020 2.7 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 3 years now.

Warning: This server is incompatible with anonymization.

Provided by: https://dnsforfamily.com

sdns://AgIAAAAAAAAADTk1LjIxNy4yMTMuOTSgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984nZG5zLWRvaC1uby1zYWZlLXNlYXJjaC5kbnNmb3JmYW1pbHkuY29tCi9kbnMtcXVlcnk


## dnsforfamily-no-safe-search

(DNSCrypt Protocol) Block adult websites, gambling websites, malwares and advertisements.
Unlike other dnsforfamily DNSCrypt servers, this one does not enforces safe search. So Google, YouTube, Bing, DuckDuckGo and Yandex are completely accessible without any restriction.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of December 2020 2.7 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 3 years now.

Warning: This server is incompatible with anonymization.

Provided by: https://dnsforfamily.com

sdns://AQIAAAAAAAAADzEzNS4xODEuMTkzLjIyMiBHFKrWl_Swzwd8Mcwa8ZhdLGFgC94SpKo_g57e_49DthBkbnNmb3JmYW1pbHkuY29t


## dnsforfamily-v6

(DNSCrypt Protocol) Block adult websites, gambling websites, malwares and advertisements.
It also enforces safe search in: Google, YouTube, Bing, DuckDuckGo and Yandex.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.
As of December 2020 2.7 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 3 years now.

Provided by: https://dnsforfamily.com

sdns://AQIAAAAAAAAAF1syYTAxOjRmODoxYzE3OjRkZjg6OjFdIGN4CrSY4fb2hK8voFJL3GKiM7xQNwkKGH4b0k7LmMPxEGRuc2ZvcmZhbWlseS5jb20


## dnswarden-asia-adultfilter-dcv4

Hosted in Singapore. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AQMAAAAAAAAAFDIwNy4xNDguMTIwLjI0NDo1NTU1IKaotzxLPX3tRvpH4lDhbTo1cHCL4X-ZhW_Ji6jU8LwyJTIuZG5zY3J5cHQtY2VydC5kbnN3YXJkZW4tYWR1bHRmaWx0ZXI


## dnswarden-asia-adultfilter-dcv6

Hosted in Singapore. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AQMAAAAAAAAALVsyMDAxOjE5ZjA6NDQwMDo0ZGUyOjU0MDA6M2ZmOmZlYTk6ZDQxOF06NTU1NSCmqLc8Sz197Ub6R-JQ4W06NXBwi-F_mYVvyYuo1PC8MiUyLmRuc2NyeXB0LWNlcnQuZG5zd2FyZGVuLWFkdWx0ZmlsdGVy


## dnswarden-asia-adultfilter-dohv4

Hosted in Singapore. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AgMAAAAAAAAADzIwNy4xNDguMTIwLjI0NCBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhZkb2guYXNpYS5kbnN3YXJkZW4uY29tDC9hZHVsdGZpbHRlcg


## dnswarden-asia-adultfilter-dohv6

Hosted in Singapore. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AgMAAAAAAAAAKFsyMDAxOjE5ZjA6NDQwMDo0ZGUyOjU0MDA6M2ZmOmZlYTk6ZDQxOF0gRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984WZG9oLmFzaWEuZG5zd2FyZGVuLmNvbQwvYWR1bHRmaWx0ZXI


## dnswarden-eu-adultfilter-dcv4

Hosted in Germany. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AQMAAAAAAAAAEDQ1Ljc2Ljg4LjIwOjU1NTUg1s4Ar-3awN0OmfAQzlZywvR2ZGVMg0aeNdwrLHspdpMlMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi1hZHVsdGZpbHRlcg


## dnswarden-eu-adultfilter-dcv6

Hosted in Germany. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AQMAAAAAAAAALVsyMDAxOjE5ZjA6NmMwMToyYjE3OjU0MDA6M2ZmOmZlYTk6ZDQyZl06NTU1NSDWzgCv7drA3Q6Z8BDOVnLC9HZkZUyDRp413Csseyl2kyUyLmRuc2NyeXB0LWNlcnQuZG5zd2FyZGVuLWFkdWx0ZmlsdGVy


## dnswarden-eu-adultfilter-dohv4

Hosted in Germany. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AgMAAAAAAAAACzQ1Ljc2Ljg4LjIwIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOFGRvaC5ldS5kbnN3YXJkZW4uY29tDC9hZHVsdGZpbHRlcg


## dnswarden-eu-adultfilter-dohv6

Hosted in Germany. For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AgMAAAAAAAAAKFsyMDAxOjE5ZjA6NmMwMToyYjE3OjU0MDA6M2ZmOmZlYTk6ZDQyZl0gRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984UZG9oLmV1LmRuc3dhcmRlbi5jb20ML2FkdWx0ZmlsdGVy


## dnswarden-us-adultfilter-dcv4

Hosted in USA (Dallas) . For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AQMAAAAAAAAAEzE0NC4yMDIuNjkuMTQ5OjU1NTUgc_eiadnb3wpUqznTHbI2NziLpELYc4uuDM-s3v3CsSQlMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi1hZHVsdGZpbHRlcg


## dnswarden-us-adultfilter-dcv6

Hosted in USA (Dallas) . For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AQMAAAAAAAAALFsyMDAxOjE5ZjA6NjQwMTpkNmU6NTQwMDozZmY6ZmVhOTpkNDVlXTo1NTU1IHP3omnZ298KVKs50x2yNjc4i6RC2HOLrgzPrN79wrEkJTIuZG5zY3J5cHQtY2VydC5kbnN3YXJkZW4tYWR1bHRmaWx0ZXI


## dnswarden-us-adultfilter-dohv4

Hosted in USA (Dallas) . For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AgMAAAAAAAAADjE0NC4yMDIuNjkuMTQ5IEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOFGRvaC51cy5kbnN3YXJkZW4uY29tDC9hZHVsdGZpbHRlcg


## dnswarden-us-adultfilter-dohv6

Hosted in USA (Dallas) . For more information look [here](https://github.com/bhanupratapys/dnswarden) or [here](https://dnswarden.com). Blocks adult content and enforces safe search on major search engines.

sdns://AgMAAAAAAAAAJ1syMDAxOjE5ZjA6NjQwMTpkNmU6NTQwMDozZmY6ZmVhOTpkNDVlXSBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhRkb2gudXMuZG5zd2FyZGVuLmNvbQwvYWR1bHRmaWx0ZXI


## doh-cleanbrowsing-adult

Blocks access to all adult, pornographic and explicit sites. It does
not block proxy or VPNs, nor mixed-content sites. Sites like Reddit
are allowed. Google and Bing are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AgMAAAAAAAAAAAAVZG9oLmNsZWFuYnJvd3Npbmcub3JnEi9kb2gvYWR1bHQtZmlsdGVyLw


## doh-cleanbrowsing-family

Blocks access to all adult, pornographic and explicit sites. It also
blocks proxy and VPN domains that are used to bypass the filters.
Mixed content sites (like Reddit) are also blocked. Google, Bing and
Youtube are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AgMAAAAAAAAAAAAVZG9oLmNsZWFuYnJvd3Npbmcub3JnEy9kb2gvZmFtaWx5LWZpbHRlci8


## safesurfer

Family safety focused blocklist for over 2 million adult sites, as well as phishing and malware and more.
Free to use, paid for customizing blocking for more categories+sites and viewing usage at my.safesurfer.io. Logs taken for viewing
usage, data never sold - https://safesurfer.io

sdns://AQMAAAAAAAAADzEwNC4xNTUuMjM3LjIyNSAnIH_VEgToNntINABd-f_R0wu-KpwzY55u2_iu2R1A2CAyLmRuc2NyeXB0LWNlcnQuc2FmZXN1cmZlci5jby5ueg


## sfw.scaleway-fr

Uses deep learning to block adult websites. Free, DNSSEC, no logs.
Hosted in Paris, running on a 1-XS server donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info/sfw.html

sdns://AQMAAAAAAAAADzE2My4xNzIuMTgwLjEyNSDfYnO_x1IZKotaObwMhaw_-WRF1zZE9mJygl01WPGh_x8yLmRuc2NyeXB0LWNlcnQuc2Z3LnNjYWxld2F5LWZy

