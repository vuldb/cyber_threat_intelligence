# REvil - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [REvil](https://vuldb.com/?actor.revil). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revil](https://vuldb.com/?actor.revil)

## Campaigns

The following _campaigns_ are known and can be associated with REvil:

* WebLogic CVE-2019-2725

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with REvil:

* US
* DE
* RU
* ...

There are 7 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of REvil.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 5.230.195.226 | - | - | High
2 | 18.223.199.234 | ec2-18-223-199-234.us-east-2.compute.amazonaws.com | - | Medium
3 | 45.9.148.108 | mx1.dendrite.network | - | High
4 | 45.33.2.79 | li956-79.members.linode.com | - | High
5 | 45.33.18.44 | li972-44.members.linode.com | - | High
6 | 45.33.20.235 | li974-235.members.linode.com | - | High
7 | 45.33.23.183 | li977-183.members.linode.com | - | High
8 | 45.33.30.197 | li1047-197.members.linode.com | - | High
9 | 45.55.211.79 | - | WebLogic CVE-2019-2725 | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by REvil. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by REvil. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.htpasswd` | Medium
2 | File | `/category_view.php` | High
3 | File | `/cgi-bin/nasset.cgi` | High
4 | File | `/cgi-bin/webadminget.cgi` | High
5 | File | `/cms/process.php` | High
6 | File | `/etc/shadow` | Medium
7 | File | `/forum/away.php` | High
8 | File | `/goform/SetNetControlList` | High
9 | File | `/index.php/weblinks-categories` | High
10 | File | `/modules/profile/index.php` | High
11 | File | `/movie.php` | Medium
12 | File | `/public/login.htm` | High
13 | File | `/show_news.php` | High
14 | File | `/uncpath/` | Medium
15 | File | `adclick.php` | Medium
16 | File | `admin.asp` | Medium
17 | ... | ... | ...

There are 139 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/04/sodinokibi-ransomware-exploits-weblogic.html
* https://ddanchev.blogspot.com/2022/01/exposing-internet-connected_24.html
* https://www.darktrace.com/en/blog/darktraces-cyber-ai-analyst-investigates-sodinokibi-r-evil-ransomware/
* https://www.varonis.com/blog/revil-msp-supply-chain-attack/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!