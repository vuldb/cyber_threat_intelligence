# Valyria - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Valyria](https://vuldb.com/?actor.valyria). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.valyria](https://vuldb.com/?actor.valyria)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Valyria:

* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Valyria.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.248.159.254](https://vuldb.com/?ip.8.248.159.254) | - | - | High
2 | [8.249.221.254](https://vuldb.com/?ip.8.249.221.254) | - | - | High
3 | [8.253.45.248](https://vuldb.com/?ip.8.253.45.248) | - | - | High
4 | [8.253.131.111](https://vuldb.com/?ip.8.253.131.111) | - | - | High
5 | [12.139.45.113](https://vuldb.com/?ip.12.139.45.113) | - | - | High
6 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
7 | [45.60.22.20](https://vuldb.com/?ip.45.60.22.20) | - | - | High
8 | [50.62.26.129](https://vuldb.com/?ip.50.62.26.129) | ip-50-62-26-129.ip.secureserver.net | - | High
9 | [54.164.54.19](https://vuldb.com/?ip.54.164.54.19) | ec2-54-164-54-19.compute-1.amazonaws.com | - | Medium
10 | [64.185.227.155](https://vuldb.com/?ip.64.185.227.155) | 64-185-227-155.static.webnx.com | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Valyria_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Valyria. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/?page=tracks` | High
4 | File | `/abcd/opac/php/otros_sitios.php` | High
5 | File | `/abs.php` | Medium
6 | File | `/Actions.php?a=login` | High
7 | File | `/add_new_purchase.php?action=is_supplier` | High
8 | File | `/add_new_supplier.php` | High
9 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
10 | File | `/admin/` | Low
11 | File | `/admin/?page=inventory/view_inventory&id=2` | High
12 | File | `/admin/?page=products/view_product` | High
13 | File | `/admin/?page=reports` | High
14 | File | `/admin/about_edit.php?action=modify` | High
15 | File | `/Admin/add-admin.php` | High
16 | File | `/admin/add-doctor.php` | High
17 | File | `/admin/apply.php` | High
18 | File | `/admin/blood/update/B+.php` | High
19 | File | `/admin/blood/update/B-.php` | High
20 | File | `/admin/blood/update/o-.php` | High
21 | File | `/admin/book-details.php` | High
22 | File | `/admin/bwdates-report-details.php` | High
23 | File | `/admin/campsdetails.php` | High
24 | File | `/admin/categories/manage_category.php` | High
25 | File | `/admin/change-image.php` | High
26 | File | `/admin/class.php?dowhat=modifyclass` | High
27 | File | `/admin/create-package.php` | High
28 | File | `/admin/edit-brand.php` | High
29 | File | `/admin/edit-card-detail.php` | High
30 | File | `/admin/edit-subadmin.php` | High
31 | File | `/admin/edit_area.php` | High
32 | File | `/admin/edit_fuel.php` | High
33 | File | `/admin/edit_manufacturer.php` | High
34 | File | `/admin/educloud/videobind.html` | High
35 | File | `/admin/emp-profile-avatar.php` | High
36 | File | `/admin/File/fileUpload` | High
37 | File | `/admin/File/pictureUpload` | High
38 | File | `/admin/home.php` | High
39 | File | `/admin/index.php` | High
40 | File | `/admin/inquiries/view_details.php` | High
41 | File | `/admin/login.php` | High
42 | File | `/admin/maintenance/manage_department.php` | High
43 | File | `/admin/massage.php` | High
44 | File | `/admin/overtime_add.php` | High
45 | File | `/admin/overtime_row.php` | High
46 | File | `/admin/password-recovery.php` | High
47 | File | `/admin/profile.php` | High
48 | File | `/Admin/registration.php` | High
49 | File | `/admin/robot.php` | High
50 | File | `/admin/search-medicalcard.php` | High
51 | File | `/admin/search-vehicle.php` | High
52 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
53 | File | `/admin/tag.php` | High
54 | File | `/admin/template/edit` | High
55 | File | `/admin/template/update` | High
56 | File | `/admin/user/user-move-run.php` | High
57 | File | `/admin/view-card-detail.php` | High
58 | File | `/admin/view-enquiry.php` | High
59 | File | `/ajax.php?action=delete_deductions` | High
60 | File | `/ajax.php?action=save_category` | High
61 | File | `/ajax.php?action=signup` | High
62 | File | `/ajax.php?action=update_account` | High
63 | File | `/ajax/checkin.php` | High
64 | File | `/ajax/chpwd.php` | High
65 | File | `/ajax/getBasicInfo.php` | High
66 | File | `/animalsadd.php` | High
67 | File | `/api/config/list` | High
68 | File | `/api/files/recipepictures/` | High
69 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
70 | File | `/api/system/user?deptId=1&page=1&size=10` | High
71 | File | `/app/action/add_staff.php` | High
72 | File | `/app/admin/controller/file/File.php` | High
73 | File | `/apply/index.php` | High
74 | File | `/bloodrequest.php` | High
75 | File | `/buscar_integrada.php` | High
76 | File | `/cap.js` | Low
77 | File | `/CDGServer3/document/Catelogs;logindojojs?command=DelCatelogs` | High
78 | File | `/cgi-bin/apkg_mgr.cgi` | High
79 | File | `/cgi-bin/cstecgi.cgi` | High
80 | File | `/cgi-bin/hd_config.cgi` | High
81 | ... | ... | ...

There are 716 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-0928-1005.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-1005-1012.html
* https://blog.talosintelligence.com/2018/12/threat-roundup-1214-1221.html
* https://blog.talosintelligence.com/2019/01/threat-roundup-0118-0125.html
* https://blog.talosintelligence.com/2019/02/threat-roundup-0208-0215.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0221-0228.html
* https://blog.talosintelligence.com/2020/10/threat-roundup-0925-1002.html
* https://blog.talosintelligence.com/threat-roundup-0505-0512-3/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
