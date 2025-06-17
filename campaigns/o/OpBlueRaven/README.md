# OpBlueRaven - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _OpBlueRaven_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OpBlueRaven:

* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/adfs/ls` | Medium
4 | File | `/admin.php?p=/Area/index#tab=t2` | High
5 | File | `/admin/add_ikev2.php` | High
6 | File | `/admin/category_save.php` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/list_ipAddressPolicy.php` | High
9 | File | `/admin/manage_model.php` | High
10 | File | `/admin/manage_user.php` | High
11 | File | `/admin/search-vehicle.php` | High
12 | File | `/admin/subject.php` | High
13 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
14 | File | `/admin/twitter.php` | High
15 | File | `/api/v1/toolbox/device/update/swap` | High
16 | File | `/app/zentao/module/repo/model.php` | High
17 | File | `/backend/admin/his_admin_register_patient.php` | High
18 | File | `/bin/httpd` | Medium
19 | File | `/boafrm/formFilter` | High
20 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
21 | File | `/catalog/all-products` | High
22 | File | `/cgi-bin/cstecgi.cgi` | High
23 | File | `/cgi-bin/ExportSettings.sh` | High
24 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
25 | File | `/com/esafenet/servlet/policy/HookService.java` | High
26 | File | `/decoration/admin/btndates_report.php` | High
27 | File | `/dental_form.php` | High
28 | File | `/edit-subject.php` | High
29 | File | `/endpoint/add-user.php` | High
30 | File | `/etc/postfix/sender_login` | High
31 | File | `/etc/shadow.sample` | High
32 | File | `/extensions/realestate/index.php/properties/list/list-with-sidebar/realties` | High
33 | File | `/foms/routers/place-order.php` | High
34 | File | `/forum/away.php` | High
35 | File | `/goform/AdvSetMacMtuWan` | High
36 | File | `/goform/aspForm` | High
37 | ... | ... | ...

There are 313 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/OpBlueRaven

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
