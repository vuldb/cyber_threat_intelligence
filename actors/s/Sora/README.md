# Sora - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sora](https://vuldb.com/?actor.sora). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sora](https://vuldb.com/?actor.sora)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sora:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sora.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.148.10.86](https://vuldb.com/?ip.45.148.10.86) | - | - | High
2 | [193.70.125.169](https://vuldb.com/?ip.193.70.125.169) | ip169.ip-193-70-125.eu | - | High
3 | [209.141.45.139](https://vuldb.com/?ip.209.141.45.139) | smtp6.thkingl.top | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sora_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sora. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `.htaccess` | Medium
3 | File | `/admin/?/layout/add` | High
4 | File | `/admin/admin_cl.php?mudi=revPwd` | High
5 | File | `/admin/dialog/select_images_post.php` | High
6 | File | `/admin/featured.php` | High
7 | File | `/admin/pass-bwdates-reports-details.php` | High
8 | File | `/admin/search-medicalcard.php` | High
9 | File | `/ajax.php` | Medium
10 | File | `/api/email_accounts` | High
11 | File | `/app/config/of` | High
12 | File | `/APR/login.php` | High
13 | File | `/artist-display.php` | High
14 | File | `/bin/su` | Low
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/cgi-bin/hd_config.cgi` | High
17 | File | `/cgi-bin/mainfunction.cgi` | High
18 | File | `/classes/Master.php` | High
19 | File | `/classes/Master.php?f=delete_category` | High
20 | File | `/common/security/realms/realms.jsf` | High
21 | File | `/configuration/auditModuleEdit.jsf` | High
22 | File | `/configuration/configuration.jsf` | High
23 | File | `/configuration/httpListenerEdit.jsf` | High
24 | File | `/control/forgot_pass.php` | High
25 | File | `/core/model/modx/modmanagerrequest.class.php` | High
26 | File | `/easy-team-manager/inc/easy_team_manager_desc_edit.php` | High
27 | File | `/endpoint/delete.php` | High
28 | File | `/etc/srapi/config/system.conf` | High
29 | File | `/file_manager/login.php` | High
30 | File | `/film-rating.php` | High
31 | File | `/goform/formSetMACFilter` | High
32 | File | `/goform/modifyDhcpRule` | High
33 | File | `/goform/ModifyPppAuthWhiteMac` | High
34 | File | `/goform/SetSysTimeCfg` | High
35 | File | `/goform/WizardHandle` | High
36 | File | `/includes/` | Medium
37 | File | `/index.php/admin` | High
38 | File | `/librarian/lab.php` | High
39 | File | `/manage_block.php` | High
40 | File | `/movie.php` | Medium
41 | File | `/ndmComponents.js` | High
42 | File | `/pet_shop/classes/Master.php?f=delete_order` | High
43 | File | `/pineapple/ui` | High
44 | File | `/report/ParkChargeRecord/GetDataList` | High
45 | File | `/resourceNode/jdbcResourceEdit.jsf` | High
46 | File | `/resourceNode/resources.jsf` | High
47 | File | `/show_news.php` | High
48 | File | `/staff/bookdetails.php` | High
49 | File | `/staff/edit_book_details.php` | High
50 | File | `/staff/lab.php` | High
51 | ... | ... | ...

There are 444 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.trendmicro.co.jp/wp-content/uploads/2020/02/IoCs_SORA_UNSTABLE.pdf
* https://s.tencent.com/research/report/1177.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
