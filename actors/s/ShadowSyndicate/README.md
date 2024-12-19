# ShadowSyndicate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ShadowSyndicate](https://vuldb.com/?actor.shadowsyndicate). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shadowsyndicate](https://vuldb.com/?actor.shadowsyndicate)

## Campaigns

The following _campaigns_ are known and can be associated with ShadowSyndicate:

* CVE-2024-23334

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ShadowSyndicate:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ShadowSyndicate.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [81.19.136.251](https://vuldb.com/?ip.81.19.136.251) | - | CVE-2024-23334 | High
2 | [103.151.172.28](https://vuldb.com/?ip.103.151.172.28) | - | CVE-2024-23334 | High
3 | [143.244.188.172](https://vuldb.com/?ip.143.244.188.172) | - | CVE-2024-23334 | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ShadowSyndicate_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-81 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ShadowSyndicate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `//etc/RT2870STA.dat` | High
3 | File | `/?import` | Medium
4 | File | `/act/ActDao.xml` | High
5 | File | `/admin-api/upload_image` | High
6 | File | `/admin.php/accessory/filesdel.html` | High
7 | File | `/admin.php/appcenter/local.html?type=addon` | High
8 | File | `/admin.php?p=/Area/index#tab=t2` | High
9 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
10 | File | `/admin/?page=products/view_product` | High
11 | File | `/admin/admin-profile.php` | High
12 | File | `/admin/admin.php` | High
13 | File | `/admin/admin_content_tag.php?action=save_content` | High
14 | File | `/admin/blood/update/o-.php` | High
15 | File | `/admin/class.php?dowhat=modifyclass` | High
16 | File | `/admin/div_data/delete?divId=9` | High
17 | File | `/admin/edit-services.php` | High
18 | File | `/admin/emp-profile-avatar.php` | High
19 | File | `/admin/File/pictureUpload` | High
20 | File | `/admin/manage-ambulance.php` | High
21 | File | `/admin/manage-users.php` | High
22 | File | `/admin/menu/toEdit` | High
23 | File | `/admin/msg.php` | High
24 | File | `/admin/network/wifi_schedule` | High
25 | File | `/Admin/News.php` | High
26 | File | `/admin/options-theme.php` | High
27 | File | `/admin/pages/list` | High
28 | File | `/admin/system.php` | High
29 | File | `/admin/tag.php` | High
30 | File | `/admin/users.php` | High
31 | File | `/admin1/file/download` | High
32 | File | `/adminPage/conf/saveCmd` | High
33 | File | `/ajax.php?action=load_answered` | High
34 | File | `/ajax/checkin.php` | High
35 | File | `/analysisProject/pagingQueryData` | High
36 | File | `/api/` | Low
37 | File | `/api/0/api-tokens/` | High
38 | File | `/api/admins` | Medium
39 | File | `/api/backend/core/web-file-upload/upload` | High
40 | File | `/api/baskets/{name}` | High
41 | File | `/api/stl/actions/search` | High
42 | File | `/api/sys/login` | High
43 | File | `/api/sys/set_passwd` | High
44 | File | `/api/system/dept/tree?sort=parentId%2Casc&sort=sort%2Casc` | High
45 | File | `/api/system/user?deptId=1&page=1&size=10` | High
46 | File | `/api/v1` | Low
47 | File | `/api/v1/alerts` | High
48 | File | `/api/v1/settings` | High
49 | File | `/api/v1/snapshots` | High
50 | File | `/api/v1/toolbox/device/update/swap` | High
51 | File | `/api/v1/vhosts/vid-` | High
52 | File | `/api2/html/` | Medium
53 | File | `/apps/api/views/deploy_api.py` | High
54 | File | `/apps/system/router/upload.go` | High
55 | File | `/Attachment/fromImageUrl` | High
56 | File | `/authMonitCallcenter` | High
57 | File | `/bitrix/admin/ldap_server_edit.php` | High
58 | File | `/boafrm/formMapDelDevice` | High
59 | File | `/car-rental-management-system/admin/view_car.php=` | High
60 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
61 | File | `/cgi-bin/cstecgi.cgi` | High
62 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
63 | File | `/cgi-bin/hd_config.cgi` | High
64 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
65 | File | `/cgi-bin/nas_sharing.cgi` | High
66 | ... | ... | ...

There are 577 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cyble.com/blog/cgsi-probes-shadowsyndicate-groups-possible-exploitation-of-aiohttp-vulnerability-cve-2024-23334/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
