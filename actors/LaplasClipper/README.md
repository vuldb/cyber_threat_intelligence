# LaplasClipper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LaplasClipper](https://vuldb.com/?actor.laplasclipper). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.laplasclipper](https://vuldb.com/?actor.laplasclipper)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LaplasClipper:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LaplasClipper.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.62.241](https://vuldb.com/?ip.5.61.62.241) | - | - | High
2 | [45.84.121.44](https://vuldb.com/?ip.45.84.121.44) | - | - | High
3 | [45.159.188.125](https://vuldb.com/?ip.45.159.188.125) | coinreborn24.com | - | High
4 | [45.159.189.105](https://vuldb.com/?ip.45.159.189.105) | . | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LaplasClipper_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LaplasClipper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/delete_user.php` | High
7 | File | `/admin/doctors.php` | High
8 | File | `/admin/user/manage_user.php` | High
9 | File | `/alphaware/summary.php` | High
10 | File | `/api/` | Low
11 | File | `/api/admin/store/product/list` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/stl/actions/search` | High
14 | File | `/api/sys/login` | High
15 | File | `/api/sys/set_passwd` | High
16 | File | `/api/trackedEntityInstances` | High
17 | File | `/api/v2/cli/commands` | High
18 | File | `/aux` | Low
19 | File | `/bin/ate` | Medium
20 | File | `/boat/login.php` | High
21 | File | `/booking/show_bookings/` | High
22 | File | `/cas/logout` | Medium
23 | File | `/cgi-bin` | Medium
24 | File | `/cgi-bin/wlogin.cgi` | High
25 | File | `/changePassword` | High
26 | File | `/collection/all` | High
27 | File | `/Content/Template/root/reverse-shell.aspx` | High
28 | File | `/dashboard/add-blog.php` | High
29 | File | `/data/remove` | Medium
30 | File | `/debug/pprof` | Medium
31 | File | `/ecshop/admin/template.php` | High
32 | File | `/env` | Low
33 | File | `/etc/passwd` | Medium
34 | File | `/filex/read-raw` | High
35 | File | `/forum/away.php` | High
36 | File | `/goform/aspForm` | High
37 | File | `/group1/uploa` | High
38 | File | `/index.php` | Medium
39 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
40 | File | `/php-sms/admin/?page=user/manage_user` | High
41 | File | `/reservation/add_message.php` | High
42 | File | `/resources//../` | High
43 | File | `/testConnection` | High
44 | ... | ... | ...

There are 383 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/6c910d55-f846-46f8-bfa5-b6af3986466c
* https://app.any.run/tasks/47c2c5a4-d752-4ba2-a2d4-15665bd5aac3
* https://bazaar.abuse.ch/sample/bd7b6f6ef2d0adfb9b2e058fc46ad29ff1edffc648f9d7408745916bb8a2f310/
* https://de.darktrace.com/blog/laplas-clipper-defending-against-crypto-currency-thieves-with-detect-respond
* https://github.com/Cisco-Talos/IOCs/blob/main/2023/02/new-mortalkombat-ransomware-and-laplas-clipper-malware-threats.txt
* https://threatfox.abuse.ch
* https://twitter.com/1ZRR4H/status/1623067548781539339
* https://twitter.com/crep1x/status/1636352242969108484
* https://twitter.com/James_inthe_box/status/1626288456795291650

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
