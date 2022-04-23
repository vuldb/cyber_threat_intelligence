# LockBit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LockBit](https://vuldb.com/?actor.lockbit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lockbit](https://vuldb.com/?actor.lockbit)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LockBit:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LockBit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.91.83.176](https://vuldb.com/?ip.45.91.83.176) | - | - | High
2 | [45.227.255.190](https://vuldb.com/?ip.45.227.255.190) | - | - | High
3 | [88.80.147.102](https://vuldb.com/?ip.88.80.147.102) | - | - | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LockBit_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1557 | CWE-300 | Channel Accessible by Non-Endpoint | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LockBit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config.php?display=disa&view=form` | High
2 | File | `/cgi-bin/admin/testserver.cgi` | High
3 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
4 | File | `/export` | Low
5 | File | `/secure/QueryComponent!Default.jspa` | High
6 | File | `backend/Login/load/` | High
7 | ... | ... | ...

There are 43 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/hvs-consulting/ioc_signatures/blob/main/Proxyshell/HvS_Proxyshell_2021_09_IOCs.csv
* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-LockBit.csv
* https://www.ic3.gov/Media/News/2022/220204.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
