# Chthonic - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chthonic](https://vuldb.com/?actor.chthonic). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chthonic](https://vuldb.com/?actor.chthonic)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chthonic:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chthonic.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.34.248.225](https://vuldb.com/?ip.5.34.248.225) | ns2.newsnet.li | - | High
2 | [5.39.81.111](https://vuldb.com/?ip.5.39.81.111) | pm.theglu.org | - | High
3 | [5.103.128.88](https://vuldb.com/?ip.5.103.128.88) | 5.103.128.88.static.fibianet.dk | - | High
4 | [5.199.135.170](https://vuldb.com/?ip.5.199.135.170) | ve1124.venus.servdiscount-customer.com | - | High
5 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
6 | [13.107.246.13](https://vuldb.com/?ip.13.107.246.13) | - | - | High
7 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
8 | [20.41.46.145](https://vuldb.com/?ip.20.41.46.145) | - | - | High
9 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | - | High
10 | [20.72.235.82](https://vuldb.com/?ip.20.72.235.82) | - | - | High
11 | [20.109.209.108](https://vuldb.com/?ip.20.109.209.108) | - | - | High
12 | [23.236.62.147](https://vuldb.com/?ip.23.236.62.147) | 147.62.236.23.bc.googleusercontent.com | - | Medium
13 | [31.28.161.68](https://vuldb.com/?ip.31.28.161.68) | ntp.exact-time.org | - | High
14 | [34.107.221.82](https://vuldb.com/?ip.34.107.221.82) | 82.221.107.34.bc.googleusercontent.com | - | Medium
15 | [35.229.93.46](https://vuldb.com/?ip.35.229.93.46) | 46.93.229.35.bc.googleusercontent.com | - | Medium
16 | [35.231.151.7](https://vuldb.com/?ip.35.231.151.7) | 7.151.231.35.bc.googleusercontent.com | - | Medium
17 | [35.244.181.201](https://vuldb.com/?ip.35.244.181.201) | 201.181.244.35.bc.googleusercontent.com | - | Medium
18 | [37.187.5.167](https://vuldb.com/?ip.37.187.5.167) | ks3370497.kimsufi.com | - | High
19 | [37.187.20.28](https://vuldb.com/?ip.37.187.20.28) | ns397460.ip-37-187-20.eu | - | High
20 | [40.67.189.14](https://vuldb.com/?ip.40.67.189.14) | - | - | High
21 | [40.70.224.146](https://vuldb.com/?ip.40.70.224.146) | - | - | High
22 | [40.76.4.15](https://vuldb.com/?ip.40.76.4.15) | - | - | High
23 | [40.90.247.210](https://vuldb.com/?ip.40.90.247.210) | - | - | High
24 | [40.91.124.111](https://vuldb.com/?ip.40.91.124.111) | - | - | High
25 | [40.112.72.205](https://vuldb.com/?ip.40.112.72.205) | - | - | High
26 | [40.113.200.201](https://vuldb.com/?ip.40.113.200.201) | - | - | High
27 | [45.87.76.3](https://vuldb.com/?ip.45.87.76.3) | ntp.devrandom.be | - | High
28 | [46.17.46.226](https://vuldb.com/?ip.46.17.46.226) | brtnjbjgyi.quest | - | High
29 | [46.54.224.12](https://vuldb.com/?ip.46.54.224.12) | ntp1.kate-wing.si | - | High
30 | ... | ... | ... | ...

There are 117 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chthonic_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chthonic. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/admin.php` | Medium
4 | File | `/admin/add-category.php` | High
5 | File | `/admin/read.php?mudi=getSignal` | High
6 | File | `/admin/subnets/ripe-query.php` | High
7 | File | `/apply.cgi` | Medium
8 | File | `/core/conditions/AbstractWrapper.java` | High
9 | File | `/debug/pprof` | Medium
10 | File | `/export` | Low
11 | File | `/file?action=download&file` | High
12 | File | `/hardware` | Medium
13 | File | `/librarian/bookdetails.php` | High
14 | File | `/medical/inventories.php` | High
15 | File | `/monitoring` | Medium
16 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
17 | File | `/plugin/LiveChat/getChat.json.php` | High
18 | File | `/plugins/servlet/audit/resource` | High
19 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
20 | File | `/replication` | Medium
21 | File | `/RestAPI` | Medium
22 | File | `/tmp/zarafa-vacation-*` | High
23 | File | `/uncpath/` | Medium
24 | File | `/upload` | Low
25 | File | `/user/loader.php?api=1` | High
26 | ... | ... | ...

There are 217 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/01/threat-roundup-0110-0117.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0501-0508.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0508-0515.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0821-0827.html
* https://blog.talosintelligence.com/2020/09/threat-roundup-0828-0904.html
* https://blog.talosintelligence.com/2020/11/threat-roundup-1030-1106.html
* https://blog.talosintelligence.com/2020/12/threat-roundup-1127-1204.html
* https://blog.talosintelligence.com/2021/01/threat-roundup-0122.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0903-0910.html
* https://blog.talosintelligence.com/2022/05/threat-roundup-0520-0527.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
