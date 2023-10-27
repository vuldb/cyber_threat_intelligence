# LaplasClipper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LaplasClipper](https://vuldb.com/?actor.laplasclipper). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.laplasclipper](https://vuldb.com/?actor.laplasclipper)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LaplasClipper:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LaplasClipper.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.84.121.44](https://vuldb.com/?ip.45.84.121.44) | - | - | High
2 | [45.159.188.125](https://vuldb.com/?ip.45.159.188.125) | coinreborn24.com | - | High
3 | [45.159.189.105](https://vuldb.com/?ip.45.159.189.105) | . | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LaplasClipper_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LaplasClipper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/accessory/filesdel.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/delete_user.php` | High
7 | File | `/admin/doctors.php` | High
8 | File | `/admin/submit-articles` | High
9 | File | `/alphaware/summary.php` | High
10 | File | `/api/` | Low
11 | File | `/api/admin/store/product/list` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/stl/actions/search` | High
14 | File | `/api/v2/cli/commands` | High
15 | File | `/attachments` | Medium
16 | File | `/bin/ate` | Medium
17 | File | `/boat/login.php` | High
18 | File | `/booking/show_bookings/` | High
19 | File | `/bsms_ci/index.php/book` | High
20 | File | `/cas/logout` | Medium
21 | File | `/cgi-bin` | Medium
22 | File | `/cgi-bin/luci/api/wireless` | High
23 | File | `/cgi-bin/wlogin.cgi` | High
24 | File | `/collection/all` | High
25 | File | `/Content/Template/root/reverse-shell.aspx` | High
26 | File | `/context/%2e/WEB-INF/web.xml` | High
27 | File | `/dashboard/add-blog.php` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/env` | Low
30 | File | `/etc/gsissh/sshd_config` | High
31 | File | `/etc/hosts` | Medium
32 | File | `/forum/away.php` | High
33 | File | `/goform/setmac` | High
34 | File | `/goform/wizard_end` | High
35 | File | `/group1/uploa` | High
36 | File | `/hrm/controller/employee.php` | High
37 | File | `/medicines/profile.php` | High
38 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
39 | File | `/out.php` | Medium
40 | File | `/php-sms/admin/?page=user/manage_user` | High
41 | File | `/proxy` | Low
42 | File | `/reservation/add_message.php` | High
43 | ... | ... | ...

There are 375 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/6c910d55-f846-46f8-bfa5-b6af3986466c
* https://app.any.run/tasks/47c2c5a4-d752-4ba2-a2d4-15665bd5aac3
* https://bazaar.abuse.ch/sample/bd7b6f6ef2d0adfb9b2e058fc46ad29ff1edffc648f9d7408745916bb8a2f310/
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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
