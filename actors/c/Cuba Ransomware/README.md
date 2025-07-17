# Cuba Ransomware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cuba Ransomware](https://vuldb.com/?actor.cuba_ransomware). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cuba_ransomware](https://vuldb.com/?actor.cuba_ransomware)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cuba Ransomware:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cuba Ransomware.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.13.102.1](https://vuldb.com/?ip.10.13.102.1) | - | - | High
2 | [10.13.102.58](https://vuldb.com/?ip.10.13.102.58) | - | - | High
3 | [10.14.100.20](https://vuldb.com/?ip.10.14.100.20) | - | - | High
4 | [10.133.78.41](https://vuldb.com/?ip.10.133.78.41) | - | - | High
5 | [23.160.193.145](https://vuldb.com/?ip.23.160.193.145) | server1.wlook.com | - | High
6 | [23.227.198.246](https://vuldb.com/?ip.23.227.198.246) | 23-227-198-246.static.hvvc.us | - | High
7 | [31.44.184.84](https://vuldb.com/?ip.31.44.184.84) | - | - | High
8 | [31.44.184.100](https://vuldb.com/?ip.31.44.184.100) | - | - | High
9 | [31.184.192.44](https://vuldb.com/?ip.31.184.192.44) | - | - | High
10 | [31.184.194.42](https://vuldb.com/?ip.31.184.194.42) | - | - | High
11 | [31.184.198.74](https://vuldb.com/?ip.31.184.198.74) | - | - | High
12 | [31.184.198.80](https://vuldb.com/?ip.31.184.198.80) | directingme.com | - | High
13 | [31.184.198.82](https://vuldb.com/?ip.31.184.198.82) | harms.directingme.com | - | High
14 | [31.184.198.83](https://vuldb.com/?ip.31.184.198.83) | - | - | High
15 | [31.184.198.84](https://vuldb.com/?ip.31.184.198.84) | - | - | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cuba Ransomware_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-273, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cuba Ransomware. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/accounts_con/register_account` | High
3 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
4 | File | `/admin/add-doctor.php` | High
5 | File | `/admin/addproduct.php` | High
6 | File | `/admin/book_row.php` | High
7 | File | `/admin/budget.php` | High
8 | File | `/admin/config_save.php` | High
9 | File | `/admin/contactus.php` | High
10 | File | `/admin/download_frame.php` | High
11 | File | `/admin/file/delete.do` | High
12 | File | `/admin/forgot-password.php` | High
13 | File | `/admin/index3.php` | High
14 | File | `/admin/leancloud.php` | High
15 | File | `/admin/manage_user.php` | High
16 | File | `/admin/newsletter1.php` | High
17 | File | `/admin/overtime_add.php` | High
18 | File | `/admin/robot/approval/list` | High
19 | File | `/admin/student.php` | High
20 | File | `/admin/students.php` | High
21 | File | `/admin/update-clients.php` | High
22 | File | `/AJAX/ajaxget` | High
23 | File | `/api/contents` | High
24 | File | `/api/wechat/app_auth` | High
25 | File | `/app/form_add/of` | High
26 | File | `/blog/comment` | High
27 | File | `/boaform/device_reset.cgi` | High
28 | File | `/boafrm/formReflashClientTbl` | High
29 | File | `/boafrm/formWsc` | High
30 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
31 | File | `/carbon/mediation_secure_vault/properties/ajaxprocessor.jsp` | High
32 | File | `/catcompany.php` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/koha/catalogue/search.pl` | High
35 | File | `/cgi-bin/nas_sharing.cgi` | High
36 | File | `/cgi-bin/touchlist_sync.cgi` | High
37 | File | `/ci_hms/search` | High
38 | File | `/classes/Master.php?f=save_service` | High
39 | File | `/classes/Users.php` | High
40 | File | `/cwms/admin/?page=articles/view_article/` | High
41 | File | `/doorgets/app/requests/user/configurationRequest.php` | High
42 | File | `/ebics-server/ebics.aspx` | High
43 | File | `/ecommerce/support_ticket` | High
44 | File | `/Employee/delete_leave.php` | High
45 | File | `/etc/services/INET/inet_ipv4.php` | High
46 | File | `/garage/editclient.php` | High
47 | File | `/goform/delIpMacBind/` | High
48 | File | `/goform/DhcpSetSer` | High
49 | File | `/goform/execCommand` | High
50 | File | `/goform/formLogDnsquery` | High
51 | File | `/goform/RgDhcp` | High
52 | File | `/goform/setcfm` | High
53 | File | `/goform/setDeviceSettings` | High
54 | File | `/goform/SetNetControlList/` | High
55 | File | `/goform/setpptpservercfg` | High
56 | File | `/goform/SetSysAutoRebbotCfg` | High
57 | File | `/goform/SetSysTimeCfg` | High
58 | File | `/goform/WifiExtraSet` | High
59 | File | `/inc/jquery/uploadify/uploadify.php` | High
60 | File | `/index.php` | Medium
61 | File | `/index.php?app=main&inc=feature_phonebook&op=phonebook_list` | High
62 | File | `/index/user/user_edit.html` | High
63 | File | `/interview/editQuestion.php` | High
64 | ... | ... | ...

There are 562 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/cuba-ransomware/110533/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-335a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
