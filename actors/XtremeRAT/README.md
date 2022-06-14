# XtremeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [XtremeRAT](https://vuldb.com/?actor.xtremerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xtremerat](https://vuldb.com/?actor.xtremerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XtremeRAT:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XtremeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.79.71.205](https://vuldb.com/?ip.5.79.71.205) | - | - | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
3 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
4 | [23.32.81.118](https://vuldb.com/?ip.23.32.81.118) | a23-32-81-118.deploy.static.akamaitechnologies.com | - | High
5 | [23.62.7.138](https://vuldb.com/?ip.23.62.7.138) | a23-62-7-138.deploy.static.akamaitechnologies.com | - | High
6 | [62.90.21.54](https://vuldb.com/?ip.62.90.21.54) | 62-90-21-54.barak.net.il | - | High
7 | [64.29.151.221](https://vuldb.com/?ip.64.29.151.221) | hostedc40.carrierzone.com | - | High
8 | [65.55.44.109](https://vuldb.com/?ip.65.55.44.109) | - | - | High
9 | [71.95.133.164](https://vuldb.com/?ip.71.95.133.164) | 071-095-133-164.res.spectrum.com | - | High
10 | [71.226.96.253](https://vuldb.com/?ip.71.226.96.253) | c-71-226-96-253.hsd1.sc.comcast.net | - | High
11 | [72.22.185.201](https://vuldb.com/?ip.72.22.185.201) | - | - | High
12 | ... | ... | ... | ...

There are 45 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XtremeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XtremeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/car.php` | Medium
3 | File | `/cgi-bin/luci/api/auth` | High
4 | File | `/cgi-bin/luci/api/diagnose` | High
5 | File | `/CMD_ACCOUNT_ADMIN` | High
6 | File | `/core/admin/categories.php` | High
7 | File | `/dashboards/#` | High
8 | File | `/etc/config/image_sign` | High
9 | File | `/etc/controller-agent/agent.conf` | High
10 | File | `/etc/groups` | Medium
11 | File | `/etc/sudoers` | Medium
12 | File | `/filemanager/php/connector.php` | High
13 | File | `/forum/away.php` | High
14 | File | `/fudforum/adm/hlplist.php` | High
15 | File | `/GponForm/fsetup_Form` | High
16 | File | `/log_download.cgi` | High
17 | File | `/mgmt/tm/util/bash` | High
18 | File | `/modules/profile/index.php` | High
19 | File | `/MTFWU` | Low
20 | File | `/out.php` | Medium
21 | File | `/php/passport/index.php` | High
22 | File | `/public/plugins/` | High
23 | File | `/s/` | Low
24 | File | `/secure/QueryComponent!Default.jspa` | High
25 | File | `/server-info` | Medium
26 | File | `/tmp` | Low
27 | File | `/tmp/kamailio_ctl` | High
28 | File | `/tmp/kamailio_fifo` | High
29 | File | `/uncpath/` | Medium
30 | File | `/updown/upload.cgi` | High
31 | ... | ... | ...

There are 262 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/07/threat-roundup-0712-0719.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0719-0726.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0913-0920.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0424-0501.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0225-0304.html
* https://blog.talosintelligence.com/2022/05/threat-roundup-0429-0506.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
