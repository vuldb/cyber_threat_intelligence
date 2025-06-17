# Magic Hound - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magic Hound](https://vuldb.com/?actor.magic_hound). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magic_hound](https://vuldb.com/?actor.magic_hound)

## Campaigns

The following _campaigns_ are known and can be associated with Magic Hound:

* PupyRAT
* Rocket Kitten
* Saffron Rose

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magic Hound:

* [US](https://vuldb.com/?country.us)
* [IR](https://vuldb.com/?country.ir)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Magic Hound.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.244.151](https://vuldb.com/?ip.5.9.244.151) | static.151.244.9.5.clients.your-server.de | Saffron Rose | High
2 | [5.39.223.227](https://vuldb.com/?ip.5.39.223.227) | - | Rocket Kitten | High
3 | [5.145.151.1](https://vuldb.com/?ip.5.145.151.1) | ip-5-145-151-1.hosts.businesscomnetworks.com | Rocket Kitten | High
4 | [5.145.151.2](https://vuldb.com/?ip.5.145.151.2) | ip-5-145-151-2.hosts.businesscomnetworks.com | Rocket Kitten | High
5 | [5.145.151.3](https://vuldb.com/?ip.5.145.151.3) | ip-5-145-151-3.hosts.businesscomnetworks.com | Rocket Kitten | High
6 | [5.145.151.4](https://vuldb.com/?ip.5.145.151.4) | ip-5-145-151-4.hosts.businesscomnetworks.com | Rocket Kitten | High
7 | [5.145.151.5](https://vuldb.com/?ip.5.145.151.5) | ip-5-145-151-5.hosts.businesscomnetworks.com | Rocket Kitten | High
8 | [5.145.151.6](https://vuldb.com/?ip.5.145.151.6) | ip-5-145-151-6.hosts.businesscomnetworks.com | Rocket Kitten | High
9 | [5.145.151.7](https://vuldb.com/?ip.5.145.151.7) | ip-5-145-151-7.hosts.businesscomnetworks.com | Rocket Kitten | High
10 | [31.192.105.10](https://vuldb.com/?ip.31.192.105.10) | - | Rocket Kitten | High
11 | [45.32.186.33](https://vuldb.com/?ip.45.32.186.33) | 45.32.186.33.vultr.com | PupyRAT | Medium
12 | [45.56.123.129](https://vuldb.com/?ip.45.56.123.129) | li941-129.members.linode.com | - | High
13 | [45.58.37.142](https://vuldb.com/?ip.45.58.37.142) | - | - | High
14 | [45.76.128.165](https://vuldb.com/?ip.45.76.128.165) | 45.76.128.165.vultr.com | - | Medium
15 | [69.87.223.26](https://vuldb.com/?ip.69.87.223.26) | - | - | High
16 | [81.17.28.227](https://vuldb.com/?ip.81.17.28.227) | - | Saffron Rose | High
17 | [81.17.28.229](https://vuldb.com/?ip.81.17.28.229) | - | Saffron Rose | High
18 | [81.17.28.231](https://vuldb.com/?ip.81.17.28.231) | - | Saffron Rose | High
19 | [81.17.28.235](https://vuldb.com/?ip.81.17.28.235) | - | Saffron Rose | High
20 | [84.11.146.52](https://vuldb.com/?ip.84.11.146.52) | host-84-11-146-52.customer.teleport-iabg.de | Rocket Kitten | High
21 | ... | ... | ... | ...

There are 82 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Magic Hound_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magic Hound. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/curriculum/view_curriculum.php` | High
2 | File | `/admin/departments/view_department.php` | High
3 | File | `/Admin/login.php` | High
4 | File | `/admin/students/manage.php` | High
5 | File | `/admin/user/manage_user.php` | High
6 | ... | ... | ...

There are 40 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.checkpoint.com/wp-content/uploads/2015/11/rocket-kitten-report.pdf
* https://unit42.paloaltonetworks.com/unit42-magic-hound-campaign-attacks-saudi-targets/
* https://www.fireeye.com/content/dam/fireeye-www/global/en/current-threats/pdfs/rpt-operation-saffron-rose.pdf
* https://www.secureworks.com/blog/iranian-pupyrat-bites-middle-eastern-organizations
* https://www.threatminer.org/report.php?q=fireeye-operation-saffron-rose.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
