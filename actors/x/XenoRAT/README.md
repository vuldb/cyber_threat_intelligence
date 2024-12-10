# XenoRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XenoRAT](https://vuldb.com/?actor.xenorat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xenorat](https://vuldb.com/?actor.xenorat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XenoRAT:

* [LA](https://vuldb.com/?country.la)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XenoRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.85.196](https://vuldb.com/?ip.2.58.85.196) | sunucuduragi.com | - | High
2 | [34.229.235.165](https://vuldb.com/?ip.34.229.235.165) | ec2-34-229-235-165.compute-1.amazonaws.com | - | Medium
3 | [45.66.231.63](https://vuldb.com/?ip.45.66.231.63) | - | - | High
4 | [45.133.174.133](https://vuldb.com/?ip.45.133.174.133) | - | - | High
5 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XenoRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XenoRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/accounts_con/register_account` | High
2 | File | `/admin/dl_sendmail.php` | High
3 | File | `/admin/file_manager/export` | High
4 | File | `/admin/index2.html` | High
5 | File | `/admin/info_deal.php` | High
6 | File | `/admin/user/manage_user.php` | High
7 | File | `/adminlogin.asp` | High
8 | File | `/adminPage/conf/reload` | High
9 | File | `/ajax/common.tabs.php` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/cron/settings/setJob/` | High
12 | File | `/api/RecordingList/DownloadRecord?file=` | High
13 | File | `/api/stl/actions/search` | High
14 | File | `/api/v2/cli/commands` | High
15 | File | `/api2/html/` | Medium
16 | File | `/app/ajax/sell_return_data.php` | High
17 | File | `/appsuite` | Medium
18 | File | `/CCMAdmin/serverlist.asp` | High
19 | File | `/cgi-bin/kerbynet` | High
20 | File | `/cgi-bin/koha/catalogue/search.pl` | High
21 | File | `/classes/Master.php?f=delete_inquiry` | High
22 | File | `/classes/SystemSettings.php?f=update_settings` | High
23 | File | `/conf/app.conf` | High
24 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
25 | File | `/DXR.axd` | Medium
26 | File | `/files/list-file` | High
27 | File | `/forum/away.php` | High
28 | File | `/goform/RGFirewallEL` | High
29 | File | `/index.php?menu=asterisk_cli` | High
30 | File | `/index/ajax/lang` | High
31 | File | `/interface/main/backup.php` | High
32 | File | `/item/item_con` | High
33 | File | `/job-details` | Medium
34 | File | `/jsoa/hntdCustomDesktopActionContent` | High
35 | File | `/log/decodmail.php` | High
36 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
37 | File | `/log_proxy` | Medium
38 | File | `/mailcleaner.php/getStats` | High
39 | ... | ... | ...

There are 337 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
