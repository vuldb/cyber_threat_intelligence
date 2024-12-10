# OpBlueRaven - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _OpBlueRaven_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OpBlueRaven:

* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* [ES](https://vuldb.com/?country.es)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with OpBlueRaven or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FIN7](https://vuldb.com/?actor.fin7) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of OpBlueRaven.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.177.23](https://vuldb.com/?ip.5.252.177.23) | 5-252-177-23.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
2 | [5.252.177.37](https://vuldb.com/?ip.5.252.177.37) | no-rdns.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
3 | [23.83.133.119](https://vuldb.com/?ip.23.83.133.119) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
4 | [37.1.211.239](https://vuldb.com/?ip.37.1.211.239) | ourdrops.org | [FIN7](https://vuldb.com/?actor.fin7) | High
5 | [37.1.215.4](https://vuldb.com/?ip.37.1.215.4) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
6 | [37.1.215.72](https://vuldb.com/?ip.37.1.215.72) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
7 | [37.252.4.131](https://vuldb.com/?ip.37.252.4.131) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
8 | [45.77.60.230](https://vuldb.com/?ip.45.77.60.230) | 45.77.60.230.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
9 | [45.77.204.130](https://vuldb.com/?ip.45.77.204.130) | 45.77.204.130.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
10 | [45.87.152.64](https://vuldb.com/?ip.45.87.152.64) | free.pq.hosting | [FIN7](https://vuldb.com/?actor.fin7) | High
11 | [45.133.216.25](https://vuldb.com/?ip.45.133.216.25) | lisulisimp.example.com | [FIN7](https://vuldb.com/?actor.fin7) | High
12 | ... | ... | ... | ...

There are 44 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/boafrm/formFilter` | High
10 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
11 | File | `/catalog/all-products` | High
12 | File | `/cgi-bin/cstecgi.cgi` | High
13 | File | `/cgi-bin/ExportSettings.sh` | High
14 | File | `/changePassword` | High
15 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
16 | File | `/edit-subject.php` | High
17 | File | `/endpoint/add-user.php` | High
18 | File | `/etc/postfix/sender_login` | High
19 | File | `/etc/shadow.sample` | High
20 | File | `/foms/routers/place-order.php` | High
21 | File | `/forum/away.php` | High
22 | File | `/goform/goform_get_cmd_process` | High
23 | File | `/goform/SetLEDCfg` | High
24 | File | `/goform/setMacFilterCfg` | High
25 | File | `/goform/SetSysTimeCfg` | High
26 | ... | ... | ...

There are 223 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/OpBlueRaven

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
