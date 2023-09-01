# TA551 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA551](https://vuldb.com/?actor.ta551). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta551](https://vuldb.com/?actor.ta551)

## Campaigns

The following _campaigns_ are known and can be associated with TA551:

* Cobalt Strike
* DarkVNC
* Hancitor
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA551:

* [RU](https://vuldb.com/?country.ru)
* [ES](https://vuldb.com/?country.es)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA551.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.209.76.110](https://vuldb.com/?ip.8.209.76.110) | - | Hancitor | High
2 | [23.82.141.241](https://vuldb.com/?ip.23.82.141.241) | - | Cobalt Strike | High
3 | [23.106.223.174](https://vuldb.com/?ip.23.106.223.174) | - | - | High
4 | [43.128.225.230](https://vuldb.com/?ip.43.128.225.230) | - | Hancitor | High
5 | [43.128.229.136](https://vuldb.com/?ip.43.128.229.136) | - | Hancitor | High
6 | [43.128.232.152](https://vuldb.com/?ip.43.128.232.152) | - | Hancitor | High
7 | [43.129.239.78](https://vuldb.com/?ip.43.129.239.78) | - | Hancitor | High
8 | [43.133.160.144](https://vuldb.com/?ip.43.133.160.144) | - | Hancitor | High
9 | [45.8.146.139](https://vuldb.com/?ip.45.8.146.139) | vm580483.stark-industries.solutions | IcedID | High
10 | [45.89.67.166](https://vuldb.com/?ip.45.89.67.166) | srbtv.ru | - | High
11 | [45.95.11.151](https://vuldb.com/?ip.45.95.11.151) | vm220095.pq.hosting | - | High
12 | [45.95.11.153](https://vuldb.com/?ip.45.95.11.153) | vm284420.pq.hosting | - | High
13 | [45.95.11.154](https://vuldb.com/?ip.45.95.11.154) | 4ser-1640356836.4server.su | - | High
14 | [45.95.11.155](https://vuldb.com/?ip.45.95.11.155) | slfk.lz | - | High
15 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA551_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA551. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=recruit/resume/edit&op=status` | High
2 | File | `/account/delivery` | High
3 | File | `/ad-list` | Medium
4 | File | `/admin/?page=user/list` | High
5 | File | `/admin/add-category.php` | High
6 | File | `/admin/add-services.php` | High
7 | File | `/admin/addproduct.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/budget/manage_budget.php` | High
10 | File | `/admin/categories/view_category.php` | High
11 | File | `/admin/contacts/organizations/edit/2` | High
12 | File | `/admin/curriculum/view_curriculum.php` | High
13 | File | `/admin/del_feedback.php` | High
14 | File | `/admin/del_service.php` | High
15 | File | `/admin/departments/view_department.php` | High
16 | File | `/admin/edit-accepted-appointment.php` | High
17 | File | `/admin/edit-services.php` | High
18 | File | `/admin/edit_category.php` | High
19 | File | `/admin/edit_product.php` | High
20 | File | `/admin/edit_subject.php` | High
21 | File | `/admin/forgot-password.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
24 | File | `/admin/invoice.php` | High
25 | File | `/admin/maintenance/view_designation.php` | High
26 | File | `/admin/modal_add_product.php` | High
27 | File | `/admin/project/update/2` | High
28 | File | `/admin/reg.php` | High
29 | File | `/admin/reminders/manage_reminder.php` | High
30 | File | `/admin/sales/manage_sale.php` | High
31 | File | `/admin/sales/view_details.php` | High
32 | File | `/admin/search-appointment.php` | High
33 | File | `/admin/suppliers/view_details.php` | High
34 | File | `/admin/sys_sql_query.php` | High
35 | File | `/admin/user/manage_user.php` | High
36 | File | `/admin/userprofile.php` | High
37 | File | `/admin/voters_row.php` | High
38 | File | `/ajax.php?action=read_msg` | High
39 | File | `/ajax.php?action=save_company` | High
40 | File | `/api/stl/actions/search` | High
41 | File | `/api/sys/set_passwd` | High
42 | File | `/App_Resource/UEditor/server/upload.aspx` | High
43 | File | `/bin/ate` | Medium
44 | File | `/blog` | Low
45 | File | `/booking/show_bookings/` | High
46 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
47 | File | `/cgi-bin/adm.cgi` | High
48 | File | `/cgi-bin/ping.cgi` | High
49 | File | `/changeimage.php` | High
50 | File | `/classes/Master.php?f=delete_inquiry` | High
51 | File | `/classes/Master.php?f=save_inquiry` | High
52 | File | `/classes/Master.php?f=save_item` | High
53 | File | `/classes/Users.php` | High
54 | File | `/classes/Users.php?f=save` | High
55 | File | `/config` | Low
56 | File | `/config/myfield/test.php` | High
57 | File | `/contact.php` | Medium
58 | File | `/contact/store` | High
59 | File | `/Controller/Ajaxfileupload.ashx` | High
60 | File | `/dev/snd/seq` | Medium
61 | File | `/dipam/athlete-profile.php` | High
62 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
63 | File | `/E-mobile/App/System/File/downfile.php` | High
64 | File | `/ecommerce/support_ticket` | High
65 | File | `/en/blog-comment-4` | High
66 | File | `/etc/master.passwd` | High
67 | File | `/etc/passwd` | Medium
68 | File | `/file_manager/admin/save_user.php` | High
69 | File | `/friends` | Medium
70 | File | `/goForm/aspForm` | High
71 | ... | ... | ...

There are 624 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/diary/28092
* https://isc.sans.edu/diary/IcedID+%28Bokbot%29+with+Dark+VNC+and+Cobalt+Strike/28884
* https://isc.sans.edu/diary/Monster+Libra+%28TA551Shathak%29+--%3E+IcedID+%28Bokbot%29+--%3E+Cobalt+Strike+%26+DarkVNC/28974
* https://isc.sans.edu/diary/Monster+Libra+%28TA551Shathak%29+pushes+IcedID+%28Bokbot%29+with+Dark+VNC+and+Cobalt+Strike/28934
* https://isc.sans.edu/diary/rss/27738
* https://isc.sans.edu/forums/diary/More+TA551+Shathak+Word+docs+push+IcedID+Bokbot/26674/
* https://isc.sans.edu/forums/diary/TA551+Shathak+Word+docs+push+IcedID+Bokbot/26438/
* https://www.malware-traffic-analysis.net/2021/09/14/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
