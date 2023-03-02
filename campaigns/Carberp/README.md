# Carberp - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Carberp_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Carberp:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Carberp or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT28](https://vuldb.com/?actor.apt28) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Carberp.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [66.172.11.207](https://vuldb.com/?ip.66.172.11.207) | ip-66-172-11-207.chunkhost.com | [APT28](https://vuldb.com/?actor.apt28) | High
2 | [191.101.31.6](https://vuldb.com/?ip.191.101.31.6) | - | [APT28](https://vuldb.com/?actor.apt28) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Carberp. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Carberp. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/access` | High
2 | File | `/admin/addemployee.php` | High
3 | File | `/admin/index.html` | High
4 | File | `/admin/index.php?id=themes&action=edit_template&filename=blog` | High
5 | File | `/admin/posts.php` | High
6 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
7 | File | `/ci_ssms/index.php/orders/create` | High
8 | File | `/fw.login.php` | High
9 | File | `/home/masterConsole` | High
10 | File | `/index.php` | Medium
11 | File | `/membres/modif_profil.php` | High
12 | File | `/ordering/admin/category/index.php?view=edit` | High
13 | File | `/pms/index.php` | High
14 | File | `/pms/update_user.php?user_id=1` | High
15 | File | `/SimpleBusTicket/index.php` | High
16 | File | `/uncpath/` | Medium
17 | File | `/usr/bin/pkexec` | High
18 | File | `/var/run/docker.sock` | High
19 | File | `/wp-admin/admin-ajax.php` | High
20 | File | `/xpdf/Stream.cc` | High
21 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
22 | File | `addpost_newpoll.php` | High
23 | File | `adm-index.php` | High
24 | File | `Admin.PHP` | Medium
25 | File | `admin.php` | Medium
26 | File | `admin.php&r=article/AdminContent/edit` | High
27 | File | `admin/expense_report.php` | High
28 | File | `admin/index.php` | High
29 | File | `admin/ops/reports/ops/forum.php` | High
30 | File | `admincp/attachment.php` | High
31 | File | `adminedit.pl` | Medium
32 | File | `ajax/api/hook/getHookList` | High
33 | File | `App\Manage\Controller\ArticleController.class.php` | High
34 | File | `archive/index.php` | High
35 | File | `auth-gss2.c` | Medium
36 | File | `backend/groups/index.php` | High
37 | File | `bbs/member_confirm.php` | High
38 | File | `bottom.php` | Medium
39 | File | `breadcrumbs_create.php` | High
40 | File | `C:\Program Files\FileZilla FTP Client\uninstall.exe` | High
41 | File | `cds-fpdf.php` | Medium
42 | File | `common.php` | Medium
43 | File | `controllers/member/Api.php` | High
44 | ... | ... | ...

There are 384 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-new-sofacy-attacks-against-us-government-agency/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
