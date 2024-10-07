# Latrodectus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Latrodectus](https://vuldb.com/?actor.latrodectus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.latrodectus](https://vuldb.com/?actor.latrodectus)

## Campaigns

The following _campaigns_ are known and can be associated with Latrodectus:

* ZaeCrypt

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Latrodectus:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 21 more country items available. Please use our online service to access the data.

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
21 | ... | ... | ... | ...

There are 79 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Latrodectus_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Latrodectus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin/about-us.php` | High
3 | File | `/admin/action/delete-vaccine.php` | High
4 | File | `/admin/doAdminAction.php?act=addCate` | High
5 | File | `/admin/edit-post.php` | High
6 | File | `/admin/index2.html` | High
7 | File | `/ajax/openvpn/activate_ovpncfg.php` | High
8 | File | `/api/baskets/{name}` | High
9 | File | `/app/Http/Controllers/ImageController.php` | High
10 | File | `/app/index/controller/Common.php` | High
11 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
12 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
13 | File | `/applications/nexus/modules/front/store/store.php` | High
14 | File | `/bitrix/admin/ldap_server_edit.php` | High
15 | File | `/books` | Low
16 | File | `/cgi-bin/apkg_mgr.cgi` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/downloadFile.cgi` | High
19 | File | `/cgi-bin/nas_sharing.cgi` | High
20 | File | `/cgi-bin/photocenter_mgr.cgi` | High
21 | File | `/classes/Master.php` | High
22 | File | `/classes/Master.php?f=delete_record` | High
23 | File | `/classes/Master.php?f=save_category` | High
24 | File | `/classes/SystemSettings.php?f=update_settings` | High
25 | File | `/classes/Users.php?f=save` | High
26 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
27 | File | `/dcim/rack-roles/` | High
28 | File | `/detailed.php` | High
29 | File | `/dipam/athlete-profile.php` | High
30 | File | `/dtale/chart-data/1` | High
31 | File | `/endpoint/update-bookmark.php` | High
32 | File | `/etc/shadow.sample` | High
33 | File | `/fftools/ffmpeg_enc.c` | High
34 | File | `/filter.php` | Medium
35 | File | `/forms/doLogin` | High
36 | File | `/formSysLog` | Medium
37 | File | `/forum/away.php` | High
38 | File | `/goform/SetOnlineDevName` | High
39 | File | `/h.php/page?ref=addtabs` | High
40 | File | `/image.php` | Medium
41 | File | `/includes/common/require_access_recovery.php` | High
42 | File | `/index.php` | Medium
43 | ... | ... | ...

There are 376 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.reveng.ai/latrodectus-distribution-via-brc4/
* https://exchange.xforce.ibmcloud.com/report/details/guid:148d737a6c91bc5044f86b67195af527
* https://hunt.io/blog/latrodectus-malware-masquerades-as-ahnlab-security-software-to-infect-victims
* https://threatfox.abuse.ch
* https://www.netskope.com/blog/latrodectus-rapid-evolution-continues-with-latest-new-payload-features
* https://www.proofpoint.com/us/blog/threat-insight/latrodectus-spider-bytes-ice
* https://www.rapid7.com/blog/post/2024/07/24/malware-campaign-lures-users-with-fake-w2-form/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
