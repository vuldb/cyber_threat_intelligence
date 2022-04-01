# APT36 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT36](https://vuldb.com/?actor.apt36). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt36](https://vuldb.com/?actor.apt36)

## Campaigns

The following _campaigns_ are known and can be associated with APT36:

* C-Major
* Crimson RAT

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT36:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT36.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.189.137.8](https://vuldb.com/?ip.5.189.137.8) | vending.softjourn.if.ua | C-Major | High
2 | [5.189.143.225](https://vuldb.com/?ip.5.189.143.225) | - | C-Major | High
3 | [5.189.152.147](https://vuldb.com/?ip.5.189.152.147) | ccloud.armax.de | C-Major | High
4 | [5.189.167.23](https://vuldb.com/?ip.5.189.167.23) | mltx.de | C-Major | High
5 | [5.189.167.65](https://vuldb.com/?ip.5.189.167.65) | vmi437585.contaboserver.net | C-Major | High
6 | [23.254.119.11](https://vuldb.com/?ip.23.254.119.11) | - | - | High
7 | [64.188.12.126](https://vuldb.com/?ip.64.188.12.126) | 64.188.12.126.static.quadranet.com | - | High
8 | [64.188.25.205](https://vuldb.com/?ip.64.188.25.205) | 64.188.25.205.static.quadranet.com | Crimson RAT | High
9 | [64.188.25.232](https://vuldb.com/?ip.64.188.25.232) | 64.188.25.232.static.quadranet.com | - | High
10 | [75.98.175.79](https://vuldb.com/?ip.75.98.175.79) | a2s83.a2hosting.com | C-Major | High
11 | [75.119.139.169](https://vuldb.com/?ip.75.119.139.169) | server1.immacolata.com | - | High
12 | [80.240.134.51](https://vuldb.com/?ip.80.240.134.51) | - | C-Major | High
13 | ... | ... | ... | ...

There are 47 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT36_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT36. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/etc/sudoers` | Medium
2 | File | `/forum/away.php` | High
3 | File | `/inc/HTTPClient.php` | High
4 | File | `/out.php` | Medium
5 | File | `/products/details.asp` | High
6 | File | `/service/upload` | High
7 | File | `/uncpath/` | Medium
8 | File | `adclick.php` | Medium
9 | File | `add_comment.php` | High
10 | File | `admin/system_manage/save.html` | High
11 | File | `admin/sysUser/save.do?callbackType=closeCurrent&navTabId=sysUser/list` | High
12 | File | `administrator/components/com_media/helpers/media.php` | High
13 | File | `arm/t7xx/r5p0/mali_kbase_core_linux.c` | High
14 | File | `awstats.pl` | Medium
15 | File | `books.php` | Medium
16 | File | `bridge/yabbse.inc.php` | High
17 | File | `cachemgr.cgi` | Medium
18 | File | `captcha.php` | Medium
19 | File | `catagorie.php` | High
20 | File | `category.php` | Medium
21 | File | `cgi-bin/` | Medium
22 | File | `cgi-bin/cmh/webcam.sh` | High
23 | File | `channels/chan_skinny.c` | High
24 | File | `clwarn.cgi` | Medium
25 | File | `coders/dcm.c` | Medium
26 | File | `comment_add.asp` | High
27 | ... | ... | ...

There are 229 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.malwarebytes.com/threat-analysis/2020/03/apt36-jumps-on-the-coronavirus-bandwagon-delivers-crimson-rat/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.05.13/Transparent%20Tribe.pdf
* https://www.threatminer.org/report.php?q=indian-military-personnel-targeted-by-information-theft-campaign-cmajor.pdf&y=2016
* https://www.trendmicro.com/en_us/research/22/a/investigating-apt36-or-earth-karkaddans-attack-chain-and-malware.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
