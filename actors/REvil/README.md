# REvil - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [REvil](https://vuldb.com/?actor.revil). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revil](https://vuldb.com/?actor.revil)

## Campaigns

The following _campaigns_ are known and can be associated with REvil:

* CVE-2019-2725

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with REvil:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of REvil.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.230.195.226](https://vuldb.com/?ip.5.230.195.226) | - | - | High
2 | [18.223.199.234](https://vuldb.com/?ip.18.223.199.234) | ec2-18-223-199-234.us-east-2.compute.amazonaws.com | - | Medium
3 | [45.9.148.108](https://vuldb.com/?ip.45.9.148.108) | mx1.dendrite.network | - | High
4 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | - | High
5 | [45.33.18.44](https://vuldb.com/?ip.45.33.18.44) | li972-44.members.linode.com | - | High
6 | [45.33.20.235](https://vuldb.com/?ip.45.33.20.235) | li974-235.members.linode.com | - | High
7 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | - | High
8 | [45.33.30.197](https://vuldb.com/?ip.45.33.30.197) | li1047-197.members.linode.com | - | High
9 | [45.55.211.79](https://vuldb.com/?ip.45.55.211.79) | - | CVE-2019-2725 | High
10 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _REvil_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-425 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by REvil. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.htpasswd` | Medium
2 | File | `/ajax.php?action=read_msg` | High
3 | File | `/assets/something/services/AppModule.class` | High
4 | File | `/category_view.php` | High
5 | File | `/cgi-bin/nasset.cgi` | High
6 | File | `/cgi-bin/webadminget.cgi` | High
7 | File | `/cms/process.php` | High
8 | File | `/debug/pprof` | Medium
9 | File | `/DXR.axd` | Medium
10 | File | `/env` | Low
11 | File | `/etc/shadow` | Medium
12 | File | `/forum/away.php` | High
13 | File | `/goform/SetNetControlList` | High
14 | File | `/hrm/controller/employee.php` | High
15 | File | `/index.php/weblinks-categories` | High
16 | File | `/modules/profile/index.php` | High
17 | File | `/movie.php` | Medium
18 | File | `/public/login.htm` | High
19 | File | `/service/v1/createUser` | High
20 | File | `/show_news.php` | High
21 | File | `/src/chatbotapp/chatWindow.java` | High
22 | File | `/system?action=ServiceAdmin` | High
23 | File | `/uncpath/` | Medium
24 | File | `/web/entry/en/address/adrsSetUserWizard.cgi` | High
25 | File | `adclick.php` | Medium
26 | File | `admin.asp` | Medium
27 | File | `admin/categories_industry.php` | High
28 | File | `admin/class-woo-popup-admin.php` | High
29 | File | `admin/content/postcategory` | High
30 | File | `admin/index.php` | High
31 | File | `admin/settings.php` | High
32 | File | `admin/status/realtime/bandwidth_status` | High
33 | ... | ... | ...

There are 277 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/04/sodinokibi-ransomware-exploits-weblogic.html
* https://blogs.blackberry.com/en/2021/11/revil-under-the-microscope
* https://ddanchev.blogspot.com/2022/01/exposing-internet-connected_24.html
* https://thedfirreport.com/2021/03/29/sodinokibi-aka-revil-ransomware/
* https://www.darktrace.com/en/blog/darktraces-cyber-ai-analyst-investigates-sodinokibi-r-evil-ransomware/
* https://www.varonis.com/blog/revil-msp-supply-chain-attack/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
