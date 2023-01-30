# CetaRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CetaRAT](https://vuldb.com/?actor.cetarat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cetarat](https://vuldb.com/?actor.cetarat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CetaRAT:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [SA](https://vuldb.com/?country.sa)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CetaRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [109.236.85.152](https://vuldb.com/?ip.109.236.85.152) | customer.worldstream.nl | - | High
2 | [161.97.142.96](https://vuldb.com/?ip.161.97.142.96) | vmi745943.contaboserver.net | - | High
3 | [164.68.104.126](https://vuldb.com/?ip.164.68.104.126) | vmd76303.contaboserver.net | - | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CetaRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CetaRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/admin.php` | Medium
4 | File | `/admin/subnets/ripe-query.php` | High
5 | File | `/core/conditions/AbstractWrapper.java` | High
6 | File | `/debug/pprof` | Medium
7 | File | `/export` | Low
8 | File | `/file?action=download&file` | High
9 | File | `/hardware` | Medium
10 | File | `/medical/inventories.php` | High
11 | File | `/monitoring` | Medium
12 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
13 | File | `/plugin/LiveChat/getChat.json.php` | High
14 | File | `/plugins/servlet/audit/resource` | High
15 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
16 | File | `/replication` | Medium
17 | File | `/RestAPI` | Medium
18 | File | `/tmp/speedtest_urls.xml` | High
19 | File | `/tmp/zarafa-vacation-*` | High
20 | File | `/uncpath/` | Medium
21 | File | `/upload` | Low
22 | File | `/user/loader.php?api=1` | High
23 | File | `/var/log/nginx` | High
24 | File | `/var/run/watchman.pid` | High
25 | ... | ... | ...

There are 206 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://s3.amazonaws.com/talos-intelligence-site/production/document_files/files/000/095/594/original/Network_IOCs_list_for_coverage.txt?1625657479

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
