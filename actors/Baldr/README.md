# Baldr - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Baldr](https://vuldb.com/?actor.baldr). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.baldr](https://vuldb.com/?actor.baldr)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Baldr:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Baldr.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.88.198](https://vuldb.com/?ip.5.8.88.198) | - | - | High
2 | [5.45.73.87](https://vuldb.com/?ip.5.45.73.87) | - | - | High
3 | [5.188.60.7](https://vuldb.com/?ip.5.188.60.7) | - | - | High
4 | [5.188.60.18](https://vuldb.com/?ip.5.188.60.18) | - | - | High
5 | [5.188.60.24](https://vuldb.com/?ip.5.188.60.24) | - | - | High
6 | [5.188.60.30](https://vuldb.com/?ip.5.188.60.30) | - | - | High
7 | [5.188.60.54](https://vuldb.com/?ip.5.188.60.54) | - | - | High
8 | [5.188.60.68](https://vuldb.com/?ip.5.188.60.68) | - | - | High
9 | [5.188.60.74](https://vuldb.com/?ip.5.188.60.74) | - | - | High
10 | [5.188.60.101](https://vuldb.com/?ip.5.188.60.101) | - | - | High
11 | [5.188.60.115](https://vuldb.com/?ip.5.188.60.115) | - | - | High
12 | [5.188.60.206](https://vuldb.com/?ip.5.188.60.206) | - | - | High
13 | [5.188.231.96](https://vuldb.com/?ip.5.188.231.96) | - | - | High
14 | [5.188.231.210](https://vuldb.com/?ip.5.188.231.210) | - | - | High
15 | [18.207.217.146](https://vuldb.com/?ip.18.207.217.146) | ec2-18-207-217-146.compute-1.amazonaws.com | - | Medium
16 | [18.221.49.166](https://vuldb.com/?ip.18.221.49.166) | ec2-18-221-49-166.us-east-2.compute.amazonaws.com | - | Medium
17 | [23.19.58.101](https://vuldb.com/?ip.23.19.58.101) | - | - | High
18 | [23.95.95.61](https://vuldb.com/?ip.23.95.95.61) | 23-95-95-61-host.colocrossing.com | - | High
19 | [23.254.217.112](https://vuldb.com/?ip.23.254.217.112) | hwsrv-930282.hostwindsdns.com | - | High
20 | [23.254.225.240](https://vuldb.com/?ip.23.254.225.240) | sha29.phpautomailer.com | - | High
21 | [45.64.186.10](https://vuldb.com/?ip.45.64.186.10) | 45-64-186-10.static.bangmod-idc.com | - | High
22 | [45.77.252.143](https://vuldb.com/?ip.45.77.252.143) | 45.77.252.143.vultr.com | - | Medium
23 | [46.30.42.130](https://vuldb.com/?ip.46.30.42.130) | assetshub.com | - | High
24 | [46.249.62.196](https://vuldb.com/?ip.46.249.62.196) | - | - | High
25 | ... | ... | ... | ...

There are 97 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Baldr_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Baldr. This data is unique as it uses our predictive model for actor profiling.

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
9 | File | `/medical/inventories.php` | High
10 | File | `/monitoring` | Medium
11 | File | `/NAGErrors` | Medium
12 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
13 | File | `/plugin/LiveChat/getChat.json.php` | High
14 | File | `/plugins/servlet/audit/resource` | High
15 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
16 | File | `/replication` | Medium
17 | File | `/RestAPI` | Medium
18 | File | `/tmp` | Low
19 | File | `/tmp/speedtest_urls.xml` | High
20 | File | `/tmp/zarafa-vacation-*` | High
21 | File | `/uncpath/` | Medium
22 | File | `/upload` | Low
23 | File | `/var/log/nginx` | High
24 | File | `/var/run/watchman.pid` | High
25 | File | `/viewer/krpano.html` | High
26 | File | `/wp-json/oembed/1.0/embed?url` | High
27 | File | `admin-ajax.php?action=get_wdtable order[0][dir]` | High
28 | File | `admin\model\catalog\download.php` | High
29 | ... | ... | ...

There are 245 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Stealer-Baldr

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
