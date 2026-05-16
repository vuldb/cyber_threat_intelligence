# Amazon AWS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Amazon AWS_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Amazon AWS:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [DE](https://vuldb.com/?country.de)
* ...

There are 20 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Amazon AWS or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Amazon AWS.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [2.58.150.54](https://vuldb.com/?ip.2.58.150.54) | mta-15054.mail.members.Y3GJIj6l6jdzv.com | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [3.87.88.196](https://vuldb.com/?ip.3.87.88.196) | ec2-3-87-88-196.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
3 | [3.92.161.20](https://vuldb.com/?ip.3.92.161.20) | ec2-3-92-161-20.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
4 | [3.120.207.231](https://vuldb.com/?ip.3.120.207.231) | ec2-3-120-207-231.eu-central-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
5 | [3.134.110.223](https://vuldb.com/?ip.3.134.110.223) | ec2-3-134-110-223.us-east-2.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
6 | [3.143.228.87](https://vuldb.com/?ip.3.143.228.87) | ec2-3-143-228-87.us-east-2.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
7 | [3.230.173.139](https://vuldb.com/?ip.3.230.173.139) | ec2-3-230-173-139.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
8 | [3.238.100.27](https://vuldb.com/?ip.3.238.100.27) | ec2-3-238-100-27.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
9 | [13.56.247.108](https://vuldb.com/?ip.13.56.247.108) | ec2-13-56-247-108.us-west-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
10 | [18.144.86.242](https://vuldb.com/?ip.18.144.86.242) | ec2-18-144-86-242.us-west-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
11 | [18.159.195.197](https://vuldb.com/?ip.18.159.195.197) | ec2-18-159-195-197.eu-central-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
12 | [18.207.250.11](https://vuldb.com/?ip.18.207.250.11) | ec2-18-207-250-11.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
13 | [20.18.34.148](https://vuldb.com/?ip.20.18.34.148) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
14 | [20.97.113.197](https://vuldb.com/?ip.20.97.113.197) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
15 | [20.163.67.84](https://vuldb.com/?ip.20.163.67.84) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
16 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Amazon AWS. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Amazon AWS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?explorer/index/zip` | High
3 | File | `/?r=email/api/mark&op=delFromSend` | High
4 | File | `/add-subadmin.php` | High
5 | File | `/add_new_invoice.php` | High
6 | File | `/add_user.php` | High
7 | File | `/admin/?page=system_info/contact_info` | High
8 | File | `/admin/?page=zone` | High
9 | File | `/admin/aboutus.php` | High
10 | File | `/admin/actions/check-attendance.php` | High
11 | File | `/admin/add-table.php` | High
12 | File | `/admin/admin_running.php` | High
13 | File | `/admin/ajax.php?action=save_recruitment_status` | High
14 | File | `/Admin/akun_edit.php` | High
15 | File | `/admin/apply.php` | High
16 | File | `/admin/approve_reservation.php` | High
17 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
18 | File | `/admin/changeimage.php` | High
19 | File | `/Admin/changepassword.php` | High
20 | File | `/admin/completed-requests.php` | High
21 | File | `/admin/content/editor` | High
22 | File | `/admin/create-package.php` | High
23 | File | `/admin/create_product.php` | High
24 | File | `/admin/delete_s6.php` | High
25 | File | `/admin/delete_user.php` | High
26 | File | `/admin/div_data/delete?divId=9` | High
27 | File | `/admin/doAdminAction.php?act=addCate` | High
28 | File | `/admin/edit-art-product-detail.php?editid=2` | High
29 | File | `/admin/edit-brand.php` | High
30 | File | `/admin/edit-user.php` | High
31 | File | `/admin/edit_room.php` | High
32 | File | `/admin/includes/edit_post.php` | High
33 | File | `/admin/index.php` | High
34 | File | `/admin/index.php?page=user-profile` | High
35 | File | `/admin/login.php` | High
36 | File | `/Admin/login.php` | High
37 | File | `/admin/massage.php` | High
38 | File | `/admin/mechanics/manage_mechanic.php` | High
39 | File | `/admin/modules/room/index.php` | High
40 | File | `/admin/profile.php` | High
41 | File | `/Admin/Proses_Edit_Akun.php` | High
42 | File | `/admin/receipt.php` | High
43 | File | `/admin/robot.php` | High
44 | File | `/admin/search-invoices.php` | High
45 | File | `/admin/tags/save` | High
46 | File | `/admin/twitter.php` | High
47 | File | `/admin/user-bookings.php` | High
48 | File | `/admin/user/index.php?view=edit` | High
49 | File | `/admin/view-appointment.php` | High
50 | File | `/admin/yesterday-reg-users.php` | High
51 | File | `/adminapi/system/file/openfile` | High
52 | File | `/administrator/addcategory.php` | High
53 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
54 | File | `/admin_class.php` | High
55 | File | `/ajax.php?action=save_payroll` | High
56 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
57 | File | `/alphaware/summary.php` | High
58 | File | `/animalsupdate.php` | High
59 | File | `/api/File/downloadFile` | High
60 | File | `/api/settings` | High
61 | File | `/api/sys/login` | High
62 | File | `/api/wizard/getCapability` | High
63 | File | `/app/api/controller/collect.php` | High
64 | File | `/app/api/v1/openvpn.py` | High
65 | File | `/app/controller/Api.php` | High
66 | File | `/app/register.php?action=reg` | High
67 | File | `/app/sys1.php` | High
68 | File | `/apply/index.php` | High
69 | File | `/assetsGroupReport/assetsService.j%73p` | High
70 | File | `/auth.asp` | Medium
71 | File | `/backend/doc/his_doc_update-account.php` | High
72 | File | `/bin/httpd` | Medium
73 | File | `/biurl_grou` | Medium
74 | File | `/boaform/formSysCmd` | High
75 | File | `/boafrm/formDMZ` | High
76 | File | `/boafrm/formRoute` | High
77 | File | `/boafrm/formTmultiAP` | High
78 | File | `/borrow.php` | Medium
79 | File | `/browse.php` | Medium
80 | ... | ... | ...

There are 703 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securitylabs.datadoghq.com/articles/following-attackers-trail-in-aws-methodology-findings-in-the-wild/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
