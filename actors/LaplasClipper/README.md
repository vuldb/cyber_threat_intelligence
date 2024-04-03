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
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LaplasClipper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin/controller/JobLogController.java` | High
3 | File | `/admin/user/manage_user.php` | High
4 | File | `/api/` | Low
5 | File | `/api/admin/store/product/list` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/stl/actions/search` | High
8 | File | `/api/sys/login` | High
9 | File | `/api/sys/set_passwd` | High
10 | File | `/api/trackedEntityInstances` | High
11 | File | `/api/v2/cli/commands` | High
12 | File | `/aux` | Low
13 | File | `/bin/ate` | Medium
14 | File | `/booking/show_bookings/` | High
15 | File | `/cas/logout` | Medium
16 | File | `/cgi-bin` | Medium
17 | File | `/cgi-bin/wlogin.cgi` | High
18 | File | `/changePassword` | High
19 | File | `/collection/all` | High
20 | File | `/Content/Template/root/reverse-shell.aspx` | High
21 | File | `/dashboard/add-blog.php` | High
22 | File | `/data/remove` | Medium
23 | File | `/debug/pprof` | Medium
24 | File | `/ecshop/admin/template.php` | High
25 | File | `/env` | Low
26 | File | `/etc/passwd` | Medium
27 | File | `/filex/read-raw` | High
28 | File | `/forum/away.php` | High
29 | File | `/goform/aspForm` | High
30 | File | `/goform/net\_Web\_get_value` | High
31 | File | `/group1/uploa` | High
32 | File | `/index.php` | Medium
33 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
34 | File | `/php-sms/admin/?page=user/manage_user` | High
35 | File | `/resources//../` | High
36 | File | `/testConnection` | High
37 | File | `/tmp/ppd.trace` | High
38 | File | `/user/inc/workidajax.php` | High
39 | File | `/user/updatePwd` | High
40 | File | `/userLogin.asp` | High
41 | ... | ... | ...

There are 349 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
