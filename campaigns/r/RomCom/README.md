# RomCom - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _RomCom_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RomCom:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with RomCom or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [RomCom](https://vuldb.com/?actor.romcom) | High
2 | [ROMCOM RAT](https://vuldb.com/?actor.romcom_rat) | High
3 | [TA569](https://vuldb.com/?actor.ta569) | High
4 | ... | ...

There are 2 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RomCom.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.94.207.116](https://vuldb.com/?ip.23.94.207.116) | 23-94-207-116-host.colocrossing.com | [UAT-5647](https://vuldb.com/?actor.uat-5647) | High
2 | [23.137.253.43](https://vuldb.com/?ip.23.137.253.43) | - | [UAT-5647](https://vuldb.com/?actor.uat-5647) | High
3 | [38.114.101.139](https://vuldb.com/?ip.38.114.101.139) | - | [TA569](https://vuldb.com/?actor.ta569) | High
4 | [45.138.74.238](https://vuldb.com/?ip.45.138.74.238) | military-giraffe.aeza.network | [RomCom](https://vuldb.com/?actor.romcom) | High
5 | [46.226.163.67](https://vuldb.com/?ip.46.226.163.67) | meaty-thrill.aeza.network | [RomCom](https://vuldb.com/?actor.romcom) | High
6 | [46.246.98.15](https://vuldb.com/?ip.46.246.98.15) | 46-246-98-15.static.glesys.net | [RomCom](https://vuldb.com/?actor.romcom) | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within RomCom. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during RomCom. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/accounts_con/register_account` | High
2 | File | `/admin/?page=inventory/view_inventory&id=2` | High
3 | File | `/admin/admin_user.php` | High
4 | File | `/admin/assigned-requests.php` | High
5 | File | `/admin/change-image.php` | High
6 | File | `/admin/delete_user.php` | High
7 | File | `/admin/File/pictureUpload` | High
8 | File | `/admin/modules/product/controller.php?action=add` | High
9 | File | `/Admin/News.php` | High
10 | File | `/admin/update.php` | High
11 | File | `/admin/user/manage_user.php` | High
12 | File | `/admin_class.php` | High
13 | File | `/ajax.php?action=save_establishment` | High
14 | File | `/anony/mjpg.cgi` | High
15 | File | `/api/admin/user` | High
16 | File | `/api/stl/actions/search` | High
17 | File | `/app/action/add_staff.php` | High
18 | File | `/app/ajax/sell_return_data.php` | High
19 | File | `/cgi-bin/nas_sharing.cgi` | High
20 | File | `/classes/Master.php?f=delete_inquiry` | High
21 | File | `/collect/PortV4/downLoad.html` | High
22 | File | `/conf/app.conf` | High
23 | File | `/cstecgi.cgi` | Medium
24 | File | `/dipam/athlete-profile.php` | High
25 | File | `/forum/away.php` | High
26 | File | `/freelance/resume_list` | High
27 | File | `/goform/DHCPReserveAddGroup` | High
28 | File | `/goform/setPWDbyBBS` | High
29 | File | `/goform/SetVirtualServerCfg` | High
30 | File | `/hrm/controller/employee.php` | High
31 | File | `/item/item_con` | High
32 | File | `/log/wifi.mac` | High
33 | File | `/login.php` | Medium
34 | ... | ... | ...

There are 290 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://arcticwolf.com/resources/blog/romcom-utilizing-socgholish-to-deliver-mythic-agent-to-usa-companies-supporting-ukraine/
* https://blog.talosintelligence.com/uat-5647-romcom/
* https://blogs.blackberry.com/en/2023/06/romcom-resurfaces-targeting-ukraine
* https://twitter.com/TLP_R3D/status/1655687889391431680
* https://www.trendmicro.com/en_us/research/23/e/void-rabisu-s-use-of-romcom-backdoor-shows-a-growing-shift-in-th.html
* https://www.welivesecurity.com/en/eset-research/romcom-exploits-firefox-and-windows-zero-days-in-the-wild/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
