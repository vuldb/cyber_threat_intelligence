# Handala - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Handala](https://vuldb.com/actor/handala). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/handala](https://vuldb.com/actor/handala)

## Campaigns

The following _campaigns_ are known and can be associated with Handala:

* ReutOne

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Handala:

* [US](https://vuldb.com/country/us)
* [IQ](https://vuldb.com/country/iq)
* [IL](https://vuldb.com/country/il)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Handala.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.57.35.223](https://vuldb.com/ip/31.57.35.223) | - | - | High
2 | [80.240.30.16](https://vuldb.com/ip/80.240.30.16) | 80.240.30.16.vultrusercontent.com | ReutOne | Medium
3 | [82.25.35.25](https://vuldb.com/ip/82.25.35.25) | - | - | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Handala_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Handala. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?page=tracks` | High
3 | File | `/Account/login.php` | High
4 | File | `/add_reference_to_local_model` | High
5 | File | `/admin` | Low
6 | File | `/admin-api/system/mail-log/page` | High
7 | File | `/admin/` | Low
8 | File | `/admin/ajax.php?action=delete_recruitment_status` | High
9 | File | `/admin/ajax.php?action=save_settings` | High
10 | File | `/admin/announcement/index.php?view=add` | High
11 | File | `/admin/article.php` | High
12 | File | `/admin/booking-search.php` | High
13 | File | `/admin/class.php` | High
14 | File | `/Admin/detail.php` | High
15 | File | `/admin/edit_categories.php` | High
16 | File | `/admin/index2.html` | High
17 | File | `/admin/inventory/manage_stock.php` | High
18 | File | `/admin/maintenance/view_designation.php` | High
19 | File | `/admin/manage-pages.php` | High
20 | File | `/admin/receipt.php` | High
21 | File | `/admin/reminders/manage_reminder.php` | High
22 | File | `/admin/student.php` | High
23 | File | `/admin/view-enquiry-detail.php` | High
24 | File | `/adminapi/system/file/openfile` | High
25 | File | `/adminSQL` | Medium
26 | File | `/ajax.php?action=delete_deductions` | High
27 | File | `/ajax.php?action=save_deductions` | High
28 | File | `/ajax.php?action=save_supplier` | High
29 | File | `/api.php` | Medium
30 | File | `/api.php?method=protectedMethod` | High
31 | File | `/api/ce/submit` | High
32 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
33 | File | `/api/v1/contenttype` | High
34 | File | `/api/v1/initialization/embedding/test` | High
35 | File | `/api/wizard/getsyncpppoecfg` | High
36 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
37 | File | `/bbdms/admin/update-contactinfo.php` | High
38 | File | `/bin/gpio` | Medium
39 | File | `/bin/httpd` | Medium
40 | File | `/boaform/formWlanSetup` | High
41 | File | `/boafrm/formIpQoS` | High
42 | File | `/boafrm/formSysCmd` | High
43 | File | `/boafrm/formWsc` | High
44 | File | `/cgi-bin/` | Medium
45 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
46 | File | `/cgi-bin/cstecgi.cgi` | High
47 | File | `/cgi-bin/kerbynet` | High
48 | File | `/cgi-bin/login.cgi` | High
49 | File | `/cgi-bin/webfile_mgr.cgi` | High
50 | File | `/cgi-bin/wlogin.cgi` | High
51 | File | `/chat/group/send` | High
52 | File | `/check_student.php` | High
53 | File | `/classes/Master.php?f=delete_category` | High
54 | File | `/classes/Master.php?f=delete_payment` | High
55 | File | `/classes/SystemSettings.php?f=update_settings` | High
56 | File | `/ClickAndBanexDemo/admin/admin_dblayers.asp` | High
57 | File | `/crm/contact/transfer` | High
58 | File | `/crm/weixinmp/index.php?userid=123&module=Users&usid=1&action=UsersAjax&minipro_const_type=1&related_module=Singin` | High
59 | File | `/customer_add_action.php` | High
60 | File | `/Digital-Infrastructure-9.6.7/y9-digitalbase-webapp/y9-module-filemanager/risenet-y9boot-webapp-filemanager/src/main/java/net/risesoft/y9public/controller/Y9FileController.java` | High
61 | File | `/doctor/deleteappointment.php` | High
62 | File | `/DXR.axd` | Medium
63 | File | `/e3api/api/main/ToJsonByControlName` | High
64 | File | `/endpoint/delete-bookmark.php` | High
65 | File | `/etc/quagga` | Medium
66 | File | `/etc/shadow` | Medium
67 | File | `/form/order.php` | High
68 | File | `/function/edit_customer.php` | High
69 | File | `/goform/APSecurity` | High
70 | File | `/goform/formSetPortTr` | High
71 | File | `/goform/SafeClientFilter` | High
72 | File | `/goform/setcfm` | High
73 | File | `/goform/set_blacklist` | High
74 | File | `/goform/VirtualSer` | High
75 | ... | ... | ...

There are 657 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://doublepulsar.com/handala-attempts-a-supply-chain-hack-via-reutone-001aa3cc684f
* https://research.checkpoint.com/2026/handala-hack-unveiling-groups-modus-operandi/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
