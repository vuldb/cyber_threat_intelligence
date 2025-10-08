# MetaStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MetaStealer](https://vuldb.com/?actor.metastealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.metastealer](https://vuldb.com/?actor.metastealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MetaStealer:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MetaStealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [4.224.60.120](https://vuldb.com/?ip.4.224.60.120) | - | - | High
2 | [5.181.3.9](https://vuldb.com/?ip.5.181.3.9) | 57723.ip-ptr.tech | - | High
3 | [13.114.196.60](https://vuldb.com/?ip.13.114.196.60) | ec2-13-114-196-60.ap-northeast-1.compute.amazonaws.com | - | Medium
4 | [13.125.88.10](https://vuldb.com/?ip.13.125.88.10) | ec2-13-125-88-10.ap-northeast-2.compute.amazonaws.com | - | Medium
5 | [31.192.232.4](https://vuldb.com/?ip.31.192.232.4) | klipto.man00.1.pserver.space | - | High
6 | [62.133.62.234](https://vuldb.com/?ip.62.133.62.234) | 52184.ip-ptr.tech | - | High
7 | [77.110.107.38](https://vuldb.com/?ip.77.110.107.38) | - | - | High
8 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MetaStealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MetaStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/admin` | Low
3 | File | `/admin/admin-profile.php` | High
4 | File | `/admin/create_product.php` | High
5 | File | `/admin/edit_area.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/inquiries/view_details.php` | High
8 | File | `/admin/login.php` | High
9 | File | `/api/esps` | Medium
10 | File | `/app/admin/controller/Upload.php` | High
11 | File | `/appointment-history.php` | High
12 | File | `/APR/signup.php` | High
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
15 | File | `/classes/SystemSettings.php?f=update_settings` | High
16 | File | `/cms/classes/Master.php?f=delete_service` | High
17 | File | `/complainer_page.php` | High
18 | File | `/download` | Medium
19 | File | `/endpoint/Add.php` | High
20 | File | `/endpoint/delete-menu.php` | High
21 | File | `/endpoint/update.php` | High
22 | File | `/expense-datewise-reports-detailed.php` | High
23 | File | `/feed/insert.json` | High
24 | File | `/filemanager/php/connector.php` | High
25 | File | `/forum/away.php` | High
26 | File | `/include/file.php` | High
27 | File | `/index.php` | Medium
28 | File | `/mfeedback.php` | High
29 | File | `/news-details.php` | High
30 | File | `/php_action/createUser.php` | High
31 | ... | ... | ...

There are 262 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/3fee3583-590c-4f90-ac08-4e22e0b27b2f
* https://app.any.run/tasks/5af15c83-3f5f-4572-966a-1f0d9e4d9b02/
* https://app.any.run/tasks/7ade5940-ac62-447e-a271-d8c5ab94df26
* https://app.any.run/tasks/880feaf2-29fd-42a8-ad05-9638f08ee84a
* https://app.any.run/tasks/a5179dde-6f3d-4980-aa44-302c95af337e
* https://app.any.run/tasks/e09bf6ae-ab79-46bb-885b-01199d756cf5
* https://bazaar.abuse.ch/sample/17ad6e2c8fb12b9c3d587cf7a4814bf6e20758589e82517420f196599c75f1ec/
* https://bazaar.abuse.ch/sample/228fcd364fef173631f410410a13560f717a84f65aa306e9a3aa2429c755dc60/
* https://bazaar.abuse.ch/sample/4641c993478534eeca8f5c777f352e0f3592d1dc67f52fabc3ff3957f195e8ab/
* https://bazaar.abuse.ch/sample/b1b4ffcd21342c7de7f0bc286eb3f4ec6a5b919df5f20d383b4df0bd462cbe48/
* https://bazaar.abuse.ch/sample/d3da939964cbf347635dd39214d941dc4bd59c84060ae4465ee6e943bae79dc9/
* https://bazaar.abuse.ch/sample/e916c8e22f9cbe3fd58afc2b228db2a07790808681bc3362061e615d14ef402c/
* https://bazaar.abuse.ch/sample/e8185b17156f56d07e51573d63ae3060e1e8341555fe083ab1328609decdcc60/
* https://bazaar.abuse.ch/sample/ec202b2050cc7a4030c74c6fa04ef98e67c11fa64a1a1dd0ff592141ff7771de/
* https://isc.sans.edu/forums/diary/Windows+MetaStealer+Malware/28522/
* https://medium.com/walmartglobaltech/metastealer-string-decryption-and-dga-overview-5f38f76830cd
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3522895/
* https://urlhaus.abuse.ch/url/3526534/
* https://urlhaus.abuse.ch/url/3526949/
* https://urlhaus.abuse.ch/url/3538129/
* https://urlhaus.abuse.ch/url/3540591/
* https://urlhaus.abuse.ch/url/3545419/
* https://urlhaus.abuse.ch/url/3548715/
* https://urlhaus.abuse.ch/url/3548743/
* https://urlhaus.abuse.ch/url/3552798/
* https://urlhaus.abuse.ch/url/3568063/
* https://urlhaus.abuse.ch/url/3592796/
* https://www.sentinelone.com/blog/macos-metastealer-new-family-of-obfuscated-go-infostealers-spread-in-targeted-attacks/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
