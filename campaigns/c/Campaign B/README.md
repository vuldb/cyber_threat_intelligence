# Campaign B - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign B_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign B:

* [NZ](https://vuldb.com/?country.nz)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Campaign B or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign B.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.27.122.119](https://vuldb.com/?ip.5.27.122.119) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [12.52.19.59](https://vuldb.com/?ip.12.52.19.59) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [16.52.54.140](https://vuldb.com/?ip.16.52.54.140) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [16.58.49.129](https://vuldb.com/?ip.16.58.49.129) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [18.50.115.97](https://vuldb.com/?ip.18.50.115.97) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
6 | [20.38.100.106](https://vuldb.com/?ip.20.38.100.106) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [22.20.28.56](https://vuldb.com/?ip.22.20.28.56) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [25.31.92.107](https://vuldb.com/?ip.25.31.92.107) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [25.117.33.82](https://vuldb.com/?ip.25.117.33.82) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [26.119.92.7](https://vuldb.com/?ip.26.119.92.7) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign B. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign B. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\Steam` | High
2 | File | `/admin/` | Low
3 | File | `/admin/action/update-deworm.php` | High
4 | File | `/admin/add-category.php` | High
5 | File | `/admin/edit.php` | High
6 | File | `/admin/orders/update_status.php` | High
7 | File | `/api/1.0/rest/language_configuration` | High
8 | File | `/api/baskets/{name}` | High
9 | File | `/api/filemanager` | High
10 | File | `/api/v2/cli/commands` | High
11 | File | `/application/index/controller/Screen.php` | High
12 | File | `/billing/home.php` | High
13 | File | `/cgi-bin/koha/catalogue/search.pl` | High
14 | File | `/cgi-bin/nas_sharing.cgi` | High
15 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
16 | File | `/cgi-bin/system_mgr.cgi` | High
17 | File | `/cgi-bin/wapopen` | High
18 | File | `/cgi-bin/wlogin.cgi` | High
19 | File | `/DXR.axd` | Medium
20 | File | `/etc/tomcat8/Catalina/attack` | High
21 | File | `/filemanager/upload.php` | High
22 | File | `/fileupload/upload.cfm` | High
23 | File | `/forum/away.php` | High
24 | File | `/home/cavesConsole` | High
25 | File | `/home/masterConsole` | High
26 | File | `/home/playerOperate` | High
27 | File | `/importexport.php` | High
28 | File | `/items/search` | High
29 | File | `/mgmt/tm/util/bash` | High
30 | ... | ... | ...

There are 251 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_B_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
