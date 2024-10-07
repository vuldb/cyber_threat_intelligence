# Mystic Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mystic Stealer](https://vuldb.com/?actor.mystic_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mystic_stealer](https://vuldb.com/?actor.mystic_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mystic Stealer:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mystic Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.111.145.27](https://vuldb.com/?ip.3.111.145.27) | ec2-3-111-145-27.ap-south-1.compute.amazonaws.com | - | Medium
2 | [5.42.64.18](https://vuldb.com/?ip.5.42.64.18) | - | - | High
3 | [5.42.64.20](https://vuldb.com/?ip.5.42.64.20) | - | - | High
4 | [5.42.65.126](https://vuldb.com/?ip.5.42.65.126) | - | - | High
5 | [5.42.92.43](https://vuldb.com/?ip.5.42.92.43) | hosted-by.yeezyhost.net | - | High
6 | [5.42.92.88](https://vuldb.com/?ip.5.42.92.88) | hosted-by.yeezyhost.net | - | High
7 | [5.42.92.211](https://vuldb.com/?ip.5.42.92.211) | . | - | High
8 | [5.42.94.125](https://vuldb.com/?ip.5.42.94.125) | juicy-milk.aeza.network | - | High
9 | [5.75.183.169](https://vuldb.com/?ip.5.75.183.169) | static.169.183.75.5.clients.your-server.de | - | High
10 | [5.188.87.45](https://vuldb.com/?ip.5.188.87.45) | - | - | High
11 | [5.196.93.222](https://vuldb.com/?ip.5.196.93.222) | 934.gra.abcvg.ovh | - | High
12 | [13.200.127.74](https://vuldb.com/?ip.13.200.127.74) | ec2-13-200-127-74.ap-south-1.compute.amazonaws.com | - | Medium
13 | [13.208.166.206](https://vuldb.com/?ip.13.208.166.206) | ec2-13-208-166-206.ap-northeast-3.compute.amazonaws.com | - | Medium
14 | [13.232.156.210](https://vuldb.com/?ip.13.232.156.210) | ec2-13-232-156-210.ap-south-1.compute.amazonaws.com | - | Medium
15 | [23.163.0.179](https://vuldb.com/?ip.23.163.0.179) | mail.pnet-asp.tech | - | High
16 | [34.88.245.41](https://vuldb.com/?ip.34.88.245.41) | 41.245.88.34.bc.googleusercontent.com | - | Medium
17 | [37.139.129.70](https://vuldb.com/?ip.37.139.129.70) | - | - | High
18 | [41.208.73.44](https://vuldb.com/?ip.41.208.73.44) | 41.208.73.44.static.ltt.ly | - | High
19 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mystic Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mystic Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/add_ikev2.php` | High
3 | File | `/admin/category_save.php` | High
4 | File | `/admin/index2.html` | High
5 | File | `/admin/list_ipAddressPolicy.php` | High
6 | File | `/admin/manage_model.php` | High
7 | File | `/admin/manage_user.php` | High
8 | File | `/admin/subject.php` | High
9 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
10 | File | `/catalog/all-products` | High
11 | File | `/cgi-bin/cstecgi.cgi` | High
12 | File | `/cgi-bin/koha/catalogue/search.pl` | High
13 | File | `/changePassword` | High
14 | File | `/edit-subject.php` | High
15 | File | `/endpoint/add-user.php` | High
16 | File | `/etc/postfix/sender_login` | High
17 | File | `/foms/routers/place-order.php` | High
18 | File | `/forum/away.php` | High
19 | File | `/goform/SetSysTimeCfg` | High
20 | File | `/index.php` | Medium
21 | File | `/index/ajax/lang` | High
22 | File | `/lesson/controller.php` | High
23 | File | `/log/decodmail.php` | High
24 | File | `/login/userinfo.php` | High
25 | File | `/mailcleaner.php/getStats` | High
26 | ... | ... | ...

There are 216 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/3bfdcee7-1163-4cb5-a421-c89ebe581fb3
* https://app.any.run/tasks/6a907458-4ae2-4bbf-a4cd-120e7c7c5b60
* https://app.any.run/tasks/83e1bcf1-7e3f-46d1-b87f-9dc761b34cd0
* https://app.any.run/tasks/342f5538-7e82-4f54-908e-18efa2cc2669
* https://app.any.run/tasks/b15ddaaf-9197-4310-af15-d2f45ef44c91
* https://app.any.run/tasks/d1a96aea-a514-4f86-acd7-e9391a8ec959
* https://blog.pulsedive.com/identifying-mystic-stealer-control-panels/
* https://github.com/threatlabz/iocs/blob/main/mystic_stealer/c2s.txt
* https://pulsedive.com/threat/Mystic%20Stealer
* https://threatfox.abuse.ch
* https://www.zscaler.com/blogs/security-research/mystic-stealer

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
