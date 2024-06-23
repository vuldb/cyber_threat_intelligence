# SilverFish - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SilverFish](https://vuldb.com/?actor.silverfish). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.silverfish](https://vuldb.com/?actor.silverfish)

## Campaigns

The following _campaigns_ are known and can be associated with SilverFish:

* SolarWinds

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SilverFish:

* [GB](https://vuldb.com/?country.gb)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SilverFish.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.57.152](https://vuldb.com/?ip.5.61.57.152) | - | SolarWinds | High
2 | [23.106.61.74](https://vuldb.com/?ip.23.106.61.74) | - | SolarWinds | High
3 | [37.48.84.156](https://vuldb.com/?ip.37.48.84.156) | - | - | High
4 | [38.135.104.189](https://vuldb.com/?ip.38.135.104.189) | h189-us104.fcsrv.net | - | High
5 | [74.72.74.142](https://vuldb.com/?ip.74.72.74.142) | cpe-74-72-74-142.nyc.res.rr.com | SolarWinds | High
6 | [79.110.52.138](https://vuldb.com/?ip.79.110.52.138) | - | - | High
7 | [79.110.52.139](https://vuldb.com/?ip.79.110.52.139) | - | - | High
8 | [79.110.52.140](https://vuldb.com/?ip.79.110.52.140) | - | - | High
9 | [81.4.122.101](https://vuldb.com/?ip.81.4.122.101) | comet.v1sor.com | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SilverFish_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SilverFish. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `.htaccess` | Medium
3 | File | `/.asp` | Low
4 | File | `/advanced/adv_dns.xgi` | High
5 | File | `/api/RecordingList/DownloadRecord?file=` | High
6 | File | `/api/v4/teams/TEAM_ID/top/team_members` | High
7 | File | `/apply.cgi` | Medium
8 | File | `/CFIDE/probe.cfm` | High
9 | File | `/cgi-bin/kerbynet` | High
10 | File | `/cgi-bin/wlogin.cgi` | High
11 | File | `/collection/all` | High
12 | File | `/conf/` | Low
13 | File | `/cupseasylive/statemodify.php` | High
14 | File | `/dashboard/add-service.php` | High
15 | File | `/dev/snd/seq` | Medium
16 | File | `/etc/passwd` | Medium
17 | File | `/etc/shadow.sample` | High
18 | File | `/goform/saveParentControlInfo` | High
19 | File | `/goform/SetFirewallCfg` | High
20 | File | `/goform/SysToolChangePwd` | High
21 | File | `/nidp/app/login` | High
22 | File | `/php/ping.php` | High
23 | File | `/pms/admin/crimes/manage_crime.php` | High
24 | File | `/proc` | Low
25 | File | `/release-x64/otfccdump` | High
26 | File | `/sbin/conf.d/SuSEconfig.javarunt` | High
27 | File | `/scripts/unlock_tasks.php` | High
28 | File | `/see_more_details.php` | High
29 | File | `/sitecore/shell/Invoke.aspx` | High
30 | File | `/SysInfo1.htm` | High
31 | File | `/sysinfo_json.cgi` | High
32 | File | `/system/user/modules/mod_users/controller.php` | High
33 | File | `/tmp` | Low
34 | File | `/uncpath/` | Medium
35 | File | `/usr/lib/utmp_update` | High
36 | File | `/usr/local` | Medium
37 | File | `/view/vpn/autovpn/sub_commit.php` | High
38 | File | `/wp-admin` | Medium
39 | File | `2020\Messages\SDNotify.exe` | High
40 | File | `adclick.php` | Medium
41 | File | `add-blog.php` | Medium
42 | ... | ... | ...

There are 360 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/SunBurst/SilverFish_Solarwinds.pdf
* https://www.prodaft.com/m/uploads/SilverFish_TLPWHITE.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
