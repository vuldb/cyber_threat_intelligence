# Gafgyt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Gafgyt](https://vuldb.com/?actor.gafgyt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gafgyt](https://vuldb.com/?actor.gafgyt)

## Campaigns

The following _campaigns_ are known and can be associated with Gafgyt:

* CVE-2014-8361 / CVE-2017-17215 / CVE-2017-18368
* CVE-2017-5638 / CVE-2018-9866
* DDoS Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gafgyt:

* [CN](https://vuldb.com/?country.cn)
* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gafgyt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.180.82.194](https://vuldb.com/?ip.5.180.82.194) | - | - | High
2 | [23.137.100.69](https://vuldb.com/?ip.23.137.100.69) | - | - | High
3 | [31.58.58.113](https://vuldb.com/?ip.31.58.58.113) | - | - | High
4 | [38.54.17.161](https://vuldb.com/?ip.38.54.17.161) | - | - | High
5 | [38.60.249.97](https://vuldb.com/?ip.38.60.249.97) | - | - | High
6 | [45.13.225.203](https://vuldb.com/?ip.45.13.225.203) | 203.225.13.45.in-addr.arpa | - | High
7 | [45.125.33.82](https://vuldb.com/?ip.45.125.33.82) | pcuwoczzmhkp.universenumber.com | - | High
8 | [45.135.194.45](https://vuldb.com/?ip.45.135.194.45) | - | - | High
9 | [45.143.166.71](https://vuldb.com/?ip.45.143.166.71) | - | - | High
10 | [45.170.248.16](https://vuldb.com/?ip.45.170.248.16) | - | - | High
11 | [46.29.235.158](https://vuldb.com/?ip.46.29.235.158) | - | - | High
12 | [46.249.32.109](https://vuldb.com/?ip.46.249.32.109) | reverse.hostingbb.com | DDoS Ukraine | High
13 | [62.60.232.26](https://vuldb.com/?ip.62.60.232.26) | 55748.ip-ptr.tech | - | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Gafgyt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gafgyt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.git/` | Low
2 | File | `.travis.yml` | Medium
3 | File | `/+CSCOE+/logon.html` | High
4 | File | `/?page=reports` | High
5 | File | `/add-normal-ticket.php` | High
6 | File | `/adfs/ls` | Medium
7 | File | `/admin.php?p=/Area/index#tab=t2` | High
8 | File | `/admin/add_ikev2.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/category_save.php` | High
11 | File | `/admin/contactus.php` | High
12 | File | `/admin/content/editor` | High
13 | File | `/admin/fetch_product_details.php` | High
14 | File | `/admin/general/change-lang` | High
15 | File | `/admin/index2.html` | High
16 | File | `/admin/inquiries/view_details.php` | High
17 | File | `/admin/list_ipAddressPolicy.php` | High
18 | File | `/admin/login_process.php` | High
19 | File | `/admin/manage_model.php` | High
20 | File | `/admin/manage_user.php` | High
21 | File | `/admin/search-vehicle.php` | High
22 | File | `/admin/subject.php` | High
23 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
24 | File | `/admin/tag.php` | High
25 | File | `/admin/twitter.php` | High
26 | File | `/admin_class.php` | High
27 | File | `/api/esps` | Medium
28 | File | `/api/v1/toolbox/device/update/swap` | High
29 | File | `/api/v2/events` | High
30 | File | `/api/v2/maps` | Medium
31 | File | `/app/zentao/module/repo/model.php` | High
32 | File | `/auth_files/photo/` | High
33 | File | `/bin/httpd` | Medium
34 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
35 | File | `/catalog/all-products` | High
36 | File | `/cgi-bin/cstecgi.cgi` | High
37 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
38 | File | `/cgi-bin/ExportSettings.sh` | High
39 | File | `/cgi-bin/hd_config.cgi` | High
40 | File | `/classes/Master.php?f=delete_record` | High
41 | File | `/classes/Master.php?f=log_employee` | High
42 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
43 | File | `/com/esafenet/servlet/policy/HookService.java` | High
44 | File | `/dev/kmem` | Medium
45 | File | `/display/map` | Medium
46 | ... | ... | ...

There are 402 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/
* https://blog.netlab.360.com/wo-men-kan-dao-de-wu-ke-lan-bei-ddosgong-ji-xi-jie/
* https://unit42.paloaltonetworks.com/home-small-office-wireless-routers-exploited-to-attack-gaming-servers/
* https://unit42.paloaltonetworks.com/unit42-multi-exploit-iotlinux-botnets-mirai-gafgyt-target-apache-struts-sonicwall/
* https://urlhaus.abuse.ch/url/3517821/
* https://urlhaus.abuse.ch/url/3518360/
* https://urlhaus.abuse.ch/url/3519621/
* https://urlhaus.abuse.ch/url/3519683/
* https://urlhaus.abuse.ch/url/3520490/
* https://urlhaus.abuse.ch/url/3520969/
* https://urlhaus.abuse.ch/url/3520977/
* https://urlhaus.abuse.ch/url/3521199/
* https://urlhaus.abuse.ch/url/3521304/
* https://urlhaus.abuse.ch/url/3521962/
* https://urlhaus.abuse.ch/url/3522180/
* https://urlhaus.abuse.ch/url/3522744/
* https://urlhaus.abuse.ch/url/3524054/
* https://urlhaus.abuse.ch/url/3524073/
* https://urlhaus.abuse.ch/url/3524858/
* https://urlhaus.abuse.ch/url/3525256/
* https://urlhaus.abuse.ch/url/3526664/
* https://urlhaus.abuse.ch/url/3526669/
* https://urlhaus.abuse.ch/url/3526670/
* https://urlhaus.abuse.ch/url/3526891/
* https://urlhaus.abuse.ch/url/3527900/
* https://urlhaus.abuse.ch/url/3528473/
* https://urlhaus.abuse.ch/url/3528904/
* https://urlhaus.abuse.ch/url/3529215/
* https://urlhaus.abuse.ch/url/3530757/
* https://urlhaus.abuse.ch/url/3531085/
* https://urlhaus.abuse.ch/url/3531246/
* https://urlhaus.abuse.ch/url/3533480/
* https://urlhaus.abuse.ch/url/3533925/
* https://urlhaus.abuse.ch/url/3534643/
* https://urlhaus.abuse.ch/url/3536492/
* https://urlhaus.abuse.ch/url/3538927/
* https://urlhaus.abuse.ch/url/3538982/
* https://urlhaus.abuse.ch/url/3540224/
* https://urlhaus.abuse.ch/url/3540367/
* https://urlhaus.abuse.ch/url/3542891/
* https://urlhaus.abuse.ch/url/3543222/
* https://urlhaus.abuse.ch/url/3543840/
* https://urlhaus.abuse.ch/url/3544838/
* https://urlhaus.abuse.ch/url/3544877/
* https://urlhaus.abuse.ch/url/3545062/
* https://urlhaus.abuse.ch/url/3545840/
* https://urlhaus.abuse.ch/url/3545910/
* https://urlhaus.abuse.ch/url/3545912/
* https://urlhaus.abuse.ch/url/3545913/
* https://urlhaus.abuse.ch/url/3545915/
* https://urlhaus.abuse.ch/url/3545943/
* https://urlhaus.abuse.ch/url/3546227/
* https://urlhaus.abuse.ch/url/3546244/
* https://urlhaus.abuse.ch/url/3546571/
* https://urlhaus.abuse.ch/url/3546687/
* https://urlhaus.abuse.ch/url/3546769/
* https://urlhaus.abuse.ch/url/3549428/
* https://urlhaus.abuse.ch/url/3550597/
* https://urlhaus.abuse.ch/url/3550993/
* https://www.aquasec.com/blog/gafgyt-malware-variant-exploits-gpu-power-and-cloud-native-environments/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
