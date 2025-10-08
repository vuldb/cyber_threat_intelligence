# TellYouThePass - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TellYouThePass](https://vuldb.com/?actor.tellyouthepass). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tellyouthepass](https://vuldb.com/?actor.tellyouthepass)

## Campaigns

The following _campaigns_ are known and can be associated with TellYouThePass:

* CVE-2024-4577

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TellYouThePass:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TellYouThePass.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.116.254.172](https://vuldb.com/?ip.14.116.254.172) | - | CVE-2024-4577 | High
2 | [14.225.53.162](https://vuldb.com/?ip.14.225.53.162) | static.vnpt.vn | CVE-2024-4577 | High
3 | [39.97.209.211](https://vuldb.com/?ip.39.97.209.211) | - | CVE-2024-4577 | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TellYouThePass_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TellYouThePass. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=route_ispinfo_export_save` | High
2 | File | `/?s=doudou&c=file&a=list` | High
3 | File | `/a/sys/user/save` | High
4 | File | `/admin-profile.php` | High
5 | File | `/admin.php` | Medium
6 | File | `/admin/?page=user/manage` | High
7 | File | `/admin/add-animals.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/ajax.php?action=delete_recruitment_status` | High
10 | File | `/admin/ajax.php?action=save_recruitment_status` | High
11 | File | `/admin/assign_save.php` | High
12 | File | `/admin/campsdetails.php` | High
13 | File | `/admin/category/controller.php` | High
14 | File | `/admin/category_update.php` | High
15 | File | `/admin/changepropic.php` | High
16 | File | `/admin/config_ISCGroupNoCache.php` | High
17 | File | `/admin/deduction_edit.php` | High
18 | File | `/admin/delete_s2.php` | High
19 | File | `/admin/delete_s3.php` | High
20 | File | `/admin/delete_s4.php` | High
21 | File | `/admin/delete_s5.php` | High
22 | File | `/admin/delete_s6.php` | High
23 | File | `/admin/del_feedback.php` | High
24 | File | `/admin/department/add` | High
25 | File | `/admin/doctors.php` | High
26 | File | `/admin/edit-admin.php` | High
27 | File | `/admin/edit-card-detail.php` | High
28 | File | `/admin/edit-class.php` | High
29 | File | `/admin/edit-doc.php` | High
30 | File | `/admin/edit_class.php` | High
31 | File | `/admin/edit_event.php` | High
32 | File | `/admin/edit_query_account.php` | High
33 | File | `/admin/fields/manage_field.php` | High
34 | File | `/admin/file/upload.do` | High
35 | File | `/admin/index.php` | High
36 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
37 | File | `/admin/inquiries/view_details.php` | High
38 | File | `/admin/login.php` | High
39 | File | `/admin/manage-card.php` | High
40 | File | `/Admin/NewsReport.php` | High
41 | File | `/admin/payment_save.php` | High
42 | File | `/admin/product.php` | High
43 | File | `/admin/team_update.php` | High
44 | File | `/admin/updatecomplaint.php` | High
45 | File | `/admin/update_s1.php` | High
46 | File | `/admin/update_s3.php` | High
47 | File | `/admin/update_s4.php` | High
48 | File | `/admin/update_s8.php` | High
49 | File | `/admin/users.php` | High
50 | File | `/admin/user_save.php` | High
51 | File | `/admin/user_update.php` | High
52 | File | `/ajax.php?action=delete_member` | High
53 | File | `/ajax.php?action=delete_user` | High
54 | File | `/ajax.php?action=save_deductions` | High
55 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
56 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
57 | File | `/Android/data/com.myairtelapp/files/` | High
58 | File | `/api/File/downloadFile` | High
59 | File | `/api/Image/WithPath` | High
60 | File | `/api/proxy` | Medium
61 | File | `/attendancelist.php` | High
62 | File | `/bin/mail` | Medium
63 | File | `/boafrm/formDMZ` | High
64 | File | `/boafrm/formFilter` | High
65 | File | `/boafrm/formMapDel` | High
66 | File | `/boafrm/formNtp` | High
67 | File | `/boafrm/formRoute` | High
68 | File | `/boafrm/formSaveConfig` | High
69 | File | `/boafrm/formWirelessTbl` | High
70 | File | `/BRS_top.html` | High
71 | File | `/business/common/sms/sendsms.jsp` | High
72 | File | `/categoryvalue.php` | High
73 | File | `/CDGServer3/workflowE/useractivate/updateorg.jsp` | High
74 | File | `/cgi-bin/cstecgi.cgi` | High
75 | File | `/cgi-bin/live_api.cgi` | High
76 | File | `/cgi-bin/luci/admin/opsw/Dual_freq_un_apple` | High
77 | ... | ... | ...

There are 674 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/cve-2024-4577-ongoing-exploitation-of-a-critical-php-vulnerability/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
