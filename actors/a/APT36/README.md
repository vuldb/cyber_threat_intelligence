# APT36 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT36](https://vuldb.com/?actor.apt36). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt36](https://vuldb.com/?actor.apt36)

## Campaigns

The following _campaigns_ are known and can be associated with APT36:

* C-Major
* Crimson RAT

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT36:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT36.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.189.137.8](https://vuldb.com/?ip.5.189.137.8) | vending.softjourn.if.ua | C-Major | High
2 | [5.189.143.225](https://vuldb.com/?ip.5.189.143.225) | - | C-Major | High
3 | [5.189.152.147](https://vuldb.com/?ip.5.189.152.147) | ccloud.armax.de | C-Major | High
4 | [5.189.167.23](https://vuldb.com/?ip.5.189.167.23) | mltx.de | C-Major | High
5 | [5.189.167.65](https://vuldb.com/?ip.5.189.167.65) | vmi437585.contaboserver.net | C-Major | High
6 | [23.254.119.11](https://vuldb.com/?ip.23.254.119.11) | - | - | High
7 | [64.188.12.126](https://vuldb.com/?ip.64.188.12.126) | 64.188.12.126.static.quadranet.com | - | High
8 | [64.188.25.205](https://vuldb.com/?ip.64.188.25.205) | 64.188.25.205.static.quadranet.com | Crimson RAT | High
9 | [64.188.25.232](https://vuldb.com/?ip.64.188.25.232) | 64.188.25.232.static.quadranet.com | - | High
10 | [75.98.175.79](https://vuldb.com/?ip.75.98.175.79) | a2s83.a2hosting.com | C-Major | High
11 | [75.119.139.169](https://vuldb.com/?ip.75.119.139.169) | server1.immacolata.com | - | High
12 | [80.240.134.51](https://vuldb.com/?ip.80.240.134.51) | - | C-Major | High
13 | ... | ... | ... | ...

There are 49 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT36_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT36. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin` | Low
3 | File | `/admin/?page=inmates/view_inmate` | High
4 | File | `/admin/?page=system_info` | High
5 | File | `/admin/?page=system_info/contact_info` | High
6 | File | `/admin/conferences/get-all-status/` | High
7 | File | `/admin/conferences/list/` | High
8 | File | `/admin/countrymanagement.php` | High
9 | File | `/admin/edit.php` | High
10 | File | `/admin/edit_admin_details.php?id=admin` | High
11 | File | `/admin/general/change-lang` | High
12 | File | `/admin/group/list/` | High
13 | File | `/admin/lab.php` | High
14 | File | `/admin/new-content` | High
15 | File | `/admin/renewaldue.php` | High
16 | File | `/admin/sign/out` | High
17 | File | `/admin/usermanagement.php` | High
18 | File | `/aqpg/users/login.php` | High
19 | File | `/artist-display.php` | High
20 | File | `/assets/php/upload.php` | High
21 | File | `/backups/` | Medium
22 | File | `/bcms/admin/?page=user/list` | High
23 | File | `/cardo/api` | Medium
24 | File | `/catcompany.php` | High
25 | File | `/CCMAdmin/serverlist.asp` | High
26 | File | `/cgi-bin/editBookmark` | High
27 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
28 | File | `/cgi-bin/nightled.cgi` | High
29 | File | `/cgi-bin/touchlist_sync.cgi` | High
30 | File | `/ci_hms/massage_room/edit/1` | High
31 | File | `/ci_hms/search` | High
32 | File | `/ci_spms/admin/category` | High
33 | File | `/ci_spms/admin/search/searching/` | High
34 | File | `/ci_ssms/index.php/orders/create` | High
35 | File | `/classes/Users.php?f=save` | High
36 | File | `/cwms/admin/?page=articles/view_article/` | High
37 | File | `/cwms/classes/Master.php?f=save_contact` | High
38 | File | `/editbrand.php` | High
39 | File | `/film-rating.php` | High
40 | File | `/front/roomtype-details.php` | High
41 | File | `/goform/RgDdns` | High
42 | File | `/goform/RgDhcp` | High
43 | File | `/goform/RGFirewallEL` | High
44 | File | `/goform/RgTime` | High
45 | File | `/goform/RgUrlBlock.asp` | High
46 | File | `/goform/wlanPrimaryNetwork` | High
47 | File | `/horde/imp/search.php` | High
48 | File | `/index.php` | Medium
49 | File | `/librarian/bookdetails.php` | High
50 | ... | ... | ...

There are 432 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.malwarebytes.com/threat-analysis/2020/03/apt36-jumps-on-the-coronavirus-bandwagon-delivers-crimson-rat/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.05.13/Transparent%20Tribe.pdf
* https://www.threatminer.org/report.php?q=indian-military-personnel-targeted-by-information-theft-campaign-cmajor.pdf&y=2016
* https://www.trendmicro.com/en_us/research/22/a/investigating-apt36-or-earth-karkaddans-attack-chain-and-malware.html
* https://www.zscaler.com/blogs/security-research/apt-36-uses-new-ttps-and-new-tools-target-indian-governmental-organizations

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
