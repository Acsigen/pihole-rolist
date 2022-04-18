# pihole-rolist

Romanian host list for Pi-Hole.

## Info

- The `hosts` file is a merged collection of hosts from zoso.ro and adblock.ro uBlock lists.
- The `deceptive-content` file blocks sites that are considered to spread fake news or have spam like content / click bait news titles.
  - **April 2022 Update**: Added [DNSC](https://dnsc.ro/vezi/document/situatie-site-uri-cu-activitate-in-contextul-crizei-ucraina-rusia-plus-adrese-ip-specifice-utilizate-in-atacuri-malware) banned domains related to Russian - Ucranian crisis

## How to use it

For the advertising domains paste the following link into your Pi-Hole adlists: `https://raw.githubusercontent.com/Acsigen/pihole-rolist/main/hosts`

For the deceptive content domains paste the following link into your Pi-Hole adlists: `https://raw.githubusercontent.com/Acsigen/pihole-rolist/main/deceptive-content`
