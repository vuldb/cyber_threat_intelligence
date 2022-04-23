# Campaign C - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign C_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign C:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 25 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Campaign C or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign C.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [9.72.55.135](https://vuldb.com/?ip.9.72.55.135) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [10.12.122.62](https://vuldb.com/?ip.10.12.122.62) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [15.50.42.142](https://vuldb.com/?ip.15.50.42.142) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [16.61.28.46](https://vuldb.com/?ip.16.61.28.46) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [17.129.132.89](https://vuldb.com/?ip.17.129.132.89) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
6 | [18.42.73.26](https://vuldb.com/?ip.18.42.73.26) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [20.93.133.52](https://vuldb.com/?ip.20.93.133.52) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [21.58.89.27](https://vuldb.com/?ip.21.58.89.27) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [21.88.128.66](https://vuldb.com/?ip.21.88.128.66) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | ... | ... | ... | ...

There are 37 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign C. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign C. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%\totalcmd\TOTALCMD64.EXE` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/.env` | Low
4 | File | `/.ssh/authorized_keys` | High
5 | File | `/admin/default.asp` | High
6 | File | `/ajax/networking/get_netcfg.php` | High
7 | File | `/api/collection/findone` | High
8 | File | `/assets/ctx` | Medium
9 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
10 | File | `/cgi-sys/FormMail-clone.cgi` | High
11 | File | `/checkLogin.cgi` | High
12 | File | `/cms/print.php` | High
13 | File | `/concat?/%2557EB-INF/web.xml` | High
14 | File | `/data/remove` | Medium
15 | File | `/etc/passwd` | Medium
16 | File | `/goform/wlanPrimaryNetwork` | High
17 | File | `/login` | Low
18 | File | `/navigate/navigate_download.php` | High
19 | File | `/owa/auth/logon.aspx` | High
20 | File | `/p` | Low
21 | File | `/password.html` | High
22 | File | `/proc/ioports` | High
23 | File | `/property-list/property_view.php` | High
24 | File | `/ptms/classes/Users.php` | High
25 | File | `/rest` | Low
26 | File | `/rest/api/2/search` | High
27 | File | `/s/` | Low
28 | File | `/scripts/cpan_config` | High
29 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
30 | File | `/services/system/setup.json` | High
31 | File | `/uncpath/` | Medium
32 | File | `/var/WEB-GUI/cgi-bin/downloadfile.cgi` | High
33 | File | `/webconsole/APIController` | High
34 | File | `/websocket/exec` | High
35 | File | `/wp-admin/admin-ajax.php` | High
36 | File | `/wp-json` | Medium
37 | File | `/wp-json/oembed/1.0/embed?url` | High
38 | File | `/_next` | Low
39 | File | `4.edu.php\conn\function.php` | High
40 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
41 | File | `adclick.php` | Medium
42 | File | `addentry.php` | Medium
43 | File | `admin.php` | Medium
44 | File | `admin.php?c=update&f=unzip` | High
45 | File | `admin/category.inc.php` | High
46 | File | `admin/conf_users_edit.php` | High
47 | File | `admin/dl_sendmail.php` | High
48 | File | `admin/index.php` | High
49 | File | `admin/member_deal.php` | High
50 | ... | ... | ...

There are 431 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_C_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
