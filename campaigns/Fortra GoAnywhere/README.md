# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Fortra GoAnywhere or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Clop](https://vuldb.com/?actor.clop) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortra GoAnywhere.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.101.53.11](https://vuldb.com/?ip.3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | [Clop](https://vuldb.com/?actor.clop) | Medium
2 | [5.34.178.28](https://vuldb.com/?ip.5.34.178.28) | s41.friendhosting.net | [Clop](https://vuldb.com/?actor.clop) | High
3 | [5.34.178.30](https://vuldb.com/?ip.5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | [Clop](https://vuldb.com/?actor.clop) | High
4 | [5.34.178.31](https://vuldb.com/?ip.5.34.178.31) | free.ds | [Clop](https://vuldb.com/?actor.clop) | High
5 | [5.34.180.48](https://vuldb.com/?ip.5.34.180.48) | mail.tube-plant.com | [Clop](https://vuldb.com/?actor.clop) | High
6 | [15.235.13.184](https://vuldb.com/?ip.15.235.13.184) | gollum.utwb.net | [Clop](https://vuldb.com/?actor.clop) | High
7 | [15.235.83.73](https://vuldb.com/?ip.15.235.83.73) | web0.meritusedu.ca | [Clop](https://vuldb.com/?actor.clop) | High
8 | [20.47.120.195](https://vuldb.com/?ip.20.47.120.195) | - | [Clop](https://vuldb.com/?actor.clop) | High
9 | [24.3.132.168](https://vuldb.com/?ip.24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | [Clop](https://vuldb.com/?actor.clop) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-29, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/academy/tutor/filter` | High
4 | File | `/account/delivery` | High
5 | File | `/ad-list` | Medium
6 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
7 | File | `/admin/?page=bike` | High
8 | File | `/admin/?page=user/list` | High
9 | File | `/admin/?page=user/manage_user&id=3` | High
10 | File | `/admin/add_user_modal.php` | High
11 | File | `/admin/admin-profile.php` | High
12 | File | `/admin/admin_content_tag.php?action=save_content` | High
13 | File | `/admin/ajax.php?action=delete_transaction` | High
14 | File | `/admin/ajax.php?action=delete_uploads` | High
15 | File | `/admin/config.php?display=disa&view=form` | High
16 | File | `/admin/contacts/organizations/edit/2` | High
17 | File | `/admin/courses/manage_course.php` | High
18 | File | `/admin/courses/view_course.php` | High
19 | File | `/admin/deduction_row.php` | High
20 | File | `/admin/departments/view_department.php` | High
21 | File | `/admin/edit-accepted-appointment.php` | High
22 | File | `/admin/edit_category.php` | High
23 | File | `/admin/edit_product.php` | High
24 | File | `/admin/inquiries/view_inquiry.php` | High
25 | File | `/admin/leancloud.php` | High
26 | File | `/admin/list_addr_fwresource_ip.php` | High
27 | File | `/admin/list_onlineuser.php` | High
28 | File | `/admin/login.php` | High
29 | File | `/admin/maintenance/manage_category.php` | High
30 | File | `/admin/maintenance/view_designation.php` | High
31 | File | `/admin/manage_user.php` | High
32 | File | `/admin/mechanics/manage_mechanic.php` | High
33 | File | `/admin/modal_add_product.php` | High
34 | File | `/admin/order.php` | High
35 | File | `/admin/products/manage_product.php` | High
36 | File | `/admin/project/update/2` | High
37 | File | `/admin/reg.php` | High
38 | File | `/admin/report/index.php` | High
39 | File | `/admin/reportupload.aspx` | High
40 | File | `/admin/search-appointment.php` | High
41 | File | `/admin/students/update_status.php` | High
42 | File | `/admin/suppliers/view_details.php` | High
43 | File | `/admin/sys_sql_query.php` | High
44 | File | `/admin/theme-edit.php` | High
45 | File | `/admin/upload.php` | High
46 | File | `/admin/user/manage_user.php` | High
47 | File | `/admin/vote_edit.php` | High
48 | File | `/administration/setting_security.php` | High
49 | File | `/ajax.php?action=read_msg` | High
50 | File | `/api/es/admin/v3/security/user/1` | High
51 | File | `/api/sys/login` | High
52 | File | `/apply.cgi` | Medium
53 | File | `/App_Resource/UEditor/server/upload.aspx` | High
54 | File | `/author_posts.php` | High
55 | File | `/blog` | Low
56 | File | `/cas/logout` | Medium
57 | File | `/cgi-bin/` | Medium
58 | File | `/cgi-bin/koha/catalogue/search.pl` | High
59 | File | `/cgi-bin/vitogate.cgi` | High
60 | File | `/chaincity/user/ticket/create` | High
61 | File | `/change-language/de_DE` | High
62 | File | `/changeimage.php` | High
63 | File | `/classes/Master.php` | High
64 | File | `/classes/Master.php?f=delete_category` | High
65 | File | `/classes/Master.php?f=save_category` | High
66 | File | `/classes/Master.php?f=save_inquiry` | High
67 | File | `/classes/Master.php?f=save_item` | High
68 | File | `/classes/Users.php?f=save` | High
69 | File | `/classes/Users.phpp` | High
70 | File | `/collection/all` | High
71 | File | `/company/store` | High
72 | File | `/config` | Low
73 | File | `/config/api/v1/reboot` | High
74 | File | `/contact.php` | Medium
75 | File | `/contact/store` | High
76 | File | `/Content/Plugins/uploader/FileChoose.html?fileUrl=/Upload/File/Pics/&parent` | High
77 | File | `/Controller/Ajaxfileupload.ashx` | High
78 | File | `/core/tools/customblock.php` | High
79 | ... | ... | ...

There are 692 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
