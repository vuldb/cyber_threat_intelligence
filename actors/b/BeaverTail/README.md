# BeaverTail - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BeaverTail](https://vuldb.com/?actor.beavertail). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.beavertail](https://vuldb.com/?actor.beavertail)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BeaverTail:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BeaverTail.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.253.43.122](https://vuldb.com/?ip.5.253.43.122) | - | - | High
2 | [23.227.202.244](https://vuldb.com/?ip.23.227.202.244) | 23-227-202-244.static.hvvc.us | - | High
3 | [37.221.126.117](https://vuldb.com/?ip.37.221.126.117) | vm4038553.stark-industries.solutions | - | High
4 | [38.92.47.85](https://vuldb.com/?ip.38.92.47.85) | - | - | High
5 | [38.92.47.91](https://vuldb.com/?ip.38.92.47.91) | - | - | High
6 | [38.92.47.151](https://vuldb.com/?ip.38.92.47.151) | - | - | High
7 | [45.8.146.93](https://vuldb.com/?ip.45.8.146.93) | vm2985624.stark-industries.solutions | - | High
8 | [45.12.141.170](https://vuldb.com/?ip.45.12.141.170) | vm3700987.stark-industries.solutions | - | High
9 | [45.43.11.201](https://vuldb.com/?ip.45.43.11.201) | - | - | High
10 | [45.61.150.31](https://vuldb.com/?ip.45.61.150.31) | - | - | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BeaverTail_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BeaverTail. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add-apartment.php` | High
2 | File | `/admin-control.php` | High
3 | File | `/admin.php/appcenter/local.html?type=addon` | High
4 | File | `/admin/?page=system_info` | High
5 | File | `/admin/?page=system_info/contact_info` | High
6 | File | `/admin/action/new-father.php` | High
7 | File | `/admin/add-art-medium.php` | High
8 | File | `/admin/add-team.php` | High
9 | File | `/admin/add_retailer.php` | High
10 | File | `/admin/admin-area.php` | High
11 | File | `/admin/booking-bwdates-reports-details.php` | High
12 | File | `/admin/edit-team.php` | High
13 | File | `/admin/invoice.php` | High
14 | File | `/admin/maintenance/brand.php` | High
15 | File | `/admin/manage-art-medium.php` | High
16 | File | `/auth/userkey/logout.php` | High
17 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
18 | File | `/cakeshop/supplier.php` | High
19 | File | `/category_view.php` | High
20 | File | `/cgi-bin/cstecgi.cgi` | High
21 | File | `/details.php` | Medium
22 | File | `/DXR.axd` | Medium
23 | File | `/endpoint/delete-mark.php` | High
24 | File | `/film-rating.php` | High
25 | File | `/forum/away.php` | High
26 | File | `/goform/SetSysAutoRebbotCfg` | High
27 | File | `/handgunner-administrator/prod.php` | High
28 | File | `/horde/util/go.php` | High
29 | File | `/hospital/hms/admin/manage-doctors.php` | High
30 | File | `/index.php/Login/login` | High
31 | File | `/index.php?r=admin/database/index/updatesurveylocalesettings_generalsettings` | High
32 | File | `/librarian/bookdetails.php` | High
33 | File | `/locales/locale.json` | High
34 | File | `/login.php` | Medium
35 | File | `/manage-apartment.php` | High
36 | File | `/mark.php` | Medium
37 | File | `/multi-vendor-shopping-script/product-list.php` | High
38 | File | `/officer/assigncase.php` | High
39 | File | `/owa/auth/logon.aspx` | High
40 | File | `/php-jms/review_se_result.php` | High
41 | File | `/product-detail.php` | High
42 | ... | ... | ...

There are 358 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/87299/
* https://github.com/Cisco-Talos/IOCs/blob/main/2025/10/beavertail-and-ottercookie.txt
* https://search.censys.io/hosts/67.203.7.163
* https://search.censys.io/hosts/147.124.214.129
* https://search.censys.io/hosts/147.124.214.131
* https://search.censys.io/hosts/147.124.214.237
* https://socket.dev/blog/north-korean-apt-lazarus-targets-developers-with-malicious-npm-package
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3526728/
* https://urlhaus.abuse.ch/url/3526729/
* https://www.trendmicro.com/en_us/research/25/d/russian-infrastructure-north-korean-cybercrime.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
