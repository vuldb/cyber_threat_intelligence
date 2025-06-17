# CoralRaider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CoralRaider](https://vuldb.com/?actor.coralraider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.coralraider](https://vuldb.com/?actor.coralraider)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CoralRaider:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CoralRaider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.225.210.97](https://vuldb.com/?ip.14.225.210.97) | static.vnpt.vn | - | High
2 | [14.225.210.98](https://vuldb.com/?ip.14.225.210.98) | static.vnpt.vn | - | High
3 | [14.225.210.209](https://vuldb.com/?ip.14.225.210.209) | static.vnpt.vn | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CoralRaider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CoralRaider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//etc/RT2870STA.dat` | High
2 | File | `/account/forgotpassword` | High
3 | File | `/add_user.php` | High
4 | File | `/admin/ajax.php` | High
5 | File | `/admin/all_users.php` | High
6 | File | `/admin/bookList?page=1&limit=10` | High
7 | File | `/admin/clients/` | High
8 | File | `/admin/config_ISCGroupNoCache.php` | High
9 | File | `/admin/create_product.php` | High
10 | File | `/admin/DatabaseQuery` | High
11 | File | `/admin/deleteroom.php` | High
12 | File | `/admin/edit_role.php` | High
13 | File | `/admin/fetch_product_details.php` | High
14 | File | `/admin/index.php/news/edit` | High
15 | File | `/admin/model/addOrUpdate` | High
16 | File | `/admin/order.php` | High
17 | File | `/admin/profile.php` | High
18 | File | `/admin/project/update/2` | High
19 | File | `/admin/salary_slip.php` | High
20 | File | `/admin/settings/index.php?page=accounts` | High
21 | File | `/admin/template/edit` | High
22 | File | `/adminapi/system/file/openfile` | High
23 | File | `/admin_ping.htm` | High
24 | File | `/ajax.php?action=delete_deductions` | High
25 | File | `/api/job/add/` | High
26 | File | `/api/login/auth` | High
27 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
28 | File | `/api/v2/categories` | High
29 | File | `/Attachment/fromImageUrl` | High
30 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
31 | File | `/backend/admin/his_admin_add_vendor.php` | High
32 | File | `/backend/admin/his_admin_register_patient.php` | High
33 | File | `/boafrm/formIPv6Addr` | High
34 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
35 | File | `/cgi-bin/cstecgi.cgi` | High
36 | File | `/cgi-bin/ExportIbmsConfig.sh` | High
37 | File | `/cgi-bin/luci/api/auth` | High
38 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
39 | File | `/cgi-bin/wlogin.cgi` | High
40 | File | `/changeimage1.php` | High
41 | File | `/chat/completions` | High
42 | File | `/CollatWebApp/gcmsRefInsert?name=SUPP` | High
43 | File | `/common/logViewer/logViewer.jsf` | High
44 | File | `/core/tools/add_translation.php` | High
45 | File | `/crm/weixinmp/index.php?userid=123&module=Users&usid=1&action=UsersAjax&minipro_const_type=1&related_module=Singin` | High
46 | File | `/department.php` | High
47 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
48 | File | `/DXR.axd` | Medium
49 | ... | ... | ...

There are 430 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/coralraider-targets-socialmedia-accounts/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
