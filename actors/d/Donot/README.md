# Donot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Donot](https://vuldb.com/?actor.donot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.donot](https://vuldb.com/?actor.donot)

## Campaigns

The following _campaigns_ are known and can be associated with Donot:

* DarkMusical
* Gedit

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Donot:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [CH](https://vuldb.com/?country.ch)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Donot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.135.19.26](https://vuldb.com/?ip.5.135.19.26) | - | - | High
2 | [5.135.199.0](https://vuldb.com/?ip.5.135.199.0) | - | - | High
3 | [37.48.122.145](https://vuldb.com/?ip.37.48.122.145) | - | Gedit | High
4 | [37.120.140.211](https://vuldb.com/?ip.37.120.140.211) | - | - | High
5 | [37.120.198.208](https://vuldb.com/?ip.37.120.198.208) | - | DarkMusical | High
6 | [37.139.3.130](https://vuldb.com/?ip.37.139.3.130) | - | - | High
7 | [37.139.28.208](https://vuldb.com/?ip.37.139.28.208) | - | - | High
8 | [45.33.29.133](https://vuldb.com/?ip.45.33.29.133) | li1046-133.members.linode.com | - | High
9 | [45.61.137.7](https://vuldb.com/?ip.45.61.137.7) | - | - | High
10 | [46.101.204.168](https://vuldb.com/?ip.46.101.204.168) | - | - | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Donot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Donot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin` | Low
3 | File | `/admin/?page=inmates/view_inmate` | High
4 | File | `/admin/?page=system_info` | High
5 | File | `/admin/?page=system_info/contact_info` | High
6 | File | `/admin/add_exercises.php` | High
7 | File | `/admin/conferences/get-all-status/` | High
8 | File | `/admin/conferences/list/` | High
9 | File | `/admin/countrymanagement.php` | High
10 | File | `/admin/edit.php` | High
11 | File | `/admin/general/change-lang` | High
12 | File | `/admin/group/list/` | High
13 | File | `/admin/lab.php` | High
14 | File | `/admin/new-content` | High
15 | File | `/Admin/News.php` | High
16 | File | `/admin/renewaldue.php` | High
17 | File | `/admin/sign/out` | High
18 | File | `/admin/usermanagement.php` | High
19 | File | `/adminPage/conf/saveCmd` | High
20 | File | `/admin_route/inc_service_credits.php` | High
21 | File | `/aqpg/users/login.php` | High
22 | File | `/artist-display.php` | High
23 | File | `/backups/` | Medium
24 | File | `/bcms/admin/?page=user/list` | High
25 | File | `/cardo/api` | Medium
26 | File | `/catcompany.php` | High
27 | File | `/CCMAdmin/serverlist.asp` | High
28 | File | `/cgi-bin/cstecgi.cgi` | High
29 | File | `/cgi-bin/editBookmark` | High
30 | File | `/cgi-bin/system_mgr.cgi` | High
31 | File | `/cgi-bin/touchlist_sync.cgi` | High
32 | File | `/cgi-bin/wlogin.cgi` | High
33 | File | `/cimom` | Low
34 | File | `/ci_spms/admin/category` | High
35 | File | `/classes/Users.php?f=save` | High
36 | File | `/cwms/admin/?page=articles/view_article/` | High
37 | File | `/cwms/classes/Master.php?f=save_contact` | High
38 | File | `/dashboard/add-blog.php` | High
39 | File | `/dashboard/add-portfolio.php` | High
40 | File | `/dashboard/settings` | High
41 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
42 | File | `/env` | Low
43 | File | `/film-rating.php` | High
44 | File | `/forum/away.php` | High
45 | File | `/front/roomtype-details.php` | High
46 | File | `/goform/fast_setting_wifi_set` | High
47 | ... | ... | ...

There are 412 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.cyble.com/2021/07/22/donot-apt-group-delivers-a-spyware-variant-of-chat-app/
* https://github.com/eset/malware-ioc/tree/master/donot
* https://github.com/faisalusuf/ThreatIntelligence/blob/main/APT%20DONOT%20TEAM/Tracking-DONOT-IOCs.csv
* https://twitter.com/ShadowChasing1/status/1497125743125413892
* https://www.cyfirma.com/outofband/donot-apt-elevates-its-tactics-by-deploying-malicious-android-apps-on-google-play-store/
* https://www.welivesecurity.com/2022/01/18/donot-go-do-not-respawn/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
