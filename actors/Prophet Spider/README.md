# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
3 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
4 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
5 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
6 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
7 | [51.79.175.139](https://vuldb.com/?ip.51.79.175.139) | vps-dc8b0481.vps.ovh.ca | Log4Shell | High
8 | [51.222.121.180](https://vuldb.com/?ip.51.222.121.180) | ip180.ip-51-222-121.net | Log4Shell | High
9 | ... | ... | ... | ...

There are 31 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-270, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/comment.yml` | High
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/academy/home/courses` | High
4 | File | `/ad-list` | Medium
5 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/?page=user/manage_user&id=3` | High
8 | File | `/admin/addproduct.php` | High
9 | File | `/admin/ajax.php?action=confirm_order` | High
10 | File | `/admin/article/article-add.php` | High
11 | File | `/admin/article/article-edit-run.php` | High
12 | File | `/admin/budget/manage_budget.php` | High
13 | File | `/admin/cms_admin.php` | High
14 | File | `/admin/contacts/organizations/edit/2` | High
15 | File | `/admin/edit_product.php` | High
16 | File | `/admin/edit_subject.php` | High
17 | File | `/admin/index.php` | High
18 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
19 | File | `/admin/leancloud.php` | High
20 | File | `/admin/modal_add_product.php` | High
21 | File | `/admin/project/update/2` | High
22 | File | `/admin/read.php?mudi=getSignal` | High
23 | File | `/admin/reg.php` | High
24 | File | `/admin/reportupload.aspx` | High
25 | File | `/admin/service.php` | High
26 | File | `/admin/sys_sql_query.php` | High
27 | File | `/admin/test_status.php` | High
28 | File | `/admin/update_s6.php` | High
29 | File | `/admin/upload.php` | High
30 | File | `/admin/userprofile.php` | High
31 | File | `/admin/vote_edit.php` | High
32 | File | `/ajax.php?action=read_msg` | High
33 | File | `/ajax.php?action=save_company` | High
34 | File | `/api/stl/actions/search` | High
35 | File | `/api/sys/login` | High
36 | File | `/App_Resource/UEditor/server/upload.aspx` | High
37 | File | `/autheditpwd.php` | High
38 | File | `/author_posts.php` | High
39 | File | `/bin/sh` | Low
40 | File | `/blog` | Low
41 | File | `/blog-single.php` | High
42 | File | `/booking/show_bookings/` | High
43 | File | `/browse` | Low
44 | File | `/cgi-bin/ping.cgi` | High
45 | File | `/chaincity/user/ticket/create` | High
46 | File | `/changeimage.php` | High
47 | File | `/classes/Master.php?f=delete_category` | High
48 | File | `/classes/Master.php?f=delete_inquiry` | High
49 | File | `/classes/Master.php?f=delete_service` | High
50 | File | `/classes/Master.php?f=save_inquiry` | High
51 | File | `/classes/Master.php?f=save_item` | High
52 | File | `/classes/Users.php?f=save` | High
53 | File | `/collection/all` | High
54 | File | `/company/store` | High
55 | File | `/config` | Low
56 | File | `/contact.php` | Medium
57 | File | `/Controller/Ajaxfileupload.ashx` | High
58 | File | `/course/filterRecords/` | High
59 | File | `/dipam/save-delegates.php` | High
60 | File | `/Duty/AjaxHandle/UploadFloodPlanFileUpdate.ashx` | High
61 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
62 | File | `/ecommerce/support_ticket` | High
63 | File | `/edit_user.php` | High
64 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
65 | File | `/EventBookingCalendar/load.php?controller=GzFront/action=checkout/cid=1/layout=calendar/show_header=T/local=3` | High
66 | File | `/file_manager/admin/save_user.php` | High
67 | File | `/find-a-match` | High
68 | File | `/friends` | Medium
69 | File | `/friends/ajax_invite` | High
70 | File | `/fusion/portal/action/Link` | High
71 | File | `/goForm/aspForm` | High
72 | File | `/goform/SetSysTimeCfg` | High
73 | File | `/goform/SetVirtualServerCfg` | High
74 | File | `/home/courses` | High
75 | File | `/home/filter_listings` | High
76 | ... | ... | ...

There are 673 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
