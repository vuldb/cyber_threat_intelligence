# Tropic Trooper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Tropic Trooper](https://vuldb.com/?actor.tropic_trooper). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tropic_trooper](https://vuldb.com/?actor.tropic_trooper)

## Campaigns

The following _campaigns_ are known and can be associated with Tropic Trooper:

* Poison Ivy
* USBferry

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tropic Trooper:

* [US](https://vuldb.com/?country.us)
* [HK](https://vuldb.com/?country.hk)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tropic Trooper.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.196.132.154](https://vuldb.com/?ip.10.196.132.154) | - | - | High
2 | [23.27.112.216](https://vuldb.com/?ip.23.27.112.216) | - | Poison Ivy | High
3 | [23.234.27.100](https://vuldb.com/?ip.23.234.27.100) | - | - | High
4 | [27.126.176.169](https://vuldb.com/?ip.27.126.176.169) | - | - | High
5 | [27.126.186.74](https://vuldb.com/?ip.27.126.186.74) | krakow.intellectint.net | - | High
6 | [27.126.186.222](https://vuldb.com/?ip.27.126.186.222) | grupos.slidefresh.net | - | High
7 | [43.129.177.152](https://vuldb.com/?ip.43.129.177.152) | - | - | High
8 | [43.134.194.237](https://vuldb.com/?ip.43.134.194.237) | - | - | High
9 | [43.154.74.7](https://vuldb.com/?ip.43.154.74.7) | - | - | High
10 | [43.154.85.5](https://vuldb.com/?ip.43.154.85.5) | - | - | High
11 | [43.154.88.192](https://vuldb.com/?ip.43.154.88.192) | - | - | High
12 | [45.32.47.148](https://vuldb.com/?ip.45.32.47.148) | 45.32.47.148.vultr.com | - | Medium
13 | [45.76.218.247](https://vuldb.com/?ip.45.76.218.247) | 45.76.218.247.vultrusercontent.com | - | Medium
14 | [45.77.178.47](https://vuldb.com/?ip.45.77.178.47) | 45.77.178.47.vultrusercontent.com | - | Medium
15 | [45.77.214.244](https://vuldb.com/?ip.45.77.214.244) | - | - | High
16 | [45.125.12.147](https://vuldb.com/?ip.45.125.12.147) | spk.cloudie.hk | - | High
17 | ... | ... | ... | ...

There are 62 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Tropic Trooper_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Tropic Trooper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?p=/Area/index#tab=t2` | High
2 | File | `/dist/index.js` | High
3 | File | `/ecommerce/admin/settings/setDiscount.php` | High
4 | File | `/shell` | Low
5 | ... | ... | ...

There are 33 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/369/tropic-trooper-apt-iocs/
* https://citizenlab.ca/2016/11/parliament-keyboy/
* https://citizenlab.ca/2018/08/familiar-feeling-a-malware-campaign-targeting-the-tibetan-diaspora-resurfaces/
* https://documents.trendmicro.com/assets/Tech-Brief-Tropic-Trooper-s-Back-USBferry-Attack-Targets-Air-gapped-Environments.pdf
* https://github.com/citizenlab/malware-indicators/blob/master/201808_FamiliarFeeling/indicators.csv
* https://unit42.paloaltonetworks.com/unit42-tropic-trooper-targets-taiwanese-government-and-fossil-fuel-provider-with-poison-ivy/
* https://www.anomali.com/blog/anomali-suspects-that-china-backed-apt-pirate-panda-may-be-seeking-access-to-vietnam-government-data-center#When:15:00:00Z
* https://www.pwc.co.uk/issues/cyber-security-services/research/the-keyboys-are-back-in-town.html
* https://www.threatminer.org/report.php?q=It%E2%80%99sParliamentary_KeyBoyandthetargetingoftheTibetanCommunity-TheCitizenLab.pdf&y=2016
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/l/collecting-in-the-dark-tropic-trooper-targets-transportation-and-government-organizations/IOCs-Collecting-in-the-dark-Tropic-Trooper.txt
* https://www.trendmicro.de/cloud-content/us/pdfs/security-intelligence/white-papers/wp-operation-tropic-trooper.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
