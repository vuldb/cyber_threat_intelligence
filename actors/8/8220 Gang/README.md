# 8220 Gang - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [8220 Gang](https://vuldb.com/?actor.8220_gang). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.8220_gang](https://vuldb.com/?actor.8220_gang)

## Campaigns

The following _campaigns_ are known and can be associated with 8220 Gang:

* CVE-2017-10271 / CVE-2020-14883
* CVE-2019-2725
* CVE-2022-26134

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with 8220 Gang:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of 8220 Gang.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.67.29](https://vuldb.com/?ip.5.42.67.29) | - | - | High
2 | [51.79.175.139](https://vuldb.com/?ip.51.79.175.139) | vps-dc8b0481.vps.ovh.ca | CVE-2022-26134 | High
3 | [51.222.111.116](https://vuldb.com/?ip.51.222.111.116) | vps-373fb9eb.vps.ovh.ca | CVE-2017-10271 / CVE-2020-14883 | High
4 | [51.255.171.23](https://vuldb.com/?ip.51.255.171.23) | vps-fc1a1567.vps.ovh.net | CVE-2022-26134 | High
5 | [64.227.170.227](https://vuldb.com/?ip.64.227.170.227) | - | CVE-2017-10271 / CVE-2020-14883 | High
6 | [77.91.84.42](https://vuldb.com/?ip.77.91.84.42) | goodvpn.aeza.network | - | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _8220 Gang_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by 8220 Gang. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES%\MyQ\PHP\Sessions\` | High
2 | File | `.htaccess` | Medium
3 | File | `//proc/kcore` | Medium
4 | File | `/add_new_invoice.php` | High
5 | File | `/admin/about-us.php` | High
6 | File | `/admin/action/delete-vaccine.php` | High
7 | File | `/Admin/akun_edit.php` | High
8 | File | `/admin/apply.php` | High
9 | File | `/admin/create-package.php` | High
10 | File | `/admin/doAdminAction.php?act=addCate` | High
11 | File | `/admin/edit-brand.php` | High
12 | File | `/admin/edit-post.php` | High
13 | File | `/admin/index2.html` | High
14 | File | `/admin/notes/create` | High
15 | File | `/admin/pages/list` | High
16 | File | `/Admin/Proses_Edit_Akun.php` | High
17 | File | `/admin/robot.php` | High
18 | File | `/admin/search-invoices.php` | High
19 | File | `/admin/userprofile.php` | High
20 | File | `/admin_class.php` | High
21 | File | `/alphaware/summary.php` | High
22 | File | `/api/baskets/{name}` | High
23 | File | `/api/swaggerui/static` | High
24 | File | `/app/index/controller/Common.php` | High
25 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
26 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
27 | File | `/applications/nexus/modules/front/store/store.php` | High
28 | File | `/bitrix/admin/ldap_server_edit.php` | High
29 | File | `/cgi-bin/apkg_mgr.cgi` | High
30 | File | `/cgi-bin/cstecgi.cgi` | High
31 | File | `/cgi-bin/nas_sharing.cgi` | High
32 | File | `/cgi-bin/photocenter_mgr.cgi` | High
33 | File | `/classes/Master.php` | High
34 | File | `/classes/Master.php?f=delete_record` | High
35 | File | `/classes/Master.php?f=save_category` | High
36 | File | `/classes/SystemSettings.php?f=update_settings` | High
37 | File | `/classes/Users.php?f=save` | High
38 | File | `/command_port.ini` | High
39 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
40 | File | `/cupseasylive/countrymodify.php` | High
41 | File | `/dcim/rack-roles/` | High
42 | File | `/deal/{note_id}/note` | High
43 | File | `/detailed.php` | High
44 | File | `/domains/list` | High
45 | File | `/dtale/chart-data/1` | High
46 | File | `/etc/shadow.sample` | High
47 | File | `/fftools/ffmpeg_enc.c` | High
48 | File | `/filter.php` | Medium
49 | File | `/forms/doLogin` | High
50 | File | `/formSysLog` | Medium
51 | ... | ... | ...

There are 442 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/503/8220-botnet-iocs/
* https://asec.ahnlab.com/en/36820/
* https://asec.ahnlab.com/en/51568/
* https://blog.checkpoint.com/2022/06/09/crypto-miners-leveraging-atlassian-zero-day-vulnerability/
* https://blog.projectdiscovery.io/zimbra-remote-code-execution/
* https://blog.xlab.qianxin.com/8220-k4spreader-new-tool-en/
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/8220Gang/8220_Gang_iocs_20242409.csv
* https://github.com/uptycslabs/IOCs/blob/main/8220Gang
* https://www.sentinelone.com/blog/8220-gang-cloud-botnet-targets-misconfigured-cloud-workloads/
* https://www.sentinelone.com/blog/soc-team-essentials-how-to-investigate-and-track-the-8220-gang-cloud-threat/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
