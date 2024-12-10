# Latrodectus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Latrodectus](https://vuldb.com/?actor.latrodectus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.latrodectus](https://vuldb.com/?actor.latrodectus)

## Campaigns

The following _campaigns_ are known and can be associated with Latrodectus:

* ZaeCrypt

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Latrodectus:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Latrodectus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.47.86](https://vuldb.com/?ip.5.8.47.86) | rtuyrt.com | - | High
2 | [5.149.248.166](https://vuldb.com/?ip.5.149.248.166) | - | - | High
3 | [5.149.255.67](https://vuldb.com/?ip.5.149.255.67) | - | - | High
4 | [5.181.159.53](https://vuldb.com/?ip.5.181.159.53) | 5-181-159-53.mivocloud.com | - | High
5 | [5.252.21.207](https://vuldb.com/?ip.5.252.21.207) | vm2259505.stark-industries.solutions | - | High
6 | [5.255.101.33](https://vuldb.com/?ip.5.255.101.33) | - | - | High
7 | [23.227.202.187](https://vuldb.com/?ip.23.227.202.187) | 23-227-202-187.static.hvvc.us | - | High
8 | [23.227.203.161](https://vuldb.com/?ip.23.227.203.161) | 23-227-203-161.static.hvvc.us | - | High
9 | [23.254.201.238](https://vuldb.com/?ip.23.254.201.238) | hwsrv-1235958.hostwindsdns.com | - | High
10 | [23.254.230.8](https://vuldb.com/?ip.23.254.230.8) | hwsrv-1234109.hostwindsdns.com | - | High
11 | [37.221.67.152](https://vuldb.com/?ip.37.221.67.152) | alexhost0923.com | ZaeCrypt | High
12 | [45.143.166.23](https://vuldb.com/?ip.45.143.166.23) | - | - | High
13 | [45.143.166.66](https://vuldb.com/?ip.45.143.166.66) | - | - | High
14 | [45.143.166.85](https://vuldb.com/?ip.45.143.166.85) | - | - | High
15 | [45.143.166.95](https://vuldb.com/?ip.45.143.166.95) | - | - | High
16 | [45.143.166.161](https://vuldb.com/?ip.45.143.166.161) | - | - | High
17 | [45.143.166.190](https://vuldb.com/?ip.45.143.166.190) | - | - | High
18 | [45.143.167.157](https://vuldb.com/?ip.45.143.167.157) | - | - | High
19 | [46.19.143.153](https://vuldb.com/?ip.46.19.143.153) | greiatfamily.world | - | High
20 | [46.105.141.52](https://vuldb.com/?ip.46.105.141.52) | mail.ltdeskcontrol.com | - | High
21 | [46.105.141.53](https://vuldb.com/?ip.46.105.141.53) | ip53.ip-46-105-141.eu | - | High
22 | [51.91.35.147](https://vuldb.com/?ip.51.91.35.147) | ip147.ip-51-91-35.eu | - | High
23 | [51.91.35.153](https://vuldb.com/?ip.51.91.35.153) | ip153.ip-51-91-35.eu | - | High
24 | [51.161.207.168](https://vuldb.com/?ip.51.161.207.168) | ip168.ip-51-161-207.net | - | High
25 | ... | ... | ... | ...

There are 95 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Latrodectus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Latrodectus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add_new_invoice.php` | High
3 | File | `/admin.php/Admin/adminadd.html` | High
4 | File | `/admin/about-us.php` | High
5 | File | `/admin/action/delete-vaccine.php` | High
6 | File | `/admin/apply.php` | High
7 | File | `/admin/create-package.php` | High
8 | File | `/admin/doAdminAction.php?act=addCate` | High
9 | File | `/admin/edit-brand.php` | High
10 | File | `/admin/edit-post.php` | High
11 | File | `/admin/index2.html` | High
12 | File | `/admin/robot.php` | High
13 | File | `/admin/settings/save.php` | High
14 | File | `/admin/userprofile.php` | High
15 | File | `/api/baskets/{name}` | High
16 | File | `/app/index/controller/Common.php` | High
17 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
18 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
19 | File | `/applications/nexus/modules/front/store/store.php` | High
20 | File | `/apply.cgi` | Medium
21 | File | `/bitrix/admin/ldap_server_edit.php` | High
22 | File | `/cgi-bin/apkg_mgr.cgi` | High
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/nas_sharing.cgi` | High
25 | File | `/cgi-bin/photocenter_mgr.cgi` | High
26 | File | `/cgi-bin/wlogin.cgi` | High
27 | File | `/classes/Master.php` | High
28 | File | `/classes/Master.php?f=delete_record` | High
29 | File | `/classes/Master.php?f=save_category` | High
30 | File | `/classes/SystemSettings.php?f=update_settings` | High
31 | File | `/classes/Users.php?f=save` | High
32 | File | `/College/admin/teacher.php` | High
33 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
34 | File | `/dcim/rack-roles/` | High
35 | File | `/deal/{note_id}/note` | High
36 | File | `/detailed.php` | High
37 | File | `/dtale/chart-data/1` | High
38 | File | `/etc/shadow.sample` | High
39 | File | `/fftools/ffmpeg_enc.c` | High
40 | File | `/filter.php` | Medium
41 | File | `/forms/doLogin` | High
42 | File | `/formSysLog` | Medium
43 | File | `/forum/away.php` | High
44 | File | `/goform/addUserName` | High
45 | File | `/goform/aspForm` | High
46 | File | `/goform/ate` | Medium
47 | File | `/goform/delAd` | High
48 | File | `/goform/formSetWanNonLogin` | High
49 | File | `/goform/formWlanSetup` | High
50 | File | `/goform/SetOnlineDevName` | High
51 | ... | ... | ...

There are 446 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.reveng.ai/latrodectus-distribution-via-brc4/
* https://exchange.xforce.ibmcloud.com/report/details/guid:148d737a6c91bc5044f86b67195af527
* https://hunt.io/blog/latrodectus-malware-masquerades-as-ahnlab-security-software-to-infect-victims
* https://threatfox.abuse.ch
* https://www.malware-traffic-analysis.net/2024/03/07/index.html
* https://www.malware-traffic-analysis.net/2024/06/25/index.html
* https://www.netskope.com/blog/latrodectus-rapid-evolution-continues-with-latest-new-payload-features
* https://www.proofpoint.com/us/blog/threat-insight/latrodectus-spider-bytes-ice
* https://www.rapid7.com/blog/post/2024/07/24/malware-campaign-lures-users-with-fake-w2-form/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
