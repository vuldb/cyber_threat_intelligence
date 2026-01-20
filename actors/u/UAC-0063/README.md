# UAC-0063 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0063](https://vuldb.com/?actor.uac-0063). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0063](https://vuldb.com/?actor.uac-0063)

## Campaigns

The following _campaigns_ are known and can be associated with UAC-0063:

* CVE-2024-23692

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0063:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0063.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.70.178](https://vuldb.com/?ip.5.45.70.178) | yyy1.com | CVE-2024-23692 | High
2 | [38.180.87.154](https://vuldb.com/?ip.38.180.87.154) | - | - | High
3 | [45.136.198.184](https://vuldb.com/?ip.45.136.198.184) | - | CVE-2024-23692 | High
4 | [46.183.219.228](https://vuldb.com/?ip.46.183.219.228) | ip-219-228.dataclub.info | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0063_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0063. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin/aboutus.php` | High
3 | File | `/admin/category/add.do` | High
4 | File | `/admin/changeimage2.php` | High
5 | File | `/admin/delete-appointment.php` | High
6 | File | `/admin/deleteuser.php` | High
7 | File | `/admin/edit-category.php` | High
8 | File | `/admin/edit_supplier.php` | High
9 | File | `/admin/emp-profile-avatar.php` | High
10 | File | `/admin/process_category_edit.php` | High
11 | File | `/Admin/resultdetails.php` | High
12 | File | `/admin/user-search.php` | High
13 | File | `/ajax.php?action=save_deductions` | High
14 | File | `/ajax.php?action=save_user` | High
15 | File | `/api/wizard/getDualbandSync` | High
16 | File | `/app/api/controller/caiji.php` | High
17 | File | `/billing/pms_check.php` | High
18 | File | `/billing/test_accesscodelogin.php` | High
19 | File | `/boafrm/formPortFw` | High
20 | File | `/boafrm/formReflashClientTbl` | High
21 | File | `/boafrm/formTracerouteDiagnosticRun` | High
22 | File | `/cancelar-enturmacao-em-lote/` | High
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/hd_config.cgi` | High
25 | File | `/cgi-bin/luci/api/auth` | High
26 | File | `/cgi-bin/nas_sharing.cgi` | High
27 | File | `/cimom` | Low
28 | File | `/dashboard/Cinvoice/manage_invoice` | High
29 | File | `/dbhcms/ext/news/ext.news.be.php` | High
30 | File | `/dental_form.php` | High
31 | File | `/diario-de-observacoes/` | High
32 | File | `/discuss/uploadMdPic` | High
33 | ... | ... | ...

There are 278 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/4697016
* https://cert.gov.ua/article/6280129
* https://www.bitdefender.com/en-us/blog/businessinsights/uac-0063-cyber-espionage-operation-expanding-from-central-asia

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
