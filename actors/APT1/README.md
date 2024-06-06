# APT1 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT1](https://vuldb.com/?actor.apt1). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt1](https://vuldb.com/?actor.apt1)

## Campaigns

The following _campaigns_ are known and can be associated with APT1:

* Mandiant
* Oceansalt

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT1:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [IL](https://vuldb.com/?country.il)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT1.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.236.62.147](https://vuldb.com/?ip.23.236.62.147) | 147.62.236.23.bc.googleusercontent.com | - | Medium
2 | [27.102.112.179](https://vuldb.com/?ip.27.102.112.179) | - | Oceansalt | High
3 | [58.246.0.0](https://vuldb.com/?ip.58.246.0.0) | - | Mandiant | High
4 | [58.247.0.0](https://vuldb.com/?ip.58.247.0.0) | - | Mandiant | High
5 | [67.222.16.131](https://vuldb.com/?ip.67.222.16.131) | host.dnsweb.org | - | High
6 | [100.42.216.230](https://vuldb.com/?ip.100.42.216.230) | tfs2480.sipnav.in | - | High
7 | [101.80.0.0](https://vuldb.com/?ip.101.80.0.0) | - | Mandiant | High
8 | [101.81.0.0](https://vuldb.com/?ip.101.81.0.0) | - | Mandiant | High
9 | [101.82.0.0](https://vuldb.com/?ip.101.82.0.0) | - | Mandiant | High
10 | [101.83.0.0](https://vuldb.com/?ip.101.83.0.0) | - | Mandiant | High
11 | [101.84.0.0](https://vuldb.com/?ip.101.84.0.0) | - | Mandiant | High
12 | [101.85.0.0](https://vuldb.com/?ip.101.85.0.0) | - | Mandiant | High
13 | [101.86.0.0](https://vuldb.com/?ip.101.86.0.0) | - | Mandiant | High
14 | [101.87.0.0](https://vuldb.com/?ip.101.87.0.0) | - | Mandiant | High
15 | [101.88.0.0](https://vuldb.com/?ip.101.88.0.0) | - | Mandiant | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT1_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT1. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/upload` | Medium
2 | File | `/php/ping.php` | High
3 | File | `/public/plugins/` | High
4 | File | `/systemrw/` | Medium
5 | File | `adm/boardgroup_form_update.php` | High
6 | ... | ... | ...

There are 34 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* http://cdn0.vox-cdn.com/assets/4589853/crowdstrike-intelligence-report-putter-panda.original.pdf
* https://www.circleid.com/posts/20201215-revisiting-apt1-iocs-with-dns-and-subdomain-intelligence/
* https://www.fireeye.com/content/dam/fireeye-www/services/pdfs/mandiant-apt1-report.pdf
* https://www.mcafee.com/enterprise/en-us/assets/reports/rp-operation-oceansalt.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
