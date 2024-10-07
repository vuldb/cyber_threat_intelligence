# Medusa - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Medusa](https://vuldb.com/?actor.medusa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusa](https://vuldb.com/?actor.medusa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Medusa:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Medusa.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.78.61](https://vuldb.com/?ip.5.42.78.61) | - | - | High
2 | [5.61.49.177](https://vuldb.com/?ip.5.61.49.177) | - | - | High
3 | [5.182.87.27](https://vuldb.com/?ip.5.182.87.27) | - | - | High
4 | [8.217.23.144](https://vuldb.com/?ip.8.217.23.144) | - | - | High
5 | [20.0.25.177](https://vuldb.com/?ip.20.0.25.177) | - | - | High
6 | [45.15.157.16](https://vuldb.com/?ip.45.15.157.16) | scientific-group.aeza.network | - | High
7 | [45.61.185.34](https://vuldb.com/?ip.45.61.185.34) | - | - | High
8 | [45.145.167.117](https://vuldb.com/?ip.45.145.167.117) | hms16304.hostmyservers.me | - | High
9 | [45.150.65.121](https://vuldb.com/?ip.45.150.65.121) | vm1757649.stark-industries.solutions | - | High
10 | [64.52.80.13](https://vuldb.com/?ip.64.52.80.13) | - | - | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Medusa_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Medusa. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/addnews.html` | High
2 | File | `/admin` | Low
3 | File | `/admin.php/news/admin/lists/zhuan` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/admin/app/product.php` | High
6 | File | `/admin/bookings/view_details.php` | High
7 | File | `/admin/delete_user.php` | High
8 | File | `/admin/edit.php` | High
9 | File | `/admin/edit_area.php` | High
10 | File | `/admin/index.php` | High
11 | File | `/admin/index2.html` | High
12 | File | `/admin/inquiries/view_inquiry.php` | High
13 | File | `/admin/maintenance/view_designation.php` | High
14 | File | `/admin/normal-bwdates-reports-details.php` | High
15 | File | `/admin/pages/list` | High
16 | File | `/admin/reports.php` | High
17 | File | `/admin/sales/view_details.php` | High
18 | File | `/admin_class.php` | High
19 | File | `/alphaware/summary.php` | High
20 | File | `/api/baskets/{name}` | High
21 | File | `/api/dept` | Medium
22 | File | `/api/swaggerui/static` | High
23 | File | `/App_Resource/UEditor/server/upload.aspx` | High
24 | File | `/cas/logout` | Medium
25 | File | `/cgi-bin/cstecgi.cgi` | High
26 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
27 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
28 | File | `/cgi-bin/login_action.cgi` | High
29 | File | `/cgi-bin/R19.9/easy1350.pl` | High
30 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
31 | File | `/cgi-bin/tosei_kikai.php` | High
32 | File | `/classes/Master.php` | High
33 | File | `/classes/Master.php?f=delete_category` | High
34 | File | `/collection/all` | High
35 | File | `/common/info.cgi` | High
36 | File | `/cupseasylive/countrymodify.php` | High
37 | File | `/cupseasylive/taxstructurelist.php` | High
38 | File | `/dcim/rack/` | Medium
39 | File | `/EditEventTypes.php` | High
40 | File | `/endpoint/add-user.php` | High
41 | File | `/endpoint/delete-expense.php` | High
42 | File | `/endpoint/update-bookmark.php` | High
43 | File | `/etc/groups` | Medium
44 | File | `/etc/passwd` | Medium
45 | File | `/file/upload/1` | High
46 | File | `/filex/read-raw` | High
47 | File | `/forum/away.php` | High
48 | File | `/general/system/interface/theme_set/save_image.php` | High
49 | File | `/goform/SetClientState` | High
50 | File | `/goform/SetDDNSCfg` | High
51 | File | `/goform/SysToolChangePwd` | High
52 | ... | ... | ...

There are 449 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/new-medusa-botnet-emerging-via-mirai-botnet-targeting-linux-users/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=5.42.78.61
* https://tracker.viriback.com/index.php?q=5.61.49.177
* https://tracker.viriback.com/index.php?q=45.15.157.16
* https://tracker.viriback.com/index.php?q=64.52.80.13
* https://tracker.viriback.com/index.php?q=77.105.146.254
* https://tracker.viriback.com/index.php?q=77.105.147.1
* https://tracker.viriback.com/index.php?q=77.105.147.136
* https://tracker.viriback.com/index.php?q=79.137.199.199
* https://tracker.viriback.com/index.php?q=79.137.202.24
* https://tracker.viriback.com/index.php?q=79.137.207.226
* https://tracker.viriback.com/index.php?q=85.192.63.65
* https://tracker.viriback.com/index.php?q=89.185.85.34
* https://tracker.viriback.com/index.php?q=89.185.85.132
* https://tracker.viriback.com/index.php?q=89.208.103.72
* https://tracker.viriback.com/index.php?q=89.208.107.158
* https://tracker.viriback.com/index.php?q=95.181.173.8
* https://tracker.viriback.com/index.php?q=95.181.173.233
* https://tracker.viriback.com/index.php?q=95.181.173.235
* https://tracker.viriback.com/index.php?q=146.70.161.13
* https://tracker.viriback.com/index.php?q=162.33.179.114
* https://tracker.viriback.com/index.php?q=185.46.46.133
* https://tracker.viriback.com/index.php?q=185.106.94.31
* https://tracker.viriback.com/index.php?q=185.112.83.36
* https://tracker.viriback.com/index.php?q=193.233.133.81
* https://tracker.viriback.com/index.php?q=193.233.133.97
* https://tracker.viriback.com/index.php?q=193.233.133.153
* https://tracker.viriback.com/index.php?q=193.233.133.198
* https://tracker.viriback.com/index.php?q=193.233.133.243
* https://tracker.viriback.com/index.php?q=212.113.116.56
* https://twitter.com/Jane_0sint/status/1670048531665518592
* https://www.bitdefender.com/blog/businessinsights/medusa-ransomware-a-growing-threat-with-a-bold-online-presence/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
