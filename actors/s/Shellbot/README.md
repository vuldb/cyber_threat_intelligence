# Shellbot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Shellbot](https://vuldb.com/?actor.shellbot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shellbot](https://vuldb.com/?actor.shellbot)

## Campaigns

The following _campaigns_ are known and can be associated with Shellbot:

* CVE-2020-17496

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Shellbot:

* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Shellbot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [34.225.57.146](https://vuldb.com/?ip.34.225.57.146) | ec2-34-225-57-146.compute-1.amazonaws.com | - | Medium
2 | [39.99.218.78](https://vuldb.com/?ip.39.99.218.78) | - | - | High
3 | [39.107.61.230](https://vuldb.com/?ip.39.107.61.230) | - | - | High
4 | [39.165.53.17](https://vuldb.com/?ip.39.165.53.17) | - | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Shellbot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Shellbot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.php` | Low
2 | File | `/admin/emp-profile-avatar.php` | High
3 | File | `/admin/network/wifi_schedule` | High
4 | File | `/admin/quote-details.php` | High
5 | File | `/admin/save.php` | High
6 | File | `/admin/team_save.php` | High
7 | File | `/admin/user/user-move-run.php` | High
8 | File | `/ajax.php?action=login` | High
9 | File | `/animalsadd.php` | High
10 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
11 | File | `/cgi-bin/web_index.cgi?lang=en&src=AwSystem.html&ertqVvnKV4TjU9Vt` | High
12 | File | `/chetc/shutdown` | High
13 | File | `/classes/Master.php?f=delete_product` | High
14 | File | `/classes/Users.php?f=save_user` | High
15 | File | `/cms/classes/Users.php?f=delete_client` | High
16 | File | `/control/activate.php` | High
17 | File | `/dashboard/admin/submit_payments.php` | High
18 | File | `/endpoint/delete-account.php` | High
19 | File | `/endpoint/delete-task.php` | High
20 | File | `/etc/networkd-dispatcher` | High
21 | File | `/goform/formLogDnsquery` | High
22 | ... | ... | ...

There are 181 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/49769/
* https://asec.ahnlab.com/en/57635/
* https://unit42.paloaltonetworks.com/cve-2020-17496/
* https://urlhaus.abuse.ch/url/3518097/
* https://urlhaus.abuse.ch/url/3518102/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
