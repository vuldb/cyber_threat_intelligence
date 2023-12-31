# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* CVE-2022-21587
* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [EG](https://vuldb.com/?country.eg)
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.95.44.214](https://vuldb.com/?ip.23.95.44.214) | 23-95-44-214-host.colocrossing.com | CVE-2022-21587 | High
3 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
4 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
5 | [45.61.136.188](https://vuldb.com/?ip.45.61.136.188) | - | CVE-2022-21587 | High
6 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
7 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
8 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=recruit/resume/edit&op=status` | High
2 | File | `/academy/home/courses` | High
3 | File | `/ad-list` | Medium
4 | File | `/admin/?page=user/list` | High
5 | File | `/admin/?page=user/manage_user&id=3` | High
6 | File | `/admin/about-us.php` | High
7 | File | `/admin/add-category.php` | High
8 | File | `/admin/admin-profile.php` | High
9 | File | `/admin/ajax.php?action=confirm_order` | High
10 | File | `/admin/article/article-add.php` | High
11 | File | `/admin/article/article-edit-run.php` | High
12 | File | `/admin/cms_admin.php` | High
13 | File | `/admin/course.php` | High
14 | File | `/admin/courses/manage_course.php` | High
15 | File | `/admin/del_feedback.php` | High
16 | File | `/admin/edit-accepted-appointment.php` | High
17 | File | `/admin/edit-services.php` | High
18 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
19 | File | `/admin/invoice.php` | High
20 | File | `/admin/leancloud.php` | High
21 | File | `/admin/list_onlineuser.php` | High
22 | File | `/admin/manage-pages.php` | High
23 | File | `/admin/settings/` | High
24 | File | `/admin/students/manage_academic.php` | High
25 | File | `/admin/students/update_status.php` | High
26 | File | `/admin/subject.php` | High
27 | File | `/admin/sys_sql_query.php` | High
28 | File | `/admin/theme-edit.php` | High
29 | File | `/admin/user/manage_user.php` | High
30 | File | `/adplanet/PlanetUser` | High
31 | File | `/ample/app/ajax/member_data.php` | High
32 | File | `/api/authentication/login` | High
33 | File | `/api/DataDictionary/GetItemList` | High
34 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
35 | File | `/api/sys/login` | High
36 | File | `/App_Resource/UEditor/server/upload.aspx` | High
37 | File | `/article/DelectArticleById/` | High
38 | File | `/auth/auth.php?user=1` | High
39 | File | `/autheditpwd.php` | High
40 | File | `/author/list?limit=10&offset=0&order=desc` | High
41 | File | `/b2b-supermarket/catalog/all-products` | High
42 | File | `/b2b-supermarket/shopping-cart` | High
43 | File | `/blog` | Low
44 | File | `/browse` | Low
45 | File | `/category.php` | High
46 | File | `/cgi-bin/` | Medium
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/claire_blake` | High
49 | File | `/classes/Master.php` | High
50 | File | `/classes/Master.php?f=delete_category` | High
51 | File | `/classes/Master.php?f=save_reminder` | High
52 | File | `/collection/all` | High
53 | File | `/company/store` | High
54 | File | `/config,admin.jsp` | High
55 | File | `/Controller/Ajaxfileupload.ashx` | High
56 | File | `/course/filterRecords/` | High
57 | File | `/dashboard/createblog` | High
58 | File | `/download/image` | High
59 | File | `/edit_user.php` | High
60 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
61 | File | `/endpoint/add-guest.php` | High
62 | File | `/endpoint/add-user.php` | High
63 | File | `/endpoint/delete-user.php` | High
64 | File | `/etc/hosts.deny` | High
65 | File | `/EventBookingCalendar/load.php?controller=GzFront/action=checkout/cid=1/layout=calendar/show_header=T/local=3` | High
66 | File | `/file-manager/delete.php` | High
67 | File | `/find-a-match` | High
68 | File | `/forum/away.php` | High
69 | File | `/friends` | Medium
70 | File | `/friends/ajax_invite` | High
71 | File | `/fusion/portal/action/Link` | High
72 | ... | ... | ...

There are 632 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me
* https://exchange.xforce.ibmcloud.com/report/details/guid:83252d980b8ff3736f528d0afbea7eba

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
