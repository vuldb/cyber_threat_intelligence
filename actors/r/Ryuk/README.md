# Ryuk - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ryuk](https://vuldb.com/?actor.ryuk). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ryuk](https://vuldb.com/?actor.ryuk)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ryuk:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ryuk.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.137.182.114](https://vuldb.com/?ip.3.137.182.114) | ec2-3-137-182-114.us-east-2.compute.amazonaws.com | - | Medium
2 | [5.2.64.113](https://vuldb.com/?ip.5.2.64.113) | - | - | High
3 | [5.2.64.133](https://vuldb.com/?ip.5.2.64.133) | - | - | High
4 | [5.2.64.135](https://vuldb.com/?ip.5.2.64.135) | mail.chelseaf1oors.com | - | High
5 | [5.2.64.144](https://vuldb.com/?ip.5.2.64.144) | - | - | High
6 | [5.2.64.149](https://vuldb.com/?ip.5.2.64.149) | - | - | High
7 | [5.2.64.167](https://vuldb.com/?ip.5.2.64.167) | - | - | High
8 | [5.2.64.172](https://vuldb.com/?ip.5.2.64.172) | - | - | High
9 | [5.2.64.174](https://vuldb.com/?ip.5.2.64.174) | liteserver.netnik.eu | - | High
10 | [5.2.64.182](https://vuldb.com/?ip.5.2.64.182) | mx.egmose.net | - | High
11 | [5.2.70.149](https://vuldb.com/?ip.5.2.70.149) | - | - | High
12 | [5.2.72.200](https://vuldb.com/?ip.5.2.72.200) | - | - | High
13 | [5.2.72.202](https://vuldb.com/?ip.5.2.72.202) | vps2020nvme.pieterb.com | - | High
14 | [5.2.79.10](https://vuldb.com/?ip.5.2.79.10) | - | - | High
15 | [5.2.79.12](https://vuldb.com/?ip.5.2.79.12) | mail.suspicious-login-managepaypal.com | - | High
16 | [5.182.210.145](https://vuldb.com/?ip.5.182.210.145) | - | - | High
17 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
18 | [8.208.103.182](https://vuldb.com/?ip.8.208.103.182) | - | - | High
19 | [34.222.33.48](https://vuldb.com/?ip.34.222.33.48) | ec2-34-222-33-48.us-west-2.compute.amazonaws.com | - | Medium
20 | [45.34.6.225](https://vuldb.com/?ip.45.34.6.225) | unassigned.psychz.net | - | High
21 | [45.34.6.226](https://vuldb.com/?ip.45.34.6.226) | unassigned.psychz.net | - | High
22 | [45.138.172.95](https://vuldb.com/?ip.45.138.172.95) | - | - | High
23 | [45.141.84.120](https://vuldb.com/?ip.45.141.84.120) | - | - | High
24 | [45.147.228.77](https://vuldb.com/?ip.45.147.228.77) | - | - | High
25 | [45.147.229.52](https://vuldb.com/?ip.45.147.229.52) | - | - | High
26 | ... | ... | ... | ...

There are 98 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ryuk_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ryuk. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/` | Low
5 | File | `/admin/about-us.php` | High
6 | File | `/admin/action/delete-vaccine.php` | High
7 | File | `/admin/admin-update-employee.php` | High
8 | File | `/admin/edit-post.php` | High
9 | File | `/admin/index2.html` | High
10 | File | `/admin/userprofile.php` | High
11 | File | `/ajax.php?action=read_msg` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/clusters/local/topics/{topic}/messages` | High
14 | File | `/API/info` | Medium
15 | File | `/app/index/controller/Common.php` | High
16 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
17 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
18 | File | `/applications/nexus/modules/front/store/store.php` | High
19 | File | `/bitrix/admin/ldap_server_edit.php` | High
20 | File | `/cgi-bin/apkg_mgr.cgi` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/nas_sharing.cgi` | High
23 | File | `/cgi-bin/photocenter_mgr.cgi` | High
24 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
25 | File | `/cgi-bin/tosei_kikai.php` | High
26 | File | `/classes/Master.php` | High
27 | File | `/classes/Master.php?f=delete_record` | High
28 | File | `/classes/Master.php?f=save_category` | High
29 | File | `/classes/SystemSettings.php?f=update_settings` | High
30 | File | `/classes/Users.php?f=save` | High
31 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
32 | File | `/dcim/rack-roles/` | High
33 | File | `/debug/pprof` | Medium
34 | File | `/dist/index.js` | High
35 | File | `/dtale/chart-data/1` | High
36 | File | `/DXR.axd` | Medium
37 | File | `/etc/shadow.sample` | High
38 | File | `/EXCU_SHELL` | Medium
39 | File | `/fftools/ffmpeg_enc.c` | High
40 | File | `/forms/doLogin` | High
41 | File | `/formSysLog` | Medium
42 | File | `/forum/away.php` | High
43 | File | `/goform/aspForm` | High
44 | File | `/goform/modifyDhcpRule` | High
45 | File | `/goform/ModifyPppAuthWhiteMac` | High
46 | File | `/goform/net\_Web\_get_value` | High
47 | ... | ... | ...

There are 412 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/2020-10-29%20C2%20Ryuk.csv
* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-Ryuk.csv
* https://thedfirreport.com/2020/10/08/ryuks-return/
* https://thedfirreport.com/2020/10/18/ryuk-in-5-hours/
* https://thedfirreport.com/2020/11/05/ryuk-speed-run-2-hours-to-ransom/
* https://thedfirreport.com/2021/01/31/bazar-no-ryuk/
* https://twitter.com/TeamDreier/status/1378005931678699521
* https://www.crowdstrike.com/blog/wizard-spider-adds-new-feature-to-ryuk-ransomware/
* https://www.fortinet.com/blog/threat-research/ryuk-revisited-analysis-of-recent-ryuk-attack.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
