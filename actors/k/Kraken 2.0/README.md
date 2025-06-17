# Kraken 2.0 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kraken 2.0](https://vuldb.com/?actor.kraken_2.0). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kraken_2.0](https://vuldb.com/?actor.kraken_2.0)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kraken 2.0:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kraken 2.0.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kraken 2.0_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37, CWE-44, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kraken 2.0. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/add-property.php` | High
2 | File | `/admin/admin_editor.php` | High
3 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
4 | File | `/admin/ajax.php?action=login` | High
5 | File | `/admin/create_product.php` | High
6 | File | `/admin/DatabaseQuery` | High
7 | File | `/admin/edit-admin.php` | High
8 | File | `/admin/extensions/upload.php` | High
9 | File | `/admin/forgot-password.php` | High
10 | File | `/admin/index.php` | High
11 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
12 | File | `/admin/index2.html` | High
13 | File | `/admin/options-theme.php` | High
14 | File | `/admin/salary_slip.php` | High
15 | File | `/adminPage/conf/reload` | High
16 | File | `/adms/admin/?page=vehicles/view_transaction` | High
17 | File | `/api/` | Low
18 | File | `/api/client/editemedia.php` | High
19 | File | `/api/Common/uploadFile` | High
20 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
21 | File | `/api/runscript` | High
22 | File | `/api/snapshots/` | High
23 | File | `/api/v1/snapshots` | High
24 | File | `/api/v2/maps` | Medium
25 | File | `/api/wizard/setsyncpppoecfg` | High
26 | File | `/apply/index.php` | High
27 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
28 | File | `/candidate/index.php` | High
29 | File | `/cgi-bin/adm.cgi` | High
30 | File | `/cgi-bin/system_mgr.cgi` | High
31 | File | `/cgi-bin/wlogin.cgi` | High
32 | File | `/classes/SystemSettings.php?f=update_settings` | High
33 | File | `/cms/category/list` | High
34 | File | `/confirmbooking.php` | High
35 | File | `/core/config-revisions` | High
36 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
37 | File | `/endpoint/add-calorie.php` | High
38 | File | `/endpoint/add-timesheet.php` | High
39 | File | `/etc/init.d/update_notifications.sh` | High
40 | File | `/filemanager/upload` | High
41 | File | `/fladmin/user_recoverpwd.php` | High
42 | File | `/foms/routers/place-order.php` | High
43 | File | `/forum/away.php` | High
44 | File | `/geoserver/gwc/rest.html` | High
45 | File | `/goform/AdvSetWrl` | High
46 | File | `/goform/DhcpListClient` | High
47 | ... | ... | ...

There are 407 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
