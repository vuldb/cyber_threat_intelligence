# ShadowSyndicate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ShadowSyndicate](https://vuldb.com/?actor.shadowsyndicate). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shadowsyndicate](https://vuldb.com/?actor.shadowsyndicate)

## Campaigns

The following _campaigns_ are known and can be associated with ShadowSyndicate:

* CVE-2024-23334
* RansomHub

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ShadowSyndicate:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ShadowSyndicate.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.216.148.33](https://vuldb.com/?ip.31.216.148.33) | 31-216-148-33.ip.dclux.com | RansomHub | High
2 | [46.161.27.151](https://vuldb.com/?ip.46.161.27.151) | - | RansomHub | High
3 | [66.203.125.21](https://vuldb.com/?ip.66.203.125.21) | - | RansomHub | High
4 | ... | ... | ... | ...

There are 12 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ShadowSyndicate_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ShadowSyndicate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
3 | File | `../mtd/Config/Sha1Account1` | High
4 | File | `/?s=doudou&c=file&a=list` | High
5 | File | `/account/forgotpassword` | High
6 | File | `/Account/Login` | High
7 | File | `/accounts/password_change/` | High
8 | File | `/add-phlebotomist.php` | High
9 | File | `/add-subadmin.php` | High
10 | File | `/admin` | Low
11 | File | `/admin-api/infra/file/upload` | High
12 | File | `/admin.php/accessory/filesdel.html` | High
13 | File | `/admin/?page=products/view_product` | High
14 | File | `/admin/admin-profile.php` | High
15 | File | `/admin/adminScoreUrl` | High
16 | File | `/admin/ajax.php?action=login` | High
17 | File | `/admin/app/profile_crud.php` | High
18 | File | `/admin/article.php` | High
19 | File | `/admin/blood/update/o-.php` | High
20 | File | `/admin/categories/save` | High
21 | File | `/admin/categories/update` | High
22 | File | `/admin/category.php` | High
23 | File | `/admin/check_availability.php` | High
24 | File | `/admin/content/book` | High
25 | File | `/admin/deleteroom.php` | High
26 | File | `/admin/edit-services.php` | High
27 | File | `/admin/editempexp.php` | High
28 | File | `/admin/faculty_action.php` | High
29 | File | `/admin/File/pictureUpload` | High
30 | File | `/admin/forgot-password.php` | High
31 | File | `/admin/group/edit.do` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/index.php/web/ajax_all_lists` | High
34 | File | `/admin/indexConfigs/save` | High
35 | File | `/admin/link.php` | High
36 | File | `/admin/login.php` | High
37 | File | `/admin/manage-nurse.php` | High
38 | File | `/admin/manage-users.php` | High
39 | File | `/admin/model/addOrUpdate` | High
40 | File | `/admin/msg.php` | High
41 | File | `/admin/network/wifi_schedule` | High
42 | File | `/admin/options-theme.php` | High
43 | File | `/admin/sales-reports-detail.php` | High
44 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
45 | File | `/admin/setup.cgi` | High
46 | File | `/admin/subcategory.php` | High
47 | File | `/admin/tag/save` | High
48 | File | `/admin/view-user-queries.php` | High
49 | File | `/adminprofile.php` | High
50 | File | `/admin_topic.php?action=delall` | High
51 | File | `/adpweb/a/base/barcodeDetail/` | High
52 | File | `/adpweb/a/ica/api/service/rfa/testService` | High
53 | File | `/adpweb/wechat/verifyToken/` | High
54 | File | `/analysisProject/pagingQueryData` | High
55 | File | `/api/admin/attachments/upload` | High
56 | File | `/api/backend/v1/user/create` | High
57 | File | `/api/baskets/{name}` | High
58 | File | `/api/client/article/list` | High
59 | File | `/api/client/editemedia.php` | High
60 | File | `/api/data.php` | High
61 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
62 | File | `/api/front/search/books` | High
63 | File | `/api/login/auth` | High
64 | File | `/api/stl/actions/search` | High
65 | File | `/api/sys/login` | High
66 | File | `/api/system/dept/update` | High
67 | File | `/Api/TinyMce/UploadAjax.ashx` | High
68 | File | `/Api/TinyMce/UploadAjaxAPI.ashx` | High
69 | File | `/api/user/update` | High
70 | File | `/api/v1/alerts` | High
71 | File | `/api/v1/vhosts/vid-` | High
72 | File | `/api /v3/auth` | High
73 | File | `/api/wechat/app_auth` | High
74 | File | `/api/wizard/getBasicInfo` | High
75 | ... | ... | ...

There are 656 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/cgsi-probes-shadowsyndicate-groups-possible-exploitation-of-aiohttp-vulnerability-cve-2024-23334/
* https://darktrace.com/blog/ransomhub-ransomware-darktraces-investigation-of-the-newest-tool-in-shadowsyndicates-arsenal

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
