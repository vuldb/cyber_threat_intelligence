# BlackCat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlackCat](https://vuldb.com/?actor.blackcat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.blackcat](https://vuldb.com/?actor.blackcat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackCat:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [DE](https://vuldb.com/?country.de)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackCat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.46.245.56](https://vuldb.com/?ip.20.46.245.56) | - | - | High
2 | [23.106.223.97](https://vuldb.com/?ip.23.106.223.97) | - | - | High
3 | [37.120.238.58](https://vuldb.com/?ip.37.120.238.58) | - | - | High
4 | ... | ... | ... | ...

There are 12 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackCat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 11 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackCat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/admin/art/data.html` | High
2 | File | `/admin.php/admin/plog/index.html` | High
3 | File | `/admin.php/admin/ulog/index.html` | High
4 | File | `/admin.php/admin/website/data.html` | High
5 | File | `/admin.php?id=siteoptions&social=display&value=0&sid=2` | High
6 | File | `/admin.php?id=siteoptions&social=edit&sid=2` | High
7 | File | `/admin/inbox.php&action=read` | High
8 | File | `/admin/posts.php` | High
9 | File | `/admin/posts.php&action=delete` | High
10 | File | `/admin/run_ajax.php` | High
11 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
12 | File | `/admin/uesrs.php&&action=delete&userid=4` | High
13 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
14 | File | `/admin_page/all-files-update-ajax.php` | High
15 | File | `/api/crontab` | Medium
16 | File | `/blog/blog.php` | High
17 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
18 | File | `/cgi-bin/kerbynet` | High
19 | File | `/cloud_config/router_post/modify_account_pwd` | High
20 | File | `/cloud_config/router_post/register` | High
21 | File | `/config/list` | Medium
22 | File | `/download/` | Medium
23 | File | `/etc/ajenti/config.yml` | High
24 | File | `/etc/cobbler` | Medium
25 | File | `/etc/passwd` | Medium
26 | File | `/export` | Low
27 | File | `/goform/delAd` | High
28 | File | `/goform/form2Reboot.cgi` | High
29 | File | `/home.asp` | Medium
30 | ... | ... | ...

There are 259 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/03/from-blackmatter-to-blackcat-analyzing.html
* https://www.ic3.gov/Media/News/2022/220420.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
