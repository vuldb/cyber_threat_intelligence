# Carberp - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Carberp_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Carberp:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
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
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Carberp. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/admin/access` | High
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/budget/manage_budget.php` | High
6 | File | `/admin/del_category.php` | High
7 | File | `/admin/emp-profile-avatar.php` | High
8 | File | `/admin/index.html` | High
9 | File | `/admin/index.php?id=themes&action=edit_template&filename=blog` | High
10 | File | `/admin/manage_academic.php` | High
11 | File | `/admin/operations/expense_category.php` | High
12 | File | `/admin/posts.php` | High
13 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
14 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
15 | File | `/ajax.php?action=read_msg` | High
16 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
17 | File | `/backend/admin/his_admin_register_patient.php` | High
18 | File | `/cgi-bin/myMusic.cgi` | High
19 | File | `/cgi-bin/p1_ftpserver.php` | High
20 | File | `/ci_ssms/index.php/orders/create` | High
21 | File | `/control/register_case.php` | High
22 | File | `/CPE` | Low
23 | File | `/edoc/doctor/patient.php` | High
24 | File | `/enterprise/www/student.php` | High
25 | File | `/eval/admin/manage_subject.php` | High
26 | File | `/foms/routers/place-order.php` | High
27 | File | `/forum/away.php` | High
28 | File | `/front/actions.php` | High
29 | File | `/fw.login.php` | High
30 | File | `/h/autoSaveDraft` | High
31 | File | `/home/masterConsole` | High
32 | File | `/index.php` | Medium
33 | File | `/membres/modif_profil.php` | High
34 | File | `/ndmComponents.js` | High
35 | File | `/NotrinosERP/sales/customer_delivery.php` | High
36 | File | `/oauth/idp/.well-known/openid-configuration` | High
37 | File | `/ordering/admin/category/index.php?view=edit` | High
38 | File | `/pet_shop/admin/orders/update_status.php` | High
39 | File | `/pms/index.php` | High
40 | File | `/pms/update_user.php?user_id=1` | High
41 | File | `/register.php` | High
42 | File | `/request.php` | Medium
43 | File | `/SimpleBusTicket/index.php` | High
44 | File | `/transcation.php` | High
45 | File | `/uncpath/` | Medium
46 | File | `/update-image1.php` | High
47 | File | `/usr/bin/httpd` | High
48 | File | `/usr/bin/pkexec` | High
49 | File | `/var/run/docker.sock` | High
50 | File | `/view/emarks_range_grade_update_form.php` | High
51 | File | `/wp-admin/admin-ajax.php` | High
52 | File | `/xpdf/Stream.cc` | High
53 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
54 | File | `adclick.php` | Medium
55 | File | `addons/mediapool/pages/index.php` | High
56 | File | `addpost_newpoll.php` | High
57 | File | `adm-index.php` | High
58 | File | `Admin.PHP` | Medium
59 | File | `admin.php` | Medium
60 | File | `admin.php&r=article/AdminContent/edit` | High
61 | File | `admin/expense_report.php` | High
62 | File | `admin/index.php` | High
63 | ... | ... | ...

There are 552 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-new-sofacy-attacks-against-us-government-agency/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
