# Royal - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Royal](https://vuldb.com/?actor.royal). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.royal](https://vuldb.com/?actor.royal)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Royal:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Royal.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.44.42.20](https://vuldb.com/?ip.5.44.42.20) | 4SER-1678212226.ip-ptr.tech | - | High
2 | [5.181.234.58](https://vuldb.com/?ip.5.181.234.58) | - | - | High
3 | [5.188.86.195](https://vuldb.com/?ip.5.188.86.195) | - | - | High
4 | [23.111.114.52](https://vuldb.com/?ip.23.111.114.52) | - | - | High
5 | [41.97.65.51](https://vuldb.com/?ip.41.97.65.51) | - | - | High
6 | [41.100.55.97](https://vuldb.com/?ip.41.100.55.97) | - | - | High
7 | [41.107.77.67](https://vuldb.com/?ip.41.107.77.67) | - | - | High
8 | [41.109.11.80](https://vuldb.com/?ip.41.109.11.80) | - | - | High
9 | [41.251.121.35](https://vuldb.com/?ip.41.251.121.35) | - | - | High
10 | [42.189.12.36](https://vuldb.com/?ip.42.189.12.36) | - | - | High
11 | [45.8.158.104](https://vuldb.com/?ip.45.8.158.104) | - | - | High
12 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Royal_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-35, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Royal. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//etc/RT2870STA.dat` | High
2 | File | `/account/forgotpassword` | High
3 | File | `/add_user.php` | High
4 | File | `/admin/ajax.php` | High
5 | File | `/Admin/akun_edit.php` | High
6 | File | `/admin/all_users.php` | High
7 | File | `/admin/clients/` | High
8 | File | `/admin/config_ISCGroupNoCache.php` | High
9 | File | `/admin/content/editor` | High
10 | File | `/admin/create_product.php` | High
11 | File | `/admin/DatabaseQuery` | High
12 | File | `/admin/deleteroom.php` | High
13 | File | `/admin/edit_role.php` | High
14 | File | `/admin/fetch_product_details.php` | High
15 | File | `/admin/index.php` | High
16 | File | `/admin/index.php/news/edit` | High
17 | File | `/admin/order.php` | High
18 | File | `/admin/profile.php` | High
19 | File | `/admin/project/update/2` | High
20 | File | `/Admin/Proses_Edit_Akun.php` | High
21 | File | `/admin/search-invoices.php` | High
22 | File | `/admin/settings/index.php?page=accounts` | High
23 | File | `/admin/template/edit` | High
24 | File | `/admin/twitter.php` | High
25 | File | `/adminapi/system/file/openfile` | High
26 | File | `/admin_ping.htm` | High
27 | File | `/ajax.php?action=delete_deductions` | High
28 | File | `/api/job/add/` | High
29 | File | `/Attachment/fromImageUrl` | High
30 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
31 | File | `/backend/admin/his_admin_add_vendor.php` | High
32 | File | `/backend/admin/his_admin_register_patient.php` | High
33 | File | `/backend/doc/his_doc_update-account.php` | High
34 | File | `/bloodrequest.php` | High
35 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
36 | File | `/cgi-bin/cstecgi.cgi` | High
37 | File | `/cgi-bin/luci/api/auth` | High
38 | File | `/chat/completions` | High
39 | File | `/CollatWebApp/gcmsRefInsert?name=SUPP` | High
40 | File | `/core/tools/add_translation.php` | High
41 | File | `/crm/weixinmp/index.php?userid=123&module=Users&usid=1&action=UsersAjax&minipro_const_type=1&related_module=Singin` | High
42 | File | `/customnode/install` | High
43 | File | `/department.php` | High
44 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
45 | File | `/DXR.axd` | Medium
46 | File | `/ECT_Provider/` | High
47 | File | `/edit/server` | Medium
48 | ... | ... | ...

There are 412 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-061a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
