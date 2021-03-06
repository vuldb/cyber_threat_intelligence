# SideWinder - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SideWinder](https://vuldb.com/?actor.sidewinder). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sidewinder](https://vuldb.com/?actor.sidewinder)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SideWinder:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SideWinder.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.245.21](https://vuldb.com/?ip.2.56.245.21) | - | - | High
2 | [5.2.70.111](https://vuldb.com/?ip.5.2.70.111) | - | - | High
3 | [5.2.72.165](https://vuldb.com/?ip.5.2.72.165) | - | - | High
4 | [5.181.156.107](https://vuldb.com/?ip.5.181.156.107) | no-rdns.mivocloud.com | - | High
5 | [5.181.156.244](https://vuldb.com/?ip.5.181.156.244) | no-rdns.mivocloud.com | - | High
6 | [5.182.206.168](https://vuldb.com/?ip.5.182.206.168) | - | - | High
7 | [5.230.67.22](https://vuldb.com/?ip.5.230.67.22) | placeholder.noezserver.de | - | High
8 | [5.230.67.166](https://vuldb.com/?ip.5.230.67.166) | placeholder.noezserver.de | - | High
9 | [5.230.67.191](https://vuldb.com/?ip.5.230.67.191) | placeholder.noezserver.de | - | High
10 | [5.252.178.129](https://vuldb.com/?ip.5.252.178.129) | 5-252-178-129.mivocloud.com | - | High
11 | [5.252.179.18](https://vuldb.com/?ip.5.252.179.18) | 5-252-179-18.mivocloud.com | - | High
12 | [5.252.179.197](https://vuldb.com/?ip.5.252.179.197) | no-rdns.mivocloud.com | - | High
13 | [5.252.195.27](https://vuldb.com/?ip.5.252.195.27) | 195-27.static.ipcserver.net | - | High
14 | [5.252.195.55](https://vuldb.com/?ip.5.252.195.55) | 195-55.static.ipcserver.net | - | High
15 | [5.252.195.161](https://vuldb.com/?ip.5.252.195.161) | 195-161.static.ipcserver.net | - | High
16 | [5.255.103.63](https://vuldb.com/?ip.5.255.103.63) | - | - | High
17 | [45.86.162.75](https://vuldb.com/?ip.45.86.162.75) | - | - | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SideWinder_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SideWinder. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/?page=system_info/contact_info` | High
2 | File | `/admin/admin_login.php` | High
3 | File | `/backups/` | Medium
4 | File | `/cgi-bin/wapopen` | High
5 | File | `/config/getuser` | High
6 | File | `/controllers/MgrDiagnosticTools.php` | High
7 | File | `/dashboard/reports/logs/view` | High
8 | File | `/dashboard/system/express/entities/forms/save_control/[GUID]` | High
9 | File | `/dev/cuse` | Medium
10 | File | `/download` | Medium
11 | File | `/etc/config/rpcd` | High
12 | File | `/EXCU_SHELL` | Medium
13 | File | `/export` | Low
14 | File | `/forum/away.php` | High
15 | File | `/gena.cgi` | Medium
16 | File | `/goform/webSettingProfileSecurity` | High
17 | File | `/login` | Low
18 | File | `/mgmt/tm/util/bash` | High
19 | File | `/MIME/INBOX-MM-1/` | High
20 | File | `/ms/file/uploadTemplate.do` | High
21 | File | `/netflow/jspui/editProfile.jsp` | High
22 | File | `/novel-admin/src/main/java/com/java2nb/common/controller/FileController.java` | High
23 | File | `/ofrs/admin/?page=requests/view_request` | High
24 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
25 | File | `/out.php` | Medium
26 | File | `/php/ajax.php` | High
27 | File | `/public/login.htm` | High
28 | File | `/rapi/read_url` | High
29 | File | `/sec/content/sec_asa_users_local_db_add.html` | High
30 | File | `/see_more_details.php` | High
31 | File | `/service/v1/createUser` | High
32 | File | `/setSystemAdmin` | High
33 | File | `/Storage/Emulated/0/Telegram/Telegram` | High
34 | File | `/thruk/#cgi-bin/extinfo.cgi?type=2` | High
35 | File | `/uncpath/` | Medium
36 | File | `/user/dls_download.php` | High
37 | File | `/vicidial/user_stats.php` | High
38 | File | `/vloggers_merch/admin/?page=orders/view_order` | High
39 | File | `/wp-admin/admin-ajax.php` | High
40 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
41 | ... | ... | ...

There are 358 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.group-ib.com/sidewinder-antibot

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
