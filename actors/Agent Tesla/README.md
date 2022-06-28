# Agent Tesla - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Agent Tesla](https://vuldb.com/?actor.agent_tesla). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.agent_tesla](https://vuldb.com/?actor.agent_tesla)

## Campaigns

The following _campaigns_ are known and can be associated with Agent Tesla:

* Phishing Korea

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Agent Tesla:

* [US](https://vuldb.com/?country.us)
* [CA](https://vuldb.com/?country.ca)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Agent Tesla.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.95.85.181](https://vuldb.com/?ip.23.95.85.181) | 23-95-85-181-host.colocrossing.com | - | High
2 | [31.3.251.197](https://vuldb.com/?ip.31.3.251.197) | h31-3-251-197.host.redstation.co.uk | - | High
3 | [31.209.137.12](https://vuldb.com/?ip.31.209.137.12) | smtp.vivaldi.net | - | High
4 | [37.19.196.108](https://vuldb.com/?ip.37.19.196.108) | unn-37-19-196-108.datapacket.com | - | High
5 | [45.142.215.180](https://vuldb.com/?ip.45.142.215.180) | connectoms.host | - | High
6 | [45.156.25.78](https://vuldb.com/?ip.45.156.25.78) | - | - | High
7 | [50.17.5.224](https://vuldb.com/?ip.50.17.5.224) | ec2-50-17-5-224.compute-1.amazonaws.com | - | Medium
8 | [51.68.128.171](https://vuldb.com/?ip.51.68.128.171) | ip171.ip-51-68-128.eu | - | High
9 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Agent Tesla_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Agent Tesla. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/api/addusers` | High
3 | File | `/cgi-bin/wapopen` | High
4 | File | `/controller/Index.php` | High
5 | File | `/etc/ajenti/config.yml` | High
6 | File | `/etc/sudoers` | Medium
7 | File | `/forum/away.php` | High
8 | File | `/goform/telnet` | High
9 | File | `/include/chart_generator.php` | High
10 | File | `/modules/profile/index.php` | High
11 | File | `/public/launchNewWindow.jsp` | High
12 | File | `/public/login.htm` | High
13 | File | `/rom-0` | Low
14 | File | `/tmp/connlicj.bin` | High
15 | File | `/tmp/phpglibccheck` | High
16 | File | `/uncpath/` | Medium
17 | File | `/usr/local/nagiosxi/html/includes/configwizards/windowswmi/windowswmi.inc.php` | High
18 | File | `/var/log/nginx` | High
19 | File | `/var/tmp/sess_*` | High
20 | File | `action.php` | Medium
21 | File | `actionphp/download.File.php` | High
22 | File | `add_comment.php` | High
23 | File | `admin.a6mambocredits.php` | High
24 | File | `admin.php` | Medium
25 | File | `admin/admin.php` | High
26 | File | `admin/content.php` | High
27 | File | `admin/import/class-import-settings.php` | High
28 | File | `admin/index.php?id=users/action=edit/user_id=1` | High
29 | File | `admin/sitesettings.php` | High
30 | File | `affich.php` | Medium
31 | File | `agent/Core/Controller/SendRequest.cpp` | High
32 | File | `akeyActivationLogin.do` | High
33 | File | `album_portal.php` | High
34 | File | `apache-auth.conf` | High
35 | File | `app/admin/routing/edit-bgp-mapping-search.php` | High
36 | File | `askapache-firefox-adsense.php` | High
37 | File | `assets/add/category.php` | High
38 | File | `attachment.cgi` | High
39 | File | `blueprints/sections/edit/1` | High
40 | File | `books.php` | Medium
41 | File | `btif_hd.cc` | Medium
42 | File | `cart.php` | Medium
43 | File | `cart_add.php` | Medium
44 | ... | ... | ...

There are 383 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/31083/
* https://blog.talosintelligence.com/2020/07/threat-roundup-0724-0731.html
* https://blogs.blackberry.com/en/2020/04/threat-spotlight-secret-agent-tesla
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-20%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-24%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-27%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-07%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-17%20Agent%20Tesla%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-20%20Agent%20Tesla%20IOCs
* https://github.com/netskopeoss/NetskopeThreatLabsIOCs/tree/main/AgentTesla/IOCs
* https://services.global.ntt/en-us/insights/blog/discovering-a-new-agent-tesla-malware-sample
* https://www.fortinet.com/blog/threat-research/phishing-campaign-targeting-korean-to-deliver-agent-tesla-new-variant

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
