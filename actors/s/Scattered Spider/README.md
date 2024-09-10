# Scattered Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Scattered Spider](https://vuldb.com/?actor.scattered_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.scattered_spider](https://vuldb.com/?actor.scattered_spider)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Scattered Spider:

* [RO](https://vuldb.com/?country.ro)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Scattered Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.182.37.59](https://vuldb.com/?ip.5.182.37.59) | vm2004101.stark-industries.solutions | - | High
2 | [23.106.248.251](https://vuldb.com/?ip.23.106.248.251) | - | - | High
3 | [31.222.238.70](https://vuldb.com/?ip.31.222.238.70) | peter1990adams.example.com | - | High
4 | [35.175.153.217](https://vuldb.com/?ip.35.175.153.217) | ec2-35-175-153-217.compute-1.amazonaws.com | - | Medium
5 | [37.19.200.142](https://vuldb.com/?ip.37.19.200.142) | unn-37-19-200-142.datapacket.com | - | High
6 | [37.19.200.151](https://vuldb.com/?ip.37.19.200.151) | unn-37-19-200-151.datapacket.com | - | High
7 | [37.19.200.155](https://vuldb.com/?ip.37.19.200.155) | unn-37-19-200-155.datapacket.com | - | High
8 | [45.32.64.247](https://vuldb.com/?ip.45.32.64.247) | 45.32.64.247.vultrusercontent.com | - | Medium
9 | [45.32.66.91](https://vuldb.com/?ip.45.32.66.91) | 45.32.66.91.vultrusercontent.com | - | Medium
10 | [45.32.84.65](https://vuldb.com/?ip.45.32.84.65) | 45.32.84.65.vultrusercontent.com | - | Medium
11 | [45.32.221.250](https://vuldb.com/?ip.45.32.221.250) | 45.32.221.250.vultrusercontent.com | - | Medium
12 | [45.63.52.43](https://vuldb.com/?ip.45.63.52.43) | 45.63.52.43.vultrusercontent.com | - | Medium
13 | [45.63.53.99](https://vuldb.com/?ip.45.63.53.99) | 45.63.53.99.vultrusercontent.com | - | Medium
14 | [45.63.54.8](https://vuldb.com/?ip.45.63.54.8) | 45.63.54.8.vultrusercontent.com | - | Medium
15 | [45.76.65.42](https://vuldb.com/?ip.45.76.65.42) | 45.76.65.42.vultrusercontent.com | - | Medium
16 | [45.76.172.113](https://vuldb.com/?ip.45.76.172.113) | 45.76.172.113.vultrusercontent.com | - | Medium
17 | [45.77.120.140](https://vuldb.com/?ip.45.77.120.140) | 45.77.120.140.vultrusercontent.com | - | Medium
18 | [45.86.200.81](https://vuldb.com/?ip.45.86.200.81) | - | - | High
19 | [45.91.21.61](https://vuldb.com/?ip.45.91.21.61) | - | - | High
20 | [45.132.227.211](https://vuldb.com/?ip.45.132.227.211) | - | - | High
21 | [45.132.227.213](https://vuldb.com/?ip.45.132.227.213) | - | - | High
22 | [45.134.140.171](https://vuldb.com/?ip.45.134.140.171) | unn-45-134-140-171.datapacket.com | - | High
23 | [45.134.140.177](https://vuldb.com/?ip.45.134.140.177) | unn-45-134-140-177.datapacket.com | - | High
24 | [45.156.85.140](https://vuldb.com/?ip.45.156.85.140) | - | - | High
25 | [51.89.138.221](https://vuldb.com/?ip.51.89.138.221) | vps-9d9720f6.vps.ovh.net | - | High
26 | [51.210.161.12](https://vuldb.com/?ip.51.210.161.12) | - | - | High
27 | [62.182.98.170](https://vuldb.com/?ip.62.182.98.170) | - | - | High
28 | ... | ... | ... | ...

There are 110 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Scattered Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-40 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Scattered Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/action/import_wireguard_cert_file/` | High
3 | File | `/admin/ajax.php` | High
4 | File | `/admin/bookings/view_booking.php` | High
5 | File | `/admin/index.php` | High
6 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
7 | File | `/admin/problem_judge.php` | High
8 | File | `/admin/service_requests/manage_inventory.php` | High
9 | File | `/api/v1/attack` | High
10 | File | `/api/v1/bait/set` | High
11 | File | `/app/options.py` | High
12 | File | `/appinfo/save` | High
13 | File | `/buspassms/download-pass.php` | High
14 | File | `/cgi-bin/login.cgi` | High
15 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
16 | File | `/classes/Master.php?f=delete_appointment` | High
17 | File | `/config/getuser` | High
18 | File | `/contact/store` | High
19 | File | `/CPE` | Low
20 | File | `/dashboard/settings` | High
21 | File | `/Default/Bd` | Medium
22 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
23 | File | `/FormLogin` | Medium
24 | File | `/forum/away.php` | High
25 | File | `/friends` | Medium
26 | File | `/getcfg.php` | Medium
27 | File | `/gfxpoly/stroke.c` | High
28 | File | `/goform/form2Wan.cgi` | High
29 | File | `/goform/setMacFilter` | High
30 | File | `/guest/s/default/` | High
31 | File | `/h/compose` | Medium
32 | File | `/index.php?module=entities/listing_types&entities_id=24` | High
33 | File | `/index/jobfairol/show/` | High
34 | File | `/investigation/delete/` | High
35 | File | `/leave_system/classes/Master.php?f=delete_department` | High
36 | File | `/leave_system/classes/Users.php?f=save` | High
37 | File | `/messageboard/view.php` | High
38 | File | `/mgmt/tm/util/bash` | High
39 | File | `/mhds/clinic/view_details.php` | High
40 | File | `/modules/projects/vw_files.php` | High
41 | File | `/MTFWU` | Low
42 | File | `/nova/bin/console` | High
43 | File | `/ofrs/admin/?page=teams/manage_team` | High
44 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
45 | File | `/panel/fields/add` | High
46 | File | `/patient/settings.php` | High
47 | File | `/protocol/iscdevicestatus/deleteonlineuser.php` | High
48 | File | `/REBOOTSYSTEM` | High
49 | File | `/sbin/acos_service` | High
50 | File | `/school/model/get_teacher.php` | High
51 | File | `/scripts/unlock_tasks.php` | High
52 | File | `/servlet/webacc` | High
53 | File | `/simple_chat_bot/admin/?page=responses/view_response` | High
54 | File | `/sscdms/classes/Users.php?f=save` | High
55 | File | `/textpattern/index.php` | High
56 | File | `/uncpath/` | Medium
57 | File | `/uploadimage` | Medium
58 | File | `/usr/bin/at` | Medium
59 | File | `/usr/bin/pkexec` | High
60 | ... | ... | ...

There are 525 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.sekoia.io/scattered-spider-laying-new-eggs/
* https://www.reliaquest.com/blog/scattered-spider-attack-analysis-account-compromise/
* https://www.trellix.com/en-us/about/newsroom/stories/research/scattered-spider-the-modus-operandi.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
