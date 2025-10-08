# ScreenConnect - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ScreenConnect](https://vuldb.com/?actor.screenconnect). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.screenconnect](https://vuldb.com/?actor.screenconnect)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ScreenConnect:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ScreenConnect.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.95.173.124](https://vuldb.com/?ip.23.95.173.124) | 23-95-173-124-host.colocrossing.com | - | High
2 | [31.129.22.45](https://vuldb.com/?ip.31.129.22.45) | 106558.ip-ptr.tech | - | High
3 | [45.138.16.87](https://vuldb.com/?ip.45.138.16.87) | 45.138.16.87.powered.by.rdp.sh | - | High
4 | [45.141.233.108](https://vuldb.com/?ip.45.141.233.108) | - | - | High
5 | [62.60.226.252](https://vuldb.com/?ip.62.60.226.252) | - | - | High
6 | [91.238.181.238](https://vuldb.com/?ip.91.238.181.238) | - | - | High
7 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ScreenConnect_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-29, CWE-35 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ScreenConnect. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?page=album` | High
2 | File | `/admin/action/new-feed.php` | High
3 | File | `/Admin/add-admin.php` | High
4 | File | `/admin/add-art-product.php` | High
5 | File | `/admin/admin_action.php` | High
6 | File | `/admin/admin_members.php?ac=search` | High
7 | File | `/admin/ajax.php?action=delete_application` | High
8 | File | `/admin/ajax.php?action=login` | High
9 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
10 | File | `/admin/blood/update/B+.php` | High
11 | File | `/admin/book_add.php` | High
12 | File | `/admin/category/view_category.php` | High
13 | File | `/admin/cmsTemplate/replace` | High
14 | File | `/admin/content/data` | High
15 | File | `/admin/content/editor` | High
16 | File | `/admin/customermanagementframework/customers/list` | High
17 | File | `/admin/deleteBooking.php` | High
18 | File | `/admin/edit-artist-detail.php?editid=1` | High
19 | File | `/admin/edit_student_query.php` | High
20 | File | `/admin/foreigner-search.php` | High
21 | File | `/admin/index.php` | High
22 | File | `/admin/index.php?act=reset_admin_psw` | High
23 | File | `/admin/list_crl_conf` | High
24 | File | `/admin/manage-ambulance.php` | High
25 | File | `/admin/manage-foreigners-ticket.php` | High
26 | File | `/admin/moneyRecord_deal.php?mudi=delRecord` | High
27 | File | `/admin/normal-search.php` | High
28 | File | `/admin/password-recovery.php` | High
29 | File | `/admin/print.php` | High
30 | File | `/admin/product.php` | High
31 | File | `/admin/products/index.php` | High
32 | File | `/admin/registration.php` | High
33 | File | `/admin/template` | High
34 | File | `/admin/twitter.php` | High
35 | File | `/admin/update_room.php` | High
36 | File | `/admin/update_s7.php` | High
37 | File | `/admin/users_photo.php` | High
38 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
39 | File | `/ajax/ajax_login.ashx` | High
40 | File | `/Android/data/com.myairtelapp/files/` | High
41 | File | `/animalsupdate.php` | High
42 | File | `/api/admin` | Medium
43 | File | `/api/admin/user?id` | High
44 | File | `/api/blade-user/export-user` | High
45 | File | `/api/upload` | Medium
46 | File | `/apply.cgi` | Medium
47 | File | `/auth/list_projects` | High
48 | File | `/backend/admin/his_admin_register_patient.php` | High
49 | File | `/bin/httpd` | Medium
50 | File | `/boafrm/formPortFw` | High
51 | File | `/buscar_integrada.php` | High
52 | File | `/catalog/compare` | High
53 | File | `/cgi-bin/cstecgi.cgi` | High
54 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
55 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
56 | File | `/cgi-bin/photocenter_mgr.cgi` | High
57 | File | `/class/edit/edit` | High
58 | File | `/classes/Master.php? f=save_medicine` | High
59 | File | `/classes/SystemSettings.php?f=update_settings` | High
60 | File | `/clinic/disease_symptoms_view.php` | High
61 | ... | ... | ...

There are 533 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/2024-02_Payloads_associated_with_ScreenConnect_attacks.csv
* https://thedfirreport.com/2023/09/25/from-screenconnect-to-hive-ransomware-in-61-hours/
* https://urlhaus.abuse.ch/url/3535241/
* https://urlhaus.abuse.ch/url/3535242/
* https://urlhaus.abuse.ch/url/3535243/
* https://urlhaus.abuse.ch/url/3535246/
* https://urlhaus.abuse.ch/url/3535247/
* https://urlhaus.abuse.ch/url/3535248/
* https://urlhaus.abuse.ch/url/3535249/
* https://urlhaus.abuse.ch/url/3535250/
* https://urlhaus.abuse.ch/url/3535251/
* https://urlhaus.abuse.ch/url/3535252/
* https://urlhaus.abuse.ch/url/3535253/
* https://urlhaus.abuse.ch/url/3535254/
* https://urlhaus.abuse.ch/url/3535255/
* https://urlhaus.abuse.ch/url/3535256/
* https://urlhaus.abuse.ch/url/3538650/
* https://urlhaus.abuse.ch/url/3578977/
* https://urlhaus.abuse.ch/url/3582040/
* https://urlhaus.abuse.ch/url/3586099/
* https://urlhaus.abuse.ch/url/3592996/
* https://urlhaus.abuse.ch/url/3601203/
* https://urlhaus.abuse.ch/url/3601206/
* https://urlhaus.abuse.ch/url/3601212/
* https://urlhaus.abuse.ch/url/3601213/
* https://urlhaus.abuse.ch/url/3601214/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
