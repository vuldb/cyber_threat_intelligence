# Magento - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magento](https://vuldb.com/?actor.magento). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magento](https://vuldb.com/?actor.magento)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magento:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [CO](https://vuldb.com/?country.co)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Magento.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.45.2](https://vuldb.com/?ip.2.58.45.2) | - | - | High
2 | [8.208.15.67](https://vuldb.com/?ip.8.208.15.67) | - | - | High
3 | [45.114.8.166](https://vuldb.com/?ip.45.114.8.166) | - | - | High
4 | [47.254.202.112](https://vuldb.com/?ip.47.254.202.112) | - | - | High
5 | [50.7.159.34](https://vuldb.com/?ip.50.7.159.34) | - | - | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Magento_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magento. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=route_ispinfo_export_save` | High
2 | File | `/admin/index.php` | High
3 | File | `/admin/role` | Medium
4 | File | `/api/es/admin/v3/security/user/1` | High
5 | File | `/api /v3/auth` | High
6 | File | `/api/workspace/:workspace-slug/update` | High
7 | File | `/boaform/getASPdata/formFirewall` | High
8 | File | `/cgi-bin/lighttpd.cgi` | High
9 | File | `/cgi-bin/webviewer_login_page` | High
10 | File | `/cgi-bin/wlogin.cgi` | High
11 | File | `/common/sysFile/list` | High
12 | File | `/Content/Template/root/reverse-shell.aspx` | High
13 | File | `/dede/group_store.php` | High
14 | File | `/ebics-server/ebics.aspx` | High
15 | File | `/forum/away.php` | High
16 | File | `/fuel/index.php/fuel/logs/items` | High
17 | File | `/hedwig.cgi` | Medium
18 | File | `/index.php` | Medium
19 | File | `/monitoring` | Medium
20 | File | `/ocwbs/classes/Master.php?f=get_vehicle_service` | High
21 | File | `/one/getpassword.php` | High
22 | File | `/out.php` | Medium
23 | File | `/phppath/php` | Medium
24 | File | `/pms/admin/crimes/manage_crime.php` | High
25 | File | `/preview.php` | Medium
26 | File | `/products/details.asp` | High
27 | File | `/products/view_product.php` | High
28 | File | `/sec/content/sec_asa_users_local_db_add.html` | High
29 | File | `/secure/admin/AssociatedProjectsForCustomField.jspa` | High
30 | File | `/secure/QueryComponent!Default.jspa` | High
31 | File | `/servlet/webacc` | High
32 | File | `/setNTP.cgi` | Medium
33 | File | `/Side.php` | Medium
34 | File | `/spip/ecrire/` | High
35 | File | `/storage` | Medium
36 | File | `/uncpath/` | Medium
37 | File | `/uploads/tags.php` | High
38 | File | `/userfs/bin/tcapi` | High
39 | ... | ... | ...

There are 340 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.sucuri.net/2019/08/magento-skimmers-from-atob-to-alibaba.html
* https://sansec.io/research/cardbleed
* https://sansec.io/research/magento-2-persistent-parasite

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
