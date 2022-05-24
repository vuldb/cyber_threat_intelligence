# Chthonic - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chthonic](https://vuldb.com/?actor.chthonic). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chthonic](https://vuldb.com/?actor.chthonic)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chthonic:

* [NL](https://vuldb.com/?country.nl)
* [JP](https://vuldb.com/?country.jp)
* [US](https://vuldb.com/?country.us)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chthonic.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.34.248.225](https://vuldb.com/?ip.5.34.248.225) | ns2.newsnet.li | - | High
2 | [5.39.81.111](https://vuldb.com/?ip.5.39.81.111) | pm.theglu.org | - | High
3 | [5.103.128.88](https://vuldb.com/?ip.5.103.128.88) | 5.103.128.88.static.fibianet.dk | - | High
4 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
5 | [13.107.246.13](https://vuldb.com/?ip.13.107.246.13) | - | - | High
6 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
7 | [20.41.46.145](https://vuldb.com/?ip.20.41.46.145) | - | - | High
8 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | - | High
9 | [23.236.62.147](https://vuldb.com/?ip.23.236.62.147) | 147.62.236.23.bc.googleusercontent.com | - | Medium
10 | [31.28.161.68](https://vuldb.com/?ip.31.28.161.68) | ntp.exact-time.org | - | High
11 | [34.107.221.82](https://vuldb.com/?ip.34.107.221.82) | 82.221.107.34.bc.googleusercontent.com | - | Medium
12 | [35.229.93.46](https://vuldb.com/?ip.35.229.93.46) | 46.93.229.35.bc.googleusercontent.com | - | Medium
13 | [35.231.151.7](https://vuldb.com/?ip.35.231.151.7) | 7.151.231.35.bc.googleusercontent.com | - | Medium
14 | [35.244.181.201](https://vuldb.com/?ip.35.244.181.201) | 201.181.244.35.bc.googleusercontent.com | - | Medium
15 | [37.187.5.167](https://vuldb.com/?ip.37.187.5.167) | ks3370497.kimsufi.com | - | High
16 | [37.187.20.28](https://vuldb.com/?ip.37.187.20.28) | ns397460.ip-37-187-20.eu | - | High
17 | [40.67.189.14](https://vuldb.com/?ip.40.67.189.14) | - | - | High
18 | [40.70.224.146](https://vuldb.com/?ip.40.70.224.146) | - | - | High
19 | [40.76.4.15](https://vuldb.com/?ip.40.76.4.15) | - | - | High
20 | [40.90.247.210](https://vuldb.com/?ip.40.90.247.210) | - | - | High
21 | [40.91.124.111](https://vuldb.com/?ip.40.91.124.111) | - | - | High
22 | [40.112.72.205](https://vuldb.com/?ip.40.112.72.205) | - | - | High
23 | [40.113.200.201](https://vuldb.com/?ip.40.113.200.201) | - | - | High
24 | [45.87.76.3](https://vuldb.com/?ip.45.87.76.3) | ntp.devrandom.be | - | High
25 | [46.17.46.226](https://vuldb.com/?ip.46.17.46.226) | brtnjbjgyi.quest | - | High
26 | ... | ... | ... | ...

There are 100 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chthonic_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chthonic. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/admin.php` | Medium
4 | File | `/admin/config.php?display=disa&view=form` | High
5 | File | `/category_view.php` | High
6 | File | `/dev/kmem` | Medium
7 | File | `/file?action=download&file` | High
8 | File | `/medical/inventories.php` | High
9 | File | `/monitoring` | Medium
10 | File | `/NAGErrors` | Medium
11 | File | `/plugins/servlet/audit/resource` | High
12 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
13 | File | `/proc/ioports` | High
14 | File | `/replication` | Medium
15 | File | `/RestAPI` | Medium
16 | File | `/rom-0` | Low
17 | File | `/tmp` | Low
18 | File | `/tmp/speedtest_urls.xml` | High
19 | File | `/tmp/zarafa-vacation-*` | High
20 | File | `/uncpath/` | Medium
21 | File | `/upload` | Low
22 | File | `/var/log/nginx` | High
23 | File | `/wp-admin/admin.php` | High
24 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
25 | File | `abook_database.php` | High
26 | File | `admin-ajax.php?action=get_wdtable order[0][dir]` | High
27 | File | `admin/index.php` | High
28 | File | `admin/login.php` | High
29 | File | `admin\model\catalog\download.php` | High
30 | File | `ajax/render/widget_php` | High
31 | File | `apcupsd.pid` | Medium
32 | File | `api/sms/send-sms` | High
33 | File | `api/v1/alarms` | High
34 | ... | ... | ...

There are 295 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
