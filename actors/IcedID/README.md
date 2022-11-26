# IcedID - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [IcedID](https://vuldb.com/?actor.icedid). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.icedid](https://vuldb.com/?actor.icedid)

## Campaigns

The following _campaigns_ are known and can be associated with IcedID:

* Cobalt Strike

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with IcedID:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of IcedID.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.46.161](https://vuldb.com/?ip.5.61.46.161) | - | - | High
2 | [5.149.252.179](https://vuldb.com/?ip.5.149.252.179) | hnh7.arenal.xyz | - | High
3 | [31.24.224.12](https://vuldb.com/?ip.31.24.224.12) | 1f18e00c.setaptr.net | - | High
4 | [31.24.228.170](https://vuldb.com/?ip.31.24.228.170) | 31.24.228.170.static.midphase.com | - | High
5 | [31.184.199.11](https://vuldb.com/?ip.31.184.199.11) | dalesmanager.com | - | High
6 | [37.120.222.100](https://vuldb.com/?ip.37.120.222.100) | - | - | High
7 | [45.129.99.241](https://vuldb.com/?ip.45.129.99.241) | 354851-vds-mamozw.gmhost.pp.ua | - | High
8 | [45.138.172.179](https://vuldb.com/?ip.45.138.172.179) | - | - | High
9 | [45.147.228.198](https://vuldb.com/?ip.45.147.228.198) | - | - | High
10 | [45.147.230.82](https://vuldb.com/?ip.45.147.230.82) | - | - | High
11 | [45.147.230.88](https://vuldb.com/?ip.45.147.230.88) | mailnode7.bulletproof-mail.biz | - | High
12 | [45.147.231.113](https://vuldb.com/?ip.45.147.231.113) | - | - | High
13 | [45.153.240.135](https://vuldb.com/?ip.45.153.240.135) | - | - | High
14 | [45.153.241.115](https://vuldb.com/?ip.45.153.241.115) | - | - | High
15 | [46.17.98.191](https://vuldb.com/?ip.46.17.98.191) | - | - | High
16 | [46.249.62.199](https://vuldb.com/?ip.46.249.62.199) | - | - | High
17 | [79.141.161.176](https://vuldb.com/?ip.79.141.161.176) | zzs7bp73.copycomdigital.com | - | High
18 | [79.141.164.241](https://vuldb.com/?ip.79.141.164.241) | x6ts.mtsgamingpro.fun | - | High
19 | [79.141.166.39](https://vuldb.com/?ip.79.141.166.39) | webimpa.com | - | High
20 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _IcedID_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by IcedID. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?&m=Public&a=login` | High
2 | File | `/api/` | Low
3 | File | `/config/getuser` | High
4 | File | `/management/api/rcx_management/global_config_query` | High
5 | File | `/setSystemAdmin` | High
6 | ... | ... | ...

There are 40 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/04/icedid-banking-trojan.html
* https://cert.gov.ua/article/39609
* https://isc.sans.edu/forums/diary/Analysis+from+March+2021+Traffic+Analysis+Quiz/27232/
* https://isc.sans.edu/forums/diary/Emotet+infection+with+IcedID+banking+Trojan/24312/
* https://isc.sans.edu/forums/diary/Emotet+infections+and+followup+malware/24532/
* https://isc.sans.edu/forums/diary/Malspam+links+to+passwordprotected+Word+docs+that+push+IcedID+Bokbot/24428/
* https://isc.sans.edu/forums/diary/Malspam+with+links+to+Word+docs+pushes+IcedID+Bokbot/25640/
* https://isc.sans.edu/forums/diary/Malspam+with+passwordprotected+word+docs+still+pushing+IcedID+Bokbot+with+Trickbot/24708/
* https://isc.sans.edu/forums/diary/Microsoft+Word+document+with+malicious+macro+pushes+IcedID+Bokbot/26146/
* https://isc.sans.edu/forums/diary/One+Emotet+infection+leads+to+three+followup+malware+infections/24140/
* https://research.checkpoint.com/2021/melting-ice-tracking-icedid-servers-with-a-few-simple-steps/
* https://thedfirreport.com/2021/07/19/icedid-and-cobalt-strike-vs-antivirus/
* https://thedfirreport.com/2021/10/18/icedid-to-xinglocker-ransomware-in-24-hours/
* https://www.cybereason.com/blog/cybereason-vs.-quantum-locker-ransomware

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
