# Mustang Panda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mustang Panda](https://vuldb.com/?actor.mustang_panda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mustang_panda](https://vuldb.com/?actor.mustang_panda)

## Campaigns

The following _campaigns_ are known and can be associated with Mustang Panda:

* Diànxùn
* Europe
* Hodur
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mustang Panda:

* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mustang Panda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.206.224.167](https://vuldb.com/?ip.5.206.224.167) | hardsysi | Europe | High
2 | [18.138.107.235](https://vuldb.com/?ip.18.138.107.235) | ec2-18-138-107-235.ap-southeast-1.compute.amazonaws.com | Europe | Medium
3 | [42.99.117.95](https://vuldb.com/?ip.42.99.117.95) | - | - | High
4 | [43.254.217.67](https://vuldb.com/?ip.43.254.217.67) | - | - | High
5 | [43.254.218.42](https://vuldb.com/?ip.43.254.218.42) | - | Hodur | High
6 | [45.32.50.150](https://vuldb.com/?ip.45.32.50.150) | 45.32.50.150.vultr.com | - | Medium
7 | [45.43.50.197](https://vuldb.com/?ip.45.43.50.197) | - | Europe | High
8 | [45.77.184.12](https://vuldb.com/?ip.45.77.184.12) | comm.phiu.pw | - | High
9 | [45.131.179.179](https://vuldb.com/?ip.45.131.179.179) | - | Hodur | High
10 | [45.134.83.41](https://vuldb.com/?ip.45.134.83.41) | - | PlugX | High
11 | [45.154.14.235](https://vuldb.com/?ip.45.154.14.235) | - | Hodur | High
12 | [45.248.87.14](https://vuldb.com/?ip.45.248.87.14) | - | - | High
13 | [45.248.87.162](https://vuldb.com/?ip.45.248.87.162) | - | Europe | High
14 | [46.8.198.134](https://vuldb.com/?ip.46.8.198.134) | - | Europe | High
15 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mustang Panda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mustang Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/cgi-bin/portal` | High
2 | File | `/Config/service/initModel?` | High
3 | File | `/export` | Low
4 | File | `/goform/NTPSyncWithHost` | High
5 | File | `/HNAP1/SetAccessPointMode` | High
6 | File | `/home/<user>/SecurityOnion/setup/so-setup` | High
7 | File | `/htmlcode/html/indexdefault.asp` | High
8 | File | `/include/helpers/upload.helper.php` | High
9 | File | `/interface/main/backup.php` | High
10 | File | `/local/domain/$DOMID` | High
11 | File | `/MTFWU` | Low
12 | File | `/rest/api/2/user/picker` | High
13 | File | `/service/upload` | High
14 | File | `/settings` | Medium
15 | File | `/tmp` | Low
16 | File | `/updater.php` | Medium
17 | File | `/uploads/dede` | High
18 | ... | ... | ...

There are 144 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/05/mustang-panda-targets-europe.html
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q2
* https://twitter.com/ESETresearch/status/1400165861973966854
* https://twitter.com/xorhex/status/1406496693735067650
* https://twitter.com/xorhex/status/1422815329684758537
* https://www.anomali.com/blog/china-based-apt-mustang-panda-targets-minority-groups-public-and-private-sector-organizations
* https://www.mcafee.com/enterprise/en-us/assets/reports/rp-operation-dianxun.pdf
* https://www.secureworks.com/blog/bronze-president-targets-russian-speakers-with-updated-plugx
* https://www.welivesecurity.com/2022/03/23/mustang-panda-hodur-old-tricks-new-korplug-variant/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
