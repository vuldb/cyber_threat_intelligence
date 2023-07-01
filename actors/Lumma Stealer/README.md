# Lumma Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lumma Stealer](https://vuldb.com/?actor.lumma_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lumma_stealer](https://vuldb.com/?actor.lumma_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lumma Stealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lumma Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.161.155.121](https://vuldb.com/?ip.5.161.155.121) | static.121.155.161.5.clients.your-server.de | - | High
2 | [23.254.225.133](https://vuldb.com/?ip.23.254.225.133) | hwsrv-1067631.hostwindsdns.com | - | High
3 | [45.8.146.130](https://vuldb.com/?ip.45.8.146.130) | vm1266137.stark-industries.solutions | - | High
4 | [45.8.146.213](https://vuldb.com/?ip.45.8.146.213) | vm1266137.stark-industries.solutions | - | High
5 | [45.8.146.227](https://vuldb.com/?ip.45.8.146.227) | vm1266137.stark-industries.solutions | - | High
6 | [45.15.25.190](https://vuldb.com/?ip.45.15.25.190) | - | - | High
7 | ... | ... | ... | ...

There are 23 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lumma Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lumma Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/profile` | Medium
2 | File | `/api/RecordingList/DownloadRecord?file=` | High
3 | File | `/apply.cgi` | Medium
4 | File | `/dataset/data/{id}` | High
5 | File | `/debug/pprof` | Medium
6 | File | `/etc/grafana/grafana.ini` | High
7 | File | `/forum/PostPrivateMessage` | High
8 | File | `/nova/bin/igmp-proxy` | High
9 | File | `/orrs/admin/?page=user/manage_user` | High
10 | File | `/pages/processlogin.php` | High
11 | File | `/rapi/read_url` | High
12 | File | `/uncpath/` | Medium
13 | File | `/usr/local/psa/admin/sbin/wrapper` | High
14 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
15 | ... | ... | ...

There are 116 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://0xtoxin-labs.gitbook.io/malware-analysis/malware-analysis/lummac2-breakdown
* https://app.any.run/tasks/4e682046-d702-46c7-91c5-6f2a6c9a0909/
* https://app.any.run/tasks/9a53fdba-8af6-4d2c-9c2b-e5b86fa34e8b
* https://app.any.run/tasks/330d3bb4-cb91-4311-8bf3-f3d8db2712fb
* https://app.any.run/tasks/b80c5c12-9c12-414d-be8e-818ffdab1e74
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=45.8.146.130
* https://tracker.viriback.com/index.php?q=45.8.146.213
* https://tracker.viriback.com/index.php?q=45.8.146.227
* https://tracker.viriback.com/index.php?q=82.118.23.50
* https://tracker.viriback.com/index.php?q=85.239.62.218
* https://tracker.viriback.com/index.php?q=94.142.138.26
* https://tracker.viriback.com/index.php?q=185.99.133.246
* https://twitter.com/Ishusoka/status/1649716132822089728
* https://twitter.com/sekoia_io/status/1572889505497223169

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
