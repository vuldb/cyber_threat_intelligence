# Wild Neutron - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Wild Neutron](https://vuldb.com/?actor.wild_neutron). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.wild_neutron](https://vuldb.com/?actor.wild_neutron)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wild Neutron:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wild Neutron.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [46.183.217.132](https://vuldb.com/?ip.46.183.217.132) | skalli.pereformed.com | - | High
2 | [64.187.225.231](https://vuldb.com/?ip.64.187.225.231) | 64-187-225-231.quickpacket.com | - | High
3 | [66.55.133.89](https://vuldb.com/?ip.66.55.133.89) | 66-55-133-89.choopa.net | - | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Wild Neutron_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Wild Neutron. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/admin.php` | Medium
4 | File | `/admin/config.php?display=disa&view=form` | High
5 | File | `/category_view.php` | High
6 | File | `/dev/kmem` | Medium
7 | File | `/dev/shm` | Medium
8 | File | `/file?action=download&file` | High
9 | File | `/medical/inventories.php` | High
10 | File | `/monitoring` | Medium
11 | File | `/NAGErrors` | Medium
12 | File | `/plugins/servlet/audit/resource` | High
13 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
14 | File | `/proc/ioports` | High
15 | File | `/replication` | Medium
16 | File | `/RestAPI` | Medium
17 | File | `/rom-0` | Low
18 | File | `/tmp` | Low
19 | File | `/tmp/speedtest_urls.xml` | High
20 | File | `/uncpath/` | Medium
21 | File | `/var/log/nginx` | High
22 | File | `/wp-admin/admin.php` | High
23 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
24 | File | `abook_database.php` | High
25 | File | `account.asp` | Medium
26 | File | `admin-ajax.php?action=get_wdtable order[0][dir]` | High
27 | File | `admin/index.php` | High
28 | File | `admin/login.php` | High
29 | File | `admincp.php?app=apps&do=save` | High
30 | File | `admincp.php?app=files` | High
31 | File | `admin\model\catalog\download.php` | High
32 | File | `ajax/render/widget_php` | High
33 | File | `apcupsd.pid` | Medium
34 | File | `api/sms/send-sms` | High
35 | File | `api/v1/alarms` | High
36 | File | `application/controller/InstallerController.php` | High
37 | ... | ... | ...

There are 313 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=WildNeutron_Economic_espionage.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
