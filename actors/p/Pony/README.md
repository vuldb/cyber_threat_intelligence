# Pony - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pony](https://vuldb.com/?actor.pony). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pony](https://vuldb.com/?actor.pony)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pony:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pony.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.15.199](https://vuldb.com/?ip.5.39.15.199) | - | - | High
2 | [5.135.8.71](https://vuldb.com/?ip.5.135.8.71) | - | - | High
3 | [45.58.116.102](https://vuldb.com/?ip.45.58.116.102) | - | - | High
4 | [46.161.1.172](https://vuldb.com/?ip.46.161.1.172) | free.gbnhost.com | - | High
5 | [50.56.223.113](https://vuldb.com/?ip.50.56.223.113) | 50-56-223-113.static.cloud-ips.com | - | High
6 | [62.112.130.165](https://vuldb.com/?ip.62.112.130.165) | - | - | High
7 | [64.85.169.189](https://vuldb.com/?ip.64.85.169.189) | - | - | High
8 | [64.85.169.190](https://vuldb.com/?ip.64.85.169.190) | - | - | High
9 | [66.175.212.25](https://vuldb.com/?ip.66.175.212.25) | 66-175-212-25.ip.linodeusercontent.com | - | High
10 | [69.194.196.39](https://vuldb.com/?ip.69.194.196.39) | visit.keznews.com | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pony_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pony. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/` | Low
2 | File | `/admin/about-us.php` | High
3 | File | `/admin/bookings/view_details.php` | High
4 | File | `/Admin/changepassword.php` | High
5 | File | `/admin/court` | Medium
6 | File | `/Admin/createClass.php` | High
7 | File | `/admin/curriculum/view_curriculum.php` | High
8 | File | `/admin/del_service.php` | High
9 | File | `/admin/edit_category.php` | High
10 | File | `/admin/maintenance/manage_brand.php` | High
11 | File | `/admin/maintenance/view_designation.php` | High
12 | File | `/admin/orders/update_status.php` | High
13 | File | `/admin/orders/view_order.php` | High
14 | File | `/admin/problem_judge.php` | High
15 | File | `/admin/product/manage_product.php` | High
16 | File | `/admin/reg.php` | High
17 | File | `/admin/save.php` | High
18 | File | `/admin/settings/` | High
19 | File | `/adminapi/system/file/openfile` | High
20 | File | `/api/controllers/common/UploadsController.php` | High
21 | File | `/app/api/controller/default/File.php` | High
22 | File | `/app/api/controller/default/Sqlite.php` | High
23 | File | `/app/Http/Controllers/ImageController.php` | High
24 | File | `/apps/login_auth.php` | High
25 | File | `/APR/signup.php` | High
26 | File | `/auth/user/all.api` | High
27 | File | `/b2b-supermarket/shopping-cart` | High
28 | File | `/blog-single.php` | High
29 | File | `/blog/blog.php` | High
30 | File | `/boaform/wlan_basic_set.cgi` | High
31 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
32 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/wlogin.cgi` | High
36 | File | `/classes/Master.php` | High
37 | File | `/classes/Master.php?f=delete_inquiry` | High
38 | File | `/College/admin/teacher.php` | High
39 | File | `/conf/app.conf` | High
40 | File | `/course/filterRecords/` | High
41 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
42 | File | `/E-mobile/App/System/File/downfile.php` | High
43 | File | `/Electron/download` | High
44 | File | `/endpoint/add-faq.php` | High
45 | File | `/endpoint/add-guest.php` | High
46 | File | `/file-manager/rename.php` | High
47 | File | `/file-manager/upload.php` | High
48 | File | `/forum/away.php` | High
49 | File | `/geoserver/gwc/rest.html` | High
50 | File | `/goform/RgTime` | High
51 | File | `/goform/wifiSSIDset` | High
52 | File | `/index.php` | Medium
53 | File | `/index.php/coins/update_marketboxslider` | High
54 | File | `/kelasdosen/data` | High
55 | File | `/librarian/bookdetails.php` | High
56 | File | `/libsystem/login.php` | High
57 | File | `/manage_sy.php` | High
58 | File | `/mims/login.php` | High
59 | File | `/ndmComponents.js` | High
60 | File | `/onlinecourse/` | High
61 | ... | ... | ...

There are 533 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/forums/diary/Malicious+spam+Subject+RE+Bill/20417/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
