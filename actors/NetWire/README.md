# NetWire - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [NetWire](https://vuldb.com/?actor.netwire). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.netwire](https://vuldb.com/?actor.netwire)

## Campaigns

The following _campaigns_ are known and can be associated with NetWire:

* Phishing

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NetWire:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 27 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NetWire.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.254.202.192](https://vuldb.com/?ip.23.254.202.192) | hwsrv-738718.hostwindsdns.com | - | High
2 | [37.0.11.206](https://vuldb.com/?ip.37.0.11.206) | - | - | High
3 | [37.46.150.139](https://vuldb.com/?ip.37.46.150.139) | - | - | High
4 | [37.139.64.106](https://vuldb.com/?ip.37.139.64.106) | - | - | High
5 | [45.144.225.219](https://vuldb.com/?ip.45.144.225.219) | - | - | High
6 | [79.134.225.52](https://vuldb.com/?ip.79.134.225.52) | - | - | High
7 | [89.249.74.213](https://vuldb.com/?ip.89.249.74.213) | - | - | High
8 | [94.103.80.254](https://vuldb.com/?ip.94.103.80.254) | v702647.hosted-by-vdsina.ru | - | High
9 | [103.150.8.54](https://vuldb.com/?ip.103.150.8.54) | - | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _NetWire_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by NetWire. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/../../conf/template/uhttpd.json` | High
3 | File | `/admin/contenttemp` | High
4 | File | `/admin/modules/system/custom_field.php` | High
5 | File | `/admin/web_config.php` | High
6 | File | `/api/crontab` | Medium
7 | File | `/bin/boa` | Medium
8 | File | `/cgi-bin/qcmap_auth` | High
9 | File | `/cgi-bin/wapopen` | High
10 | File | `/cgi-mod/lookup.cgi` | High
11 | File | `/cms/print.php` | High
12 | File | `/DataHandler/AM/AM_Handler.ashx` | High
13 | File | `/dev/dri/card1` | High
14 | File | `/etc/sudoers` | Medium
15 | File | `/export` | Low
16 | File | `/forum/away.php` | High
17 | File | `/iissamples` | Medium
18 | File | `/index.php` | Medium
19 | File | `/index.php?controller=calendar&format=raw&cat[0]=SQLi&task=events` | High
20 | File | `/login` | Low
21 | File | `/osm/REGISTER.cmd` | High
22 | File | `/product.php` | Medium
23 | File | `/public/plugins/` | High
24 | File | `/rom-0` | Low
25 | File | `/servlet/webacc` | High
26 | File | `/uncpath/` | Medium
27 | File | `/usr/bin/pkexec` | High
28 | File | `/usr/sbin/suexec` | High
29 | File | `/webconsole/Controller` | High
30 | File | `/webman/info.cgi` | High
31 | File | `/wp-admin/admin-ajax.php` | High
32 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
33 | File | `AAclAuthz.java` | High
34 | File | `ABuffer.cpp` | Medium
35 | File | `ActionsAndOperations` | High
36 | File | `adclick.php` | Medium
37 | File | `admin.php` | Medium
38 | File | `admin.php?page=languages` | High
39 | File | `admin/conf_users_edit.php` | High
40 | ... | ... | ...

There are 341 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2021/01/analysis-of-netwire-rat-campaign.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0416-0423.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0423-0430.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0625-0702.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0723-0730.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0813-0820.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0910-0917.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0917-0924.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1022-1029.html
* https://unit42.paloaltonetworks.jp/guloader-installing-netwire-rat/
* https://www.mandiant.com/resources/dissecting-netwire-phishing-campaigns-usage-process-hollowing

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
