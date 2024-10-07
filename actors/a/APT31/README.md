# APT31 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT31](https://vuldb.com/?actor.apt31). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt31](https://vuldb.com/?actor.apt31)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT31:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [SG](https://vuldb.com/?country.sg)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT31.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.252.176.102](https://vuldb.com/?ip.5.252.176.102) | no-rdns.mivocloud.com | - | High
2 | [20.11.11.67](https://vuldb.com/?ip.20.11.11.67) | - | - | High
3 | [45.147.229.194](https://vuldb.com/?ip.45.147.229.194) | - | - | High
4 | [50.71.100.164](https://vuldb.com/?ip.50.71.100.164) | S010690a7c1a10cf2.wp.shawcable.net | - | High
5 | [58.96.237.98](https://vuldb.com/?ip.58.96.237.98) | - | - | High
6 | [58.182.61.137](https://vuldb.com/?ip.58.182.61.137) | 137.61.182.58.starhub.net.sg | - | High
7 | [68.146.18.127](https://vuldb.com/?ip.68.146.18.127) | S010690a7c1b6e041.cg.shawcable.net | - | High
8 | [71.64.151.132](https://vuldb.com/?ip.71.64.151.132) | cpe-71-64-151-132.cinci.res.rr.com | - | High
9 | [73.229.137.54](https://vuldb.com/?ip.73.229.137.54) | c-73-229-137-54.hsd1.co.comcast.net | - | High
10 | [78.82.247.37](https://vuldb.com/?ip.78.82.247.37) | 78-82-247-37.customers.ownit.se | - | High
11 | [81.83.4.48](https://vuldb.com/?ip.81.83.4.48) | d51530430.static.telenet.be | - | High
12 | [81.227.88.108](https://vuldb.com/?ip.81.227.88.108) | 81-227-88-108-no2661.tbcn.telia.com | - | High
13 | [81.232.51.161](https://vuldb.com/?ip.81.232.51.161) | 81-232-51-161-no600.tbcn.telia.com | - | High
14 | [81.234.227.62](https://vuldb.com/?ip.81.234.227.62) | 81-234-227-62-no551.tbcn.telia.com | - | High
15 | ... | ... | ... | ...

There are 56 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT31_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-29 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT31. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/api/RecordingList/DownloadRecord?file=` | High
3 | File | `/apply.cgi` | Medium
4 | File | `/cgi-bin/cstecgi.cgi` | High
5 | File | `/etc/openstack-dashboard/local_settings` | High
6 | File | `/get_getnetworkconf.cgi` | High
7 | File | `/goform/RgDhcp` | High
8 | File | `/goform/RGFirewallEL` | High
9 | File | `/horde/util/go.php` | High
10 | File | `/php/ping.php` | High
11 | File | `/rapi/read_url` | High
12 | File | `/scripts/unlock_tasks.php` | High
13 | File | `/SysInfo1.htm` | High
14 | File | `/sysinfo_json.cgi` | High
15 | File | `/system/dictData/loadDictItem` | High
16 | File | `/system/user/modules/mod_users/controller.php` | High
17 | File | `/uncpath/` | Medium
18 | ... | ... | ...

There are 149 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.infoblox.com/cyber-threat-intelligence/cyber-threat-advisory-apt31-targeting-france/
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/2021-11-10%20APT31%20IOCs.csv
* https://www.ptsecurity.com/ww-en/analytics/pt-esc-threat-intelligence/apt31-new-attacks/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
