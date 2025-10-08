# TA866 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA866](https://vuldb.com/?actor.ta866). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta866](https://vuldb.com/?actor.ta866)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA866:

* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA866.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.192.63.13](https://vuldb.com/?ip.5.192.63.13) | - | - | High
2 | [5.192.63.126](https://vuldb.com/?ip.5.192.63.126) | - | - | High
3 | [6.151.25.15](https://vuldb.com/?ip.6.151.25.15) | - | - | High
4 | [8.210.10.62](https://vuldb.com/?ip.8.210.10.62) | - | - | High
5 | [12.113.6.27](https://vuldb.com/?ip.12.113.6.27) | - | - | High
6 | [15.225.200.157](https://vuldb.com/?ip.15.225.200.157) | - | - | High
7 | [18.225.200.157](https://vuldb.com/?ip.18.225.200.157) | ec2-18-225-200-157.us-east-2.compute.amazonaws.com | - | Medium
8 | [21.113.106.27](https://vuldb.com/?ip.21.113.106.27) | - | - | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA866_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-35, CWE-37 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA866. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//index.php` | Medium
2 | File | `/adm/index.php` | High
3 | File | `/admin` | Low
4 | File | `/admin-cp/plugin/install` | High
5 | File | `/admin-profile.php` | High
6 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
7 | File | `/admin/aboutus.php` | High
8 | File | `/admin/add-teacher.php` | High
9 | File | `/admin/addadvertisement.php` | High
10 | File | `/admin/addroom.php` | High
11 | File | `/admin/admin_login.php` | High
12 | File | `/Admin/akun_edit.php` | High
13 | File | `/admin/bwdates-reports-details.php` | High
14 | File | `/admin/changeimage.php` | High
15 | File | `/Admin/changepassword.php` | High
16 | File | `/admin/doAdminAction.php?act=delCate&id=31` | High
17 | File | `/admin/edit-category-detail.php` | High
18 | File | `/admin/edit-teacher-detail.php` | High
19 | File | `/admin/edit_area.php` | High
20 | File | `/admin/edit_page.php?link_id=1` | High
21 | File | `/admin/fetch_product_details.php` | High
22 | File | `/admin/filemanager/connector/` | High
23 | File | `/admin/level.php` | High
24 | File | `/admin/list_onlineuser.php` | High
25 | File | `/admin/manage-nurse.php` | High
26 | File | `/admin/password-recovery.php` | High
27 | File | `/admin/products/index.php` | High
28 | File | `/admin/sys/user/list` | High
29 | File | `/admin/view-patient.php` | High
30 | File | `/admin/viewpackage.php` | High
31 | File | `/administrator` | High
32 | File | `/admin_type.php` | High
33 | File | `/adv_dhcps.php` | High
34 | File | `/ajax.php?action=save_plan` | High
35 | File | `/ajax/getBasicInfo.php` | High
36 | File | `/api/dept` | Medium
37 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
38 | File | `/App/Core/Extend/Function/ydLib.php` | High
39 | File | `/appointment-history.php` | High
40 | File | `/author/list?limit=10&offset=0&order=desc` | High
41 | File | `/billing/pms_check.php` | High
42 | File | `/birthing_print.php` | High
43 | File | `/boafrm/formMapDel` | High
44 | File | `/boafrm/formMapReboot` | High
45 | File | `/boafrm/formMultiAP` | High
46 | File | `/boafrm/formPortFw` | High
47 | File | `/boafrm/formSetLg` | High
48 | File | `/boat-details.php` | High
49 | File | `/bwdates-reports-details.php` | High
50 | File | `/catalog/all-products` | High
51 | File | `/ccm/system/dialogs/file/delete/1/submit` | High
52 | File | `/cgi-bin/cstecgi.cgi` | High
53 | File | `/cgi-bin/login_action.cgi` | High
54 | File | `/cgi-bin/main.cgi` | High
55 | File | `/cgi-bin/sysconf.cgi` | High
56 | File | `/change-password.php` | High
57 | File | `/change_s_pwd.php` | High
58 | File | `/classes/Master.php?f=delete_category` | High
59 | File | `/contact.php` | Medium
60 | File | `/control/player?center&eventlist&pda&dummy_for_reload=1736177631&p_evt` | High
61 | ... | ... | ...

There are 529 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/highlighting-ta866-asylum-ambuscade/
* https://github.com/Cisco-Talos/IOCs/blob/main/2024/10/highlighting-ta866-asylum-ambuscade.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
