# Ficker Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ficker Stealer](https://vuldb.com/?actor.ficker_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ficker_stealer](https://vuldb.com/?actor.ficker_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ficker Stealer:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ficker Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.212.247](https://vuldb.com/?ip.2.56.212.247) | - | - | High
2 | [5.178.2.214](https://vuldb.com/?ip.5.178.2.214) | - | - | High
3 | [8.208.86.224](https://vuldb.com/?ip.8.208.86.224) | - | - | High
4 | [8.209.71.17](https://vuldb.com/?ip.8.209.71.17) | - | - | High
5 | [8.211.195.96](https://vuldb.com/?ip.8.211.195.96) | - | - | High
6 | [34.65.142.243](https://vuldb.com/?ip.34.65.142.243) | 243.142.65.34.bc.googleusercontent.com | - | Medium
7 | [34.90.166.4](https://vuldb.com/?ip.34.90.166.4) | 4.166.90.34.bc.googleusercontent.com | - | Medium
8 | [34.91.253.186](https://vuldb.com/?ip.34.91.253.186) | 186.253.91.34.bc.googleusercontent.com | - | Medium
9 | [34.94.171.115](https://vuldb.com/?ip.34.94.171.115) | 115.171.94.34.bc.googleusercontent.com | - | Medium
10 | [34.106.112.240](https://vuldb.com/?ip.34.106.112.240) | 240.112.106.34.bc.googleusercontent.com | - | Medium
11 | [35.203.73.169](https://vuldb.com/?ip.35.203.73.169) | 169.73.203.35.bc.googleusercontent.com | - | Medium
12 | [35.228.242.21](https://vuldb.com/?ip.35.228.242.21) | 21.242.228.35.bc.googleusercontent.com | - | Medium
13 | [37.0.8.225](https://vuldb.com/?ip.37.0.8.225) | avilalee.cartierevannucci.com | - | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ficker Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ficker Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `..\WWWRoot\CustomPages\aspshell.asp` | High
2 | File | `/agc/vicidial.php` | High
3 | File | `/cgi-bin/viewcert` | High
4 | File | `/console/ConsolePage/Master.html` | High
5 | File | `/cstecgi.cgi` | Medium
6 | File | `/forum/away.php` | High
7 | File | `/freelance/resume_list` | High
8 | File | `/img/main.cgi` | High
9 | File | `/index.php` | Medium
10 | File | `/pms/admin/crimes/manage_crime.php` | High
11 | File | `/sitecore/shell/Invoke.aspx` | High
12 | File | `/spip.php` | Medium
13 | File | `/TemplateManager/indexExternalLocation.jsp` | High
14 | File | `/uncpath/` | Medium
15 | File | `/userman/inbox.php` | High
16 | File | `/usr/sbin/nagios` | High
17 | File | `/var/log/nginx` | High
18 | File | `/var/run/docker.sock` | High
19 | File | `/web/api/v1/upload/UploadHandler.php` | High
20 | File | `/_vti_bin/_vti_log` | High
21 | File | `adclick.php` | Medium
22 | File | `addentry.php` | Medium
23 | File | `addtocart.asp` | High
24 | File | `add_bookmark.php` | High
25 | File | `admin.php` | Medium
26 | File | `admin/adm/test.php` | High
27 | File | `admin/admin.shtml` | High
28 | File | `admin/general.php` | High
29 | File | `admincp.php?app=prop&do=add` | High
30 | File | `administrator/components/com_media/helpers/media.php` | High
31 | File | `adminlogin.asp` | High
32 | File | `Adminstrator/Users/Edit/` | High
33 | File | `advsearch.php` | High
34 | File | `agora.cgi` | Medium
35 | File | `AppDMClient` | Medium
36 | File | `append/override_content_security_policy_directives` | High
37 | File | `authent.php4` | Medium
38 | File | `base/ErrorHandler.php` | High
39 | ... | ... | ...

There are 339 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/53eb34b5a1decc113a67803db9a49cc844958fe9d33b645183b870f5d1ac7901/
* https://threatfox.abuse.ch
* https://twitter.com/0xrb/status/1627623872832086016?s=20
* https://urlhaus.abuse.ch/url/918649/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
