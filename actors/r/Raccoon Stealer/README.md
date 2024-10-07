# Raccoon Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Raccoon Stealer](https://vuldb.com/?actor.raccoon_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.raccoon_stealer](https://vuldb.com/?actor.raccoon_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Raccoon Stealer:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Raccoon Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.247](https://vuldb.com/?ip.2.58.56.247) | powered.by.rdp.sh | - | High
2 | [5.42.199.87](https://vuldb.com/?ip.5.42.199.87) | - | - | High
3 | [5.252.22.62](https://vuldb.com/?ip.5.252.22.62) | vm523526.stark-industries.solutions | - | High
4 | [5.252.22.66](https://vuldb.com/?ip.5.252.22.66) | s-germany.rocks | - | High
5 | [5.252.22.107](https://vuldb.com/?ip.5.252.22.107) | ns3.pacehost.de | - | High
6 | [23.88.55.150](https://vuldb.com/?ip.23.88.55.150) | static.150.55.88.23.clients.your-server.de | - | High
7 | [31.13.195.44](https://vuldb.com/?ip.31.13.195.44) | - | - | High
8 | [45.61.136.191](https://vuldb.com/?ip.45.61.136.191) | - | - | High
9 | [45.67.34.152](https://vuldb.com/?ip.45.67.34.152) | vm749292.stark-industries.solutions | - | High
10 | [45.67.34.234](https://vuldb.com/?ip.45.67.34.234) | server.ga2.so-net.ne.jp | - | High
11 | [45.67.35.251](https://vuldb.com/?ip.45.67.35.251) | vm684273.stark-industries.solutions | - | High
12 | [45.84.0.80](https://vuldb.com/?ip.45.84.0.80) | sfixbfc.cn | - | High
13 | [45.92.156.52](https://vuldb.com/?ip.45.92.156.52) | - | - | High
14 | [45.92.156.53](https://vuldb.com/?ip.45.92.156.53) | - | - | High
15 | [45.133.216.145](https://vuldb.com/?ip.45.133.216.145) | mail.axiknh.top | - | High
16 | [45.133.216.170](https://vuldb.com/?ip.45.133.216.170) | wireguard.vasilchenko.dev | - | High
17 | [45.133.216.249](https://vuldb.com/?ip.45.133.216.249) | vm699942.stark-industries.solutions | - | High
18 | [45.138.74.104](https://vuldb.com/?ip.45.138.74.104) | descriptive-servant.aeza.network | - | High
19 | [45.142.212.100](https://vuldb.com/?ip.45.142.212.100) | pikpik.top | - | High
20 | [45.142.215.50](https://vuldb.com/?ip.45.142.215.50) | vm700900.stark-industries.solutions | - | High
21 | [45.142.215.92](https://vuldb.com/?ip.45.142.215.92) | vm586875.stark-industries.solutions | - | High
22 | ... | ... | ... | ...

There are 86 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Raccoon Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Raccoon Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/academy/home/courses` | High
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/admin/del_feedback.php` | High
6 | File | `/admin/edit-post.php` | High
7 | File | `/admin/index2.html` | High
8 | File | `/admin/modal_add_product.php` | High
9 | File | `/admin/positions_add.php` | High
10 | File | `/ajax.php?action=save_company` | High
11 | File | `/ajax.php?action=save_user` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/database` | High
14 | File | `/app/index/controller/Common.php` | High
15 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
16 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
17 | File | `/applications/nexus/modules/front/store/store.php` | High
18 | File | `/App_Resource/UEditor/server/upload.aspx` | High
19 | File | `/bitrix/admin/ldap_server_edit.php` | High
20 | File | `/c/PluginsController.php` | High
21 | File | `/category.php` | High
22 | File | `/cgi-bin/apkg_mgr.cgi` | High
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/nas_sharing.cgi` | High
25 | File | `/cgi-bin/photocenter_mgr.cgi` | High
26 | File | `/chaincity/user/ticket/create` | High
27 | File | `/classes/Master.php` | High
28 | File | `/classes/Master.php?f=delete_record` | High
29 | File | `/classes/Master.php?f=save_category` | High
30 | File | `/classes/SystemSettings.php?f=update_settings` | High
31 | File | `/classes/Users.php?f=save` | High
32 | File | `/collection/all` | High
33 | File | `/Controller/Ajaxfileupload.ashx` | High
34 | File | `/detailed.php` | High
35 | File | `/dtale/chart-data/1` | High
36 | File | `/ecommerce/support_ticket` | High
37 | File | `/ecrire/exec/puce_statut.php` | High
38 | File | `/etc/shadow.sample` | High
39 | File | `/fftools/ffmpeg_enc.c` | High
40 | File | `/files/` | Low
41 | File | `/forms/doLogin` | High
42 | File | `/formSysLog` | Medium
43 | File | `/forum/away.php` | High
44 | File | `/friends/ajax_invite` | High
45 | File | `/goform/SetOnlineDevName` | High
46 | ... | ... | ...

There are 395 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/610bc7b082df417ed032f5f1
* https://de.darktrace.com/blog/the-last-of-its-kind-analysis-of-a-raccoon-stealer-v1-infection-part-1
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/raccoonstealer/raccoon_stealer_iocs_20220628.csv
* https://www.esentire.com/blog/d3f-ck-loader-the-new-maas-loader
* https://www.zerofox.com/blog/brief-raccoon-stealer-version-2-0/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
