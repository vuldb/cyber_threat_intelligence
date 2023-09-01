# Mystic Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mystic Stealer](https://vuldb.com/?actor.mystic_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mystic_stealer](https://vuldb.com/?actor.mystic_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mystic Stealer:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mystic Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.94.125](https://vuldb.com/?ip.5.42.94.125) | juicy-milk.aeza.network | - | High
2 | [5.75.183.169](https://vuldb.com/?ip.5.75.183.169) | static.169.183.75.5.clients.your-server.de | - | High
3 | [23.163.0.179](https://vuldb.com/?ip.23.163.0.179) | mail.pnet-asp.tech | - | High
4 | [43.154.7.225](https://vuldb.com/?ip.43.154.7.225) | - | - | High
5 | [45.9.74.110](https://vuldb.com/?ip.45.9.74.110) | - | - | High
6 | [89.23.107.222](https://vuldb.com/?ip.89.23.107.222) | 4S-4-TG-1689355434.ip-ptr.tech | - | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mystic Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mystic Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/accessory/filesdel.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/admin/submit-articles` | High
8 | File | `/ad_js.php` | Medium
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
20 | File | `/cgi-bin` | Medium
21 | File | `/cgi-bin/luci/api/wireless` | High
22 | File | `/cgi-bin/wlogin.cgi` | High
23 | File | `/context/%2e/WEB-INF/web.xml` | High
24 | File | `/dashboard/reports/logs/view` | High
25 | File | `/debian/patches/load_ppp_generic_if_needed` | High
26 | File | `/debug/pprof` | Medium
27 | File | `/env` | Low
28 | File | `/etc/gsissh/sshd_config` | High
29 | File | `/etc/hosts` | Medium
30 | File | `/forum/away.php` | High
31 | File | `/goform/setmac` | High
32 | File | `/goform/wizard_end` | High
33 | File | `/group1/uploa` | High
34 | File | `/manage-apartment.php` | High
35 | File | `/medicines/profile.php` | High
36 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
37 | File | `/pages/apply_vacancy.php` | High
38 | File | `/php-sms/admin/?page=user/manage_user` | High
39 | File | `/proc/<PID>/mem` | High
40 | File | `/proxy` | Low
41 | File | `/reservation/add_message.php` | High
42 | File | `/resources//../` | High
43 | File | `/spip.php` | Medium
44 | File | `/tmp` | Low
45 | ... | ... | ...

There are 386 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/83e1bcf1-7e3f-46d1-b87f-9dc761b34cd0
* https://app.any.run/tasks/d1a96aea-a514-4f86-acd7-e9391a8ec959
* https://github.com/threatlabz/iocs/blob/main/mystic_stealer/c2s.txt
* https://pulsedive.com/threat/Mystic%20Stealer
* https://threatfox.abuse.ch
* https://www.zscaler.com/blogs/security-research/mystic-stealer

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
