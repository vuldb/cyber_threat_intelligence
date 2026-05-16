# Loda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Loda](https://vuldb.com/?actor.loda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.loda](https://vuldb.com/?actor.loda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Loda:

* [VN](https://vuldb.com/?country.vn)
* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Loda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.188](https://vuldb.com/?ip.2.58.56.188) | powered.by.rdp.sh | - | High
2 | [3.141.204.47](https://vuldb.com/?ip.3.141.204.47) | ec2-3-141-204-47.us-east-2.compute.amazonaws.com | - | Medium
3 | [5.241.95.104](https://vuldb.com/?ip.5.241.95.104) | m5-240-95-104.cust.tele2.lv | - | High
4 | [13.40.105.36](https://vuldb.com/?ip.13.40.105.36) | ec2-13-40-105-36.eu-west-2.compute.amazonaws.com | - | Medium
5 | [16.170.93.15](https://vuldb.com/?ip.16.170.93.15) | ec2-16-170-93-15.eu-north-1.compute.amazonaws.com | - | Medium
6 | [34.174.95.150](https://vuldb.com/?ip.34.174.95.150) | 150.95.174.34.bc.googleusercontent.com | - | Medium
7 | [37.0.14.214](https://vuldb.com/?ip.37.0.14.214) | - | - | High
8 | [45.155.249.183](https://vuldb.com/?ip.45.155.249.183) | - | - | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Loda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Loda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/add-pass.php` | High
3 | File | `/addcompany.php` | High
4 | File | `/add_new_purchase.php?action=is_supplier` | High
5 | File | `/admin-api/bpm/model/deploy` | High
6 | File | `/admin-cp/theme/editor/default` | High
7 | File | `/admin-profile.php` | High
8 | File | `/admin/aboutus.php` | High
9 | File | `/admin/actions/remove-announcement.php` | High
10 | File | `/Admin/add-admin.php` | High
11 | File | `/Admin/additems.php` | High
12 | File | `/admin/add_candidate_modal.php.` | High
13 | File | `/admin/admin-profile.php` | High
14 | File | `/admin/admin_feature.php` | High
15 | File | `/admin/archives_add.php` | High
16 | File | `/admin/betweendates-detailsreports.php` | High
17 | File | `/admin/bwdates-reports-details.php` | High
18 | File | `/admin/candidates_add.php` | High
19 | File | `/admin/comment/list` | High
20 | File | `/admin/contact-us.php` | High
21 | File | `/admin/controller/delete_group_student.php` | High
22 | File | `/Admin/createClass.php` | High
23 | File | `/admin/deleteBooking.php` | High
24 | File | `/admin/deleteroom.php` | High
25 | File | `/admin/edit-equipmentform.php` | High
26 | File | `/admin/edit-subadmin.php` | High
27 | File | `/admin/edit_room.php` | High
28 | File | `/admin/edit_teacher.php` | High
29 | File | `/admin/fields/manage_field.php` | High
30 | File | `/admin/freelist_main.php` | High
31 | File | `/Admin/gametype.php` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/index.php?language=en&nv=upload` | High
34 | File | `/Admin/InsertCategory.php` | High
35 | File | `/admin/lastthirtyays-reg-users.php` | High
36 | File | `/admin/login.php` | High
37 | File | `/admin/manage-art-medium.php` | High
38 | File | `/admin/manage-category.php` | High
39 | File | `/admin/manage-pages.php` | High
40 | File | `/admin/operation/user.php` | High
41 | File | `/admin/operations/expense.php` | High
42 | File | `/admin/profile.php` | High
43 | File | `/admin/room.php` | High
44 | File | `/admin/roomdel.php` | High
45 | File | `/admin/update-profile.php` | High
46 | File | `/admin/updatestudent.php` | High
47 | File | `/admin/view-appointment.php` | High
48 | File | `/admin/view-progress-report.php` | High
49 | File | `/admin/view_products.php` | High
50 | File | `/administrator` | High
51 | File | `/Administrator/PHP/AdminEditUser.php` | High
52 | File | `/adminsys/index.php?load=admins&act=edit_info&act_type=add` | High
53 | File | `/admin_class.php` | High
54 | File | `/ajax.php?action=save_course` | High
55 | File | `/api/areacliente/pessoa/validarCpf` | High
56 | File | `/api/config/list` | High
57 | File | `/api/wizard/networkSetup` | High
58 | File | `/app/api/controller/collect.php` | High
59 | File | `/app/register.php?action=reg` | High
60 | File | `/application/common.php` | High
61 | File | `/application/controller/Transaki.php` | High
62 | File | `/application/index/controller/Icon.php` | High
63 | File | `/APR/login.php` | High
64 | File | `/att_add.php` | Medium
65 | File | `/backend/admin/his_admin_register_patient.php` | High
66 | File | `/boafrm/formFirewallAdv` | High
67 | File | `/boafrm/formLtefotaUpgradeFibocom` | High
68 | File | `/boafrm/formStats` | High
69 | File | `/boafrm/formSysCmd` | High
70 | File | `/boafrm/fromStaticDHCP` | High
71 | File | `/c6/Jhsoft.Web.module/ToolBar/ManageWord.aspx/?text=GetUrl&style=1` | High
72 | File | `/C6/JHSoft.Web.NetDisk/NetDiskProperty.aspx` | High
73 | File | `/cart.php` | Medium
74 | File | `/cart2.php` | Medium
75 | File | `/category.php` | High
76 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
77 | File | `/cgi-bin/api.values.post` | High
78 | File | `/cgi-bin/cstecgi.cgi` | High
79 | File | `/cgi-bin/DownloadLog` | High
80 | File | `/cgi-bin/firewall.cgi` | High
81 | ... | ... | ...

There are 718 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/0370524d-75ee-4ea2-ad99-01e40a8d6b4a
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/11/get-a-loda-this.txt
* https://github.com/rapid7/Rapid7-Labs/blob/main/IOCs/LodaRat/IOC's.txt
* https://threatfox.abuse.ch
* https://www.virustotal.com/gui/file/052fba70767b01cb674b9311a220181a87bdf47161280bb6335c6024e163139c/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
