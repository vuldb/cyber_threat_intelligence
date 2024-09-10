# Baldr - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Baldr](https://vuldb.com/?actor.baldr). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.baldr](https://vuldb.com/?actor.baldr)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Baldr:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Baldr.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.23.82.72](https://vuldb.com/?ip.1.23.82.72) | - | - | High
2 | [2.2.82.64](https://vuldb.com/?ip.2.2.82.64) | - | - | High
3 | [2.12.51.56](https://vuldb.com/?ip.2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | - | High
4 | [3.95.29.25](https://vuldb.com/?ip.3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | - | Medium
5 | [4.96.46.65](https://vuldb.com/?ip.4.96.46.65) | - | - | High
6 | [5.8.88.198](https://vuldb.com/?ip.5.8.88.198) | - | - | High
7 | [5.45.73.87](https://vuldb.com/?ip.5.45.73.87) | - | - | High
8 | [5.188.60.7](https://vuldb.com/?ip.5.188.60.7) | - | - | High
9 | [5.188.60.18](https://vuldb.com/?ip.5.188.60.18) | - | - | High
10 | [5.188.60.24](https://vuldb.com/?ip.5.188.60.24) | - | - | High
11 | [5.188.60.30](https://vuldb.com/?ip.5.188.60.30) | - | - | High
12 | [5.188.60.54](https://vuldb.com/?ip.5.188.60.54) | - | - | High
13 | [5.188.60.68](https://vuldb.com/?ip.5.188.60.68) | - | - | High
14 | [5.188.60.74](https://vuldb.com/?ip.5.188.60.74) | - | - | High
15 | [5.188.60.101](https://vuldb.com/?ip.5.188.60.101) | - | - | High
16 | [5.188.60.115](https://vuldb.com/?ip.5.188.60.115) | - | - | High
17 | [5.188.60.206](https://vuldb.com/?ip.5.188.60.206) | - | - | High
18 | [5.188.231.96](https://vuldb.com/?ip.5.188.231.96) | - | - | High
19 | [5.188.231.210](https://vuldb.com/?ip.5.188.231.210) | - | - | High
20 | [18.207.217.146](https://vuldb.com/?ip.18.207.217.146) | ec2-18-207-217-146.compute-1.amazonaws.com | - | Medium
21 | [18.221.49.166](https://vuldb.com/?ip.18.221.49.166) | ec2-18-221-49-166.us-east-2.compute.amazonaws.com | - | Medium
22 | [19.2.45.3](https://vuldb.com/?ip.19.2.45.3) | - | - | High
23 | [21.15.46.55](https://vuldb.com/?ip.21.15.46.55) | - | - | High
24 | [23.19.58.101](https://vuldb.com/?ip.23.19.58.101) | - | - | High
25 | [23.95.95.61](https://vuldb.com/?ip.23.95.95.61) | 23-95-95-61-host.colocrossing.com | - | High
26 | [23.254.217.112](https://vuldb.com/?ip.23.254.217.112) | hwsrv-930282.hostwindsdns.com | - | High
27 | ... | ... | ... | ...

There are 103 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Baldr_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Baldr. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/admin.php` | Medium
4 | File | `/admin/subnets/ripe-query.php` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/core/conditions/AbstractWrapper.java` | High
7 | File | `/debug/pprof` | Medium
8 | File | `/export` | Low
9 | File | `/file?action=download&file` | High
10 | File | `/hardware` | Medium
11 | File | `/librarian/bookdetails.php` | High
12 | File | `/medical/inventories.php` | High
13 | File | `/monitoring` | Medium
14 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
15 | File | `/plugin/LiveChat/getChat.json.php` | High
16 | File | `/plugins/servlet/audit/resource` | High
17 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
18 | File | `/replication` | Medium
19 | File | `/RestAPI` | Medium
20 | File | `/tmp/speedtest_urls.xml` | High
21 | File | `/tmp/zarafa-vacation-*` | High
22 | File | `/uncpath/` | Medium
23 | File | `/upload` | Low
24 | File | `/user/loader.php?api=1` | High
25 | File | `/var/log/nginx` | High
26 | ... | ... | ...

There are 221 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Stealer-Baldr

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
