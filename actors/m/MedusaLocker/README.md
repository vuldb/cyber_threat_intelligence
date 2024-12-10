# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [IT](https://vuldb.com/?country.it)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MedusaLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.29.17.1](https://vuldb.com/?ip.3.29.17.1) | ec2-3-29-17-1.me-central-1.compute.amazonaws.com | - | Medium
2 | [40.92.90.105](https://vuldb.com/?ip.40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | - | High
3 | [45.146.164.141](https://vuldb.com/?ip.45.146.164.141) | - | - | High
4 | [50.80.219.149](https://vuldb.com/?ip.50.80.219.149) | 50-80-219-149.client.mchsi.com | - | High
5 | [84.38.189.52](https://vuldb.com/?ip.84.38.189.52) | wmw10.empresagozalez.miami | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MedusaLocker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reserve` | High
2 | File | `/?page=tickets` | High
3 | File | `/?page=tracks` | High
4 | File | `/abcd/opac/php/otros_sitios.php` | High
5 | File | `/abs.php` | Medium
6 | File | `/Actions.php?a=login` | High
7 | File | `/addcustind.php` | High
8 | File | `/addstock.php` | High
9 | File | `/add_new_purchase.php?action=is_supplier` | High
10 | File | `/add_new_supplier.php` | High
11 | File | `/admin.php?m=Acquisi&a=testcj&lid=1` | High
12 | File | `/admin/` | Low
13 | File | `/admin/?page=inventory/view_inventory&id=2` | High
14 | File | `/admin/?page=products/view_product` | High
15 | File | `/admin/?page=reports` | High
16 | File | `/Admin/add-admin.php` | High
17 | File | `/admin/add-doctor.php` | High
18 | File | `/admin/apply.php` | High
19 | File | `/admin/blood/update/B+.php` | High
20 | File | `/admin/blood/update/B-.php` | High
21 | File | `/admin/blood/update/o-.php` | High
22 | File | `/admin/book-details.php` | High
23 | File | `/admin/bwdates-report-details.php` | High
24 | File | `/admin/campsdetails.php` | High
25 | File | `/admin/categories/manage_category.php` | High
26 | File | `/admin/change-image.php` | High
27 | File | `/admin/create-package.php` | High
28 | File | `/admin/edit-brand.php` | High
29 | File | `/admin/edit-card-detail.php` | High
30 | File | `/admin/edit-subadmin.php` | High
31 | File | `/admin/edit_area.php` | High
32 | File | `/admin/edit_customer.php` | High
33 | File | `/admin/edit_fuel.php` | High
34 | File | `/admin/edit_manufacturer.php` | High
35 | File | `/admin/educloud/videobind.html` | High
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
48 | File | `/admin/robot.php` | High
49 | File | `/admin/search-medicalcard.php` | High
50 | File | `/admin/search-vehicle.php` | High
51 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
52 | File | `/admin/tag.php` | High
53 | File | `/admin/template/edit` | High
54 | File | `/admin/template/update` | High
55 | File | `/admin/user/user-move-run.php` | High
56 | File | `/admin/view-card-detail.php` | High
57 | File | `/admin/view-enquiry.php` | High
58 | File | `/ajax.php?action=delete_deductions` | High
59 | File | `/ajax.php?action=delete_tenant` | High
60 | File | `/ajax.php?action=save_category` | High
61 | File | `/ajax.php?action=signup` | High
62 | File | `/ajax.php?action=update_account` | High
63 | File | `/animalsadd.php` | High
64 | File | `/animalsupdate.php` | High
65 | File | `/api/files/recipepictures/` | High
66 | File | `/app/action/add_staff.php` | High
67 | File | `/app/admin/controller/file/File.php` | High
68 | File | `/apply/index.php` | High
69 | File | `/bloodrequest.php` | High
70 | ... | ... | ...

There are 610 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.bleepingcomputer.com/news/security/medusalocker-ransomware-wants-its-share-of-your-money/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
