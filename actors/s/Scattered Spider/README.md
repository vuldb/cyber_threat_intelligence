# Scattered Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Scattered Spider](https://vuldb.com/?actor.scattered_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.scattered_spider](https://vuldb.com/?actor.scattered_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Scattered Spider:

* RansomHub

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Scattered Spider:

* [RO](https://vuldb.com/?country.ro)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Scattered Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.182.37.59](https://vuldb.com/?ip.5.182.37.59) | vm2004101.stark-industries.solutions | - | High
2 | [20.37.139.187](https://vuldb.com/?ip.20.37.139.187) | - | RansomHub | High
3 | [23.106.248.251](https://vuldb.com/?ip.23.106.248.251) | - | - | High
4 | [31.222.238.70](https://vuldb.com/?ip.31.222.238.70) | peter1990adams.example.com | - | High
5 | [35.175.153.217](https://vuldb.com/?ip.35.175.153.217) | ec2-35-175-153-217.compute-1.amazonaws.com | - | Medium
6 | [37.19.200.142](https://vuldb.com/?ip.37.19.200.142) | unn-37-19-200-142.datapacket.com | - | High
7 | [37.19.200.151](https://vuldb.com/?ip.37.19.200.151) | unn-37-19-200-151.datapacket.com | - | High
8 | [37.19.200.155](https://vuldb.com/?ip.37.19.200.155) | unn-37-19-200-155.datapacket.com | - | High
9 | [38.244.145.85](https://vuldb.com/?ip.38.244.145.85) | - | RansomHub | High
10 | [45.32.64.247](https://vuldb.com/?ip.45.32.64.247) | 45.32.64.247.vultrusercontent.com | - | Medium
11 | [45.32.66.91](https://vuldb.com/?ip.45.32.66.91) | 45.32.66.91.vultrusercontent.com | - | Medium
12 | [45.32.84.65](https://vuldb.com/?ip.45.32.84.65) | 45.32.84.65.vultrusercontent.com | - | Medium
13 | [45.32.221.250](https://vuldb.com/?ip.45.32.221.250) | 45.32.221.250.vultrusercontent.com | - | Medium
14 | [45.63.52.43](https://vuldb.com/?ip.45.63.52.43) | 45.63.52.43.vultrusercontent.com | - | Medium
15 | [45.63.53.99](https://vuldb.com/?ip.45.63.53.99) | 45.63.53.99.vultrusercontent.com | - | Medium
16 | [45.63.54.8](https://vuldb.com/?ip.45.63.54.8) | 45.63.54.8.vultrusercontent.com | - | Medium
17 | [45.76.65.42](https://vuldb.com/?ip.45.76.65.42) | 45.76.65.42.vultrusercontent.com | - | Medium
18 | [45.76.172.113](https://vuldb.com/?ip.45.76.172.113) | 45.76.172.113.vultrusercontent.com | - | Medium
19 | [45.77.120.140](https://vuldb.com/?ip.45.77.120.140) | 45.77.120.140.vultrusercontent.com | - | Medium
20 | [45.86.200.81](https://vuldb.com/?ip.45.86.200.81) | - | - | High
21 | [45.91.21.61](https://vuldb.com/?ip.45.91.21.61) | - | - | High
22 | [45.132.227.211](https://vuldb.com/?ip.45.132.227.211) | - | - | High
23 | [45.132.227.213](https://vuldb.com/?ip.45.132.227.213) | - | - | High
24 | [45.134.140.171](https://vuldb.com/?ip.45.134.140.171) | unn-45-134-140-171.datapacket.com | - | High
25 | [45.134.140.177](https://vuldb.com/?ip.45.134.140.177) | unn-45-134-140-177.datapacket.com | - | High
26 | [45.156.85.140](https://vuldb.com/?ip.45.156.85.140) | - | - | High
27 | [51.89.138.221](https://vuldb.com/?ip.51.89.138.221) | vps-9d9720f6.vps.ovh.net | - | High
28 | [51.210.161.12](https://vuldb.com/?ip.51.210.161.12) | - | - | High
29 | ... | ... | ... | ...

There are 113 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Scattered Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Scattered Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=user` | Medium
2 | File | `/admin/bookings/view_booking.php` | High
3 | File | `/admin/delete_members.php` | High
4 | File | `/admin/index.php` | High
5 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
6 | File | `/admin/login.php` | High
7 | File | `/admin/manage-normal-ticket.php` | High
8 | File | `/admin/service_requests/manage_inventory.php` | High
9 | File | `/admin/updateorder.php` | High
10 | File | `/admin/userbuilderdelete.php` | High
11 | File | `/book_list.php` | High
12 | File | `/classes/Master.php?f=save_package` | High
13 | File | `/contact/store` | High
14 | File | `/core/tools/customblock.php` | High
15 | File | `/CPE` | Low
16 | File | `/currentsetting.htm` | High
17 | File | `/debuginfo.htm` | High
18 | File | `/delete_post.php` | High
19 | File | `/edit-student.php` | High
20 | File | `/editcus.php` | Medium
21 | File | `/Employer/ManageWalkin.php` | High
22 | File | `/forgot.php` | Medium
23 | File | `/forum/away.php` | High
24 | File | `/friends` | Medium
25 | File | `/geoserver/gwc/rest.html` | High
26 | File | `/goform/aspForm` | High
27 | File | `/goform/formLanguageChange` | High
28 | File | `/goform/SetFirewallCfg` | High
29 | File | `/goform/setMacFilter` | High
30 | File | `/goform/set_manpwd` | High
31 | File | `/goform/wirelessRestart` | High
32 | File | `/investigation/delete/` | High
33 | File | `/labvantage/rc?command=page&sdcid=LV_ReagentLot` | High
34 | File | `/log/wifi.mac` | High
35 | File | `/login` | Low
36 | File | `/market/chatuser.php` | High
37 | File | `/messageboard/view.php` | High
38 | File | `/modules/projects/vw_files.php` | High
39 | File | `/monitor/cache/getnames` | High
40 | File | `/openNDS/src/auth.c` | High
41 | File | `/pages/account_add.php` | High
42 | File | `/panel/edit_plan.php` | High
43 | File | `/pfcpiface/pfcpiface/messages_session.go` | High
44 | ... | ... | ...

There are 381 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.sekoia.io/scattered-spider-laying-new-eggs/
* https://darktrace.com/blog/ransomhub-revisited-new-front-runner-in-the-ransomware-as-a-service-marketplace
* https://www.reliaquest.com/blog/scattered-spider-attack-analysis-account-compromise/
* https://www.reliaquest.com/blog/scattered-spider-x-ransomhub-a-new-partnership/
* https://www.trellix.com/en-us/about/newsroom/stories/research/scattered-spider-the-modus-operandi.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
