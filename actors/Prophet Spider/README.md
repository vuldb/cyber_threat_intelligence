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
* [RU](https://vuldb.com/?country.ru)
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
1 | T1006 | CWE-22, CWE-24, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/academy/home/courses` | High
4 | File | `/account/delivery` | High
5 | File | `/ad-list` | Medium
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/?page=user/manage_user&id=3` | High
8 | File | `/admin/about-us.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/ajax.php?action=confirm_order` | High
11 | File | `/admin/article/article-add.php` | High
12 | File | `/admin/article/article-edit-run.php` | High
13 | File | `/admin/cms_admin.php` | High
14 | File | `/admin/courses/manage_course.php` | High
15 | File | `/admin/edit-accepted-appointment.php` | High
16 | File | `/admin/edit_product.php` | High
17 | File | `/admin/index.php` | High
18 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
19 | File | `/admin/leancloud.php` | High
20 | File | `/admin/list_onlineuser.php` | High
21 | File | `/admin/modal_add_product.php` | High
22 | File | `/admin/project/update/2` | High
23 | File | `/admin/read.php?mudi=getSignal` | High
24 | File | `/admin/reg.php` | High
25 | File | `/admin/students/manage_academic.php` | High
26 | File | `/admin/students/update_status.php` | High
27 | File | `/admin/sys_sql_query.php` | High
28 | File | `/admin/test_status.php` | High
29 | File | `/admin/upload.php` | High
30 | File | `/admin/userprofile.php` | High
31 | File | `/admin/vote_edit.php` | High
32 | File | `/api/authentication/login` | High
33 | File | `/api/sys/login` | High
34 | File | `/api/wechat/app_auth` | High
35 | File | `/App_Resource/UEditor/server/upload.aspx` | High
36 | File | `/autheditpwd.php` | High
37 | File | `/author/list?limit=10&offset=0&order=desc` | High
38 | File | `/author_posts.php` | High
39 | File | `/bin/sh` | Low
40 | File | `/blog` | Low
41 | File | `/blog-single.php` | High
42 | File | `/browse` | Low
43 | File | `/cgi-bin/` | Medium
44 | File | `/chaincity/user/ticket/create` | High
45 | File | `/classes/Master.php` | High
46 | File | `/classes/Master.php?f=delete_category` | High
47 | File | `/classes/Master.php?f=delete_inquiry` | High
48 | File | `/classes/Master.php?f=save_inquiry` | High
49 | File | `/classes/Master.php?f=save_item` | High
50 | File | `/classes/Master.php?f=save_reminder` | High
51 | File | `/classes/Users.php?f=save` | High
52 | File | `/collection/all` | High
53 | File | `/company/store` | High
54 | File | `/config` | Low
55 | File | `/contact.php` | Medium
56 | File | `/Controller/Ajaxfileupload.ashx` | High
57 | File | `/course/filterRecords/` | High
58 | File | `/dashboard/createblog` | High
59 | File | `/dipam/save-delegates.php` | High
60 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
61 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
62 | File | `/ecommerce/support_ticket` | High
63 | File | `/edit_user.php` | High
64 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
65 | File | `/EventBookingCalendar/load.php?controller=GzFront/action=checkout/cid=1/layout=calendar/show_header=T/local=3` | High
66 | File | `/find-a-match` | High
67 | File | `/forum/away.php` | High
68 | ... | ... | ...

There are 593 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
