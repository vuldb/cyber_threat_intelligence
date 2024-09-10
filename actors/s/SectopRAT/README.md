# SectopRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SectopRAT](https://vuldb.com/?actor.sectoprat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sectoprat](https://vuldb.com/?actor.sectoprat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SectopRAT:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SectopRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.57.149.77](https://vuldb.com/?ip.2.57.149.77) | - | - | High
2 | [2.57.149.235](https://vuldb.com/?ip.2.57.149.235) | - | - | High
3 | [5.42.67.10](https://vuldb.com/?ip.5.42.67.10) | - | - | High
4 | [5.75.147.135](https://vuldb.com/?ip.5.75.147.135) | static.135.147.75.5.clients.your-server.de | - | High
5 | [5.75.149.1](https://vuldb.com/?ip.5.75.149.1) | static.1.149.75.5.clients.your-server.de | - | High
6 | [5.75.153.165](https://vuldb.com/?ip.5.75.153.165) | s92.vorarlberghosting.com | - | High
7 | [34.27.150.38](https://vuldb.com/?ip.34.27.150.38) | 38.150.27.34.bc.googleusercontent.com | - | Medium
8 | [34.27.176.144](https://vuldb.com/?ip.34.27.176.144) | 144.176.27.34.bc.googleusercontent.com | - | Medium
9 | [34.89.247.212](https://vuldb.com/?ip.34.89.247.212) | 212.247.89.34.bc.googleusercontent.com | - | Medium
10 | [34.91.185.62](https://vuldb.com/?ip.34.91.185.62) | 62.185.91.34.bc.googleusercontent.com | - | Medium
11 | [34.107.35.186](https://vuldb.com/?ip.34.107.35.186) | 186.35.107.34.bc.googleusercontent.com | - | Medium
12 | [34.107.84.7](https://vuldb.com/?ip.34.107.84.7) | 7.84.107.34.bc.googleusercontent.com | - | Medium
13 | [34.141.16.89](https://vuldb.com/?ip.34.141.16.89) | 89.16.141.34.bc.googleusercontent.com | - | Medium
14 | [34.141.92.1](https://vuldb.com/?ip.34.141.92.1) | 1.92.141.34.bc.googleusercontent.com | - | Medium
15 | [34.141.167.33](https://vuldb.com/?ip.34.141.167.33) | 33.167.141.34.bc.googleusercontent.com | - | Medium
16 | [34.141.198.105](https://vuldb.com/?ip.34.141.198.105) | 105.198.141.34.bc.googleusercontent.com | - | Medium
17 | [34.142.80.219](https://vuldb.com/?ip.34.142.80.219) | 219.80.142.34.bc.googleusercontent.com | - | Medium
18 | [34.159.68.86](https://vuldb.com/?ip.34.159.68.86) | 86.68.159.34.bc.googleusercontent.com | - | Medium
19 | [34.159.180.55](https://vuldb.com/?ip.34.159.180.55) | 55.180.159.34.bc.googleusercontent.com | - | Medium
20 | ... | ... | ... | ...

There are 74 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SectopRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SectopRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.cdrdao` | High
2 | File | `.imwheelrc` | Medium
3 | File | `.jpilot` | Low
4 | File | `.plan` | Low
5 | File | `.tin` | Low
6 | File | `/+CSCOE+/logon.html` | High
7 | File | `//proc/kcore` | Medium
8 | File | `/admin/emp-profile-avatar.php` | High
9 | File | `/admin/searchview.php` | High
10 | File | `/api/v1/bait/set` | High
11 | File | `/asms/classes/Master.php?f=delete_img` | High
12 | File | `/bolt/editcontent/showcases` | High
13 | File | `/cgi-bin/` | Medium
14 | File | `/cgi-bin/system_mgr.cgi` | High
15 | File | `/configs/application.ini` | High
16 | File | `/coreframe/app/pay/admin/index.php` | High
17 | File | `/forum/away.php` | High
18 | File | `/healthcare/Admin/consulting_detail.php` | High
19 | File | `/librarian/bookdetails.php` | High
20 | File | `/lists/index.php` | High
21 | File | `/opac/Actions.php?a=login` | High
22 | File | `/protocol/iscuser/uploadiscuser.php` | High
23 | File | `/public/launchNewWindow.jsp` | High
24 | File | `/public/login.htm` | High
25 | File | `/resume_upload.php` | High
26 | File | `/rpc/membership/setProfile` | High
27 | File | `/simple_chat_bot/admin/?page=responses/manage_response` | High
28 | File | `/spacecom/login.php` | High
29 | File | `/spip.php` | Medium
30 | File | `/staff/bookdetails.php` | High
31 | File | `/tmp` | Low
32 | File | `/tour/admin/file.php` | High
33 | File | `/usr/bin/sonia` | High
34 | File | `/usr/ucb/mail` | High
35 | File | `/var/spool/fax/outgoing/.last_run` | High
36 | File | `/_next` | Low
37 | File | `5.php` | Low
38 | File | `123flashchat.php` | High
39 | File | `about.php` | Medium
40 | File | `account.php` | Medium
41 | File | `adclick.php` | Medium
42 | File | `add-phlebotomist.php` | High
43 | File | `add.php` | Low
44 | File | `addtomylist.asp` | High
45 | File | `admin.color.php` | High
46 | File | `admin/addons/archive/archive.php` | High
47 | File | `admin/profile_settings_net.html` | High
48 | File | `admincp/auth/secure.php` | High
49 | File | `adminer.php` | Medium
50 | File | `Administrator/add_pictures.php` | High
51 | File | `advsearch.php` | High
52 | File | `af_netlink.c` | Medium
53 | File | `ajax_officebuilding.php` | High
54 | ... | ... | ...

There are 468 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/20221a9d-bcf3-4ec4-bebd-6fdd18e783e5
* https://community.blueliv.com/#!/s/602f934182df413eaf345e6a
* https://de.darktrace.com/blog/not-your-average-rodent-darktraces-mitigation-of-the-sectop-remote-access-trojan-rat
* https://search.censys.io/hosts/45.141.87.50
* https://search.censys.io/hosts/94.181.229.249
* https://search.censys.io/hosts/194.26.29.112
* https://threatfox.abuse.ch
* https://twitter.com/AnFam17/status/1658666291308163072
* https://urlhaus.abuse.ch/url/2859573/
* https://www.malwarebytes.com/blog/threat-intelligence/2024/04/bing-ad-for-nordvpn-leads-to-sectoprat
* https://www.virustotal.com/gui/file/7dec8701bb5db7497c62ff78db7e5dd05b75a7b4e226d99992fcad3ceeab4ed6

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
