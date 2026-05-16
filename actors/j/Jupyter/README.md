# Jupyter - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Jupyter](https://vuldb.com/?actor.jupyter). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.jupyter](https://vuldb.com/?actor.jupyter)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Jupyter:

* [US](https://vuldb.com/?country.us)
* [CA](https://vuldb.com/?country.ca)
* [DE](https://vuldb.com/?country.de)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Jupyter.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.254.118.226](https://vuldb.com/?ip.5.254.118.226) | - | - | High
2 | [23.29.115.175](https://vuldb.com/?ip.23.29.115.175) | 23-29-115-175.static.hvvc.us | - | High
3 | [37.120.237.251](https://vuldb.com/?ip.37.120.237.251) | - | - | High
4 | [37.120.247.199](https://vuldb.com/?ip.37.120.247.199) | - | - | High
5 | [37.221.113.115](https://vuldb.com/?ip.37.221.113.115) | - | - | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Jupyter_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Jupyter. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/actuator` | Medium
2 | File | `/addProduct.php` | High
3 | File | `/add_librarian.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/activity.php` | High
6 | File | `/admin/add-subadmins.php` | High
7 | File | `/Admin/additems.php` | High
8 | File | `/admin/add_area.php` | High
9 | File | `/admin/add_payroll.php` | High
10 | File | `/admin/candidates_edit.php` | High
11 | File | `/admin/cms/material/add` | High
12 | File | `/Admin/delete-fee.php` | High
13 | File | `/admin/delete_activity.php` | High
14 | File | `/admin/editsite.php` | High
15 | File | `/admin/edit_activity_query.php` | High
16 | File | `/admin/expenses.php` | High
17 | File | `/admin/invoices.php` | High
18 | File | `/admin/login.php` | High
19 | File | `/admin/login_query.php` | High
20 | File | `/admin/modules/lesson/index.php` | High
21 | File | `/admin/products/index.php?view=add` | High
22 | File | `/admin/quesadd.php` | High
23 | File | `/admin/school_year.php` | High
24 | File | `/admin/system/variableList.do` | High
25 | File | `/admin/system/variableSave.do` | High
26 | File | `/admin/user-bookings.php` | High
27 | File | `/admin/user-search.php` | High
28 | File | `/administrator/addcategory.php` | High
29 | File | `/Administrator/PHP/AdminAddUser.php` | High
30 | File | `/Administrator/PHP/AdminViewSongs.php` | High
31 | File | `/adminLogin.php` | High
32 | File | `/admin_delete.php` | High
33 | File | `/ajax.php?action=login` | High
34 | File | `/api/GylOperator/UpdatePasswordBatch` | High
35 | File | `/api/jobs` | Medium
36 | File | `/app/checkout/delete.php` | High
37 | File | `/app/checkout/update.php` | High
38 | File | `/app/complaint.php` | High
39 | File | `/app/Jobs/Util/Import.php` | High
40 | File | `/app/register.php?action=reg` | High
41 | File | `/base/safe_setting/` | High
42 | File | `/binutils/debug.c` | High
43 | File | `/blog/bContent/save` | High
44 | File | `/boafrm/formWsc` | High
45 | File | `/c6/Jhsoft.Web.module/ToolBar/GetWordFileName.aspx/?text=GetUrl&style=add` | High
46 | File | `/cart/update/attr` | High
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/imode_alldata.php` | High
49 | File | `/check_student.php` | High
50 | File | `/chkuser.php` | Medium
51 | File | `/contact_us.php` | High
52 | File | `/controller/api/hotelList.php` | High
53 | File | `/controller/api/Room.php` | High
54 | File | `/customer_details.php` | High
55 | File | `/data/pbootcms.db` | High
56 | File | `/dayrui/Fcms/Init.php` | High
57 | File | `/dev-api/common/upload` | High
58 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
59 | ... | ... | ...

There are 514 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.morphisec.com/new-jupyter-evasive-delivery-through-msi-installer
* https://blogs.blackberry.com/en/2022/01/threat-thursday-jupyter-infostealer-is-a-master-of-disguise
* https://community.blueliv.com/#!/s/62551fc782df417ed0330c79

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
