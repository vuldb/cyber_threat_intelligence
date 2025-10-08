# Loda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Loda](https://vuldb.com/?actor.loda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.loda](https://vuldb.com/?actor.loda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Loda:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [SH](https://vuldb.com/?country.sh)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Loda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.188](https://vuldb.com/?ip.2.58.56.188) | powered.by.rdp.sh | - | High
2 | [3.141.204.47](https://vuldb.com/?ip.3.141.204.47) | ec2-3-141-204-47.us-east-2.compute.amazonaws.com | - | Medium
3 | [13.40.105.36](https://vuldb.com/?ip.13.40.105.36) | ec2-13-40-105-36.eu-west-2.compute.amazonaws.com | - | Medium
4 | [16.170.93.15](https://vuldb.com/?ip.16.170.93.15) | ec2-16-170-93-15.eu-north-1.compute.amazonaws.com | - | Medium
5 | [34.174.95.150](https://vuldb.com/?ip.34.174.95.150) | 150.95.174.34.bc.googleusercontent.com | - | Medium
6 | [37.0.14.214](https://vuldb.com/?ip.37.0.14.214) | - | - | High
7 | [45.155.249.183](https://vuldb.com/?ip.45.155.249.183) | - | - | High
8 | [46.105.113.84](https://vuldb.com/?ip.46.105.113.84) | ns320209.ip-46-105-113.eu | - | High
9 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Loda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Loda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/;/admin/role/edit` | High
3 | File | `/?p=products` | Medium
4 | File | `/add_achievement_details.php` | High
5 | File | `/admin/action/edit_chicken.php` | High
6 | File | `/admin/add-class.php` | High
7 | File | `/admin/archives/edit` | High
8 | File | `/admin/booking-bwdates-reports-details.php` | High
9 | File | `/admin/change_pass.php` | High
10 | File | `/admin/chart1.php` | High
11 | File | `/admin/contact-us.php` | High
12 | File | `/Admin/createClass.php` | High
13 | File | `/admin/deleteBooking.php` | High
14 | File | `/admin/edit-course.php` | High
15 | File | `/admin/faculty_action.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/lastthirtyays-reg-users.php` | High
18 | File | `/admin/login.php` | High
19 | File | `/admin/modal_add_product.php` | High
20 | File | `/admin/pages/update_go.php` | High
21 | File | `/admin/pass-details.php` | High
22 | File | `/admin/print.php` | High
23 | File | `/admin/readenq.php` | High
24 | File | `/admin/report.php` | High
25 | File | `/admin/search-maid.php` | High
26 | File | `/admin/submit_page.php` | High
27 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
28 | File | `/admin/tag/save` | High
29 | File | `/admin/update_user.php` | High
30 | File | `/admin/upload` | High
31 | File | `/admin/view-user-queries.php` | High
32 | File | `/admin/visitors-form.php` | High
33 | File | `/adminsys/index.php?load=admins&act=edit_info&act_type=add` | High
34 | File | `/ajax/check_medicine_name.php` | High
35 | File | `/api/front/search/books` | High
36 | File | `/api/wizard/setsyncpppoecfg` | High
37 | File | `/app/api/controller/collect.php` | High
38 | File | `/apply/index.php` | High
39 | File | `/auth/userkey/logout.php` | High
40 | File | `/backend/admin/his_admin_register_patient.php` | High
41 | File | `/bin/httpd` | Medium
42 | File | `/birthing.php` | High
43 | File | `/blog-details.php` | High
44 | File | `/boafrm/formParentControl` | High
45 | File | `/boafrm/formStats` | High
46 | File | `/boafrm/formSysLog` | High
47 | File | `/book-nurse.php?bookid=1` | High
48 | File | `/book-services.php` | High
49 | File | `/book/searchByPage` | High
50 | File | `/book_list.php` | High
51 | File | `/bwdates-report-result.php` | High
52 | File | `/bwdates-reports.php` | High
53 | File | `/catalog/all-products` | High
54 | File | `/cgi-bin/cstecgi.cgi` | High
55 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
56 | File | `/cgi-bin/ipfedr.cgi` | High
57 | File | `/cgi-bin/nas_sharing.cgi` | High
58 | File | `/cgi-bin/photocenter_mgr.cgi` | High
59 | File | `/cgi-bin/wlogin.cgi` | High
60 | File | `/check_availability.php` | High
61 | File | `/class/edit/edit` | High
62 | File | `/classes/Master.php?f=delete_reservation` | High
63 | File | `/collect/PortV4/downLoad.html` | High
64 | File | `/control/deactivate_case.php` | High
65 | File | `/crm/inicio.php` | High
66 | File | `/customer_support/index.php?page=customer_list` | High
67 | File | `/dashboard/admin/del_member.php` | High
68 | ... | ... | ...

There are 598 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
