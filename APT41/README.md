# APT41 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT41](https://vuldb.com/?actor.apt41). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt41](https://vuldb.com/?actor.apt41)

## Campaigns

The following _campaigns_ are known and can be associated with APT41:

* CVE-2019-19781
* MoonBounce

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT41:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT41.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.183.101.21](https://vuldb.com/?ip.5.183.101.21) | bestofgy.co.uk | MoonBounce | High
2 | [5.183.101.114](https://vuldb.com/?ip.5.183.101.114) | - | MoonBounce | High
3 | [5.183.103.122](https://vuldb.com/?ip.5.183.103.122) | - | MoonBounce | High
4 | [5.188.93.132](https://vuldb.com/?ip.5.188.93.132) | gcorelabs.paris.vpn015 | MoonBounce | High
5 | [5.188.108.22](https://vuldb.com/?ip.5.188.108.22) | pol1.htjsq.com | MoonBounce | High
6 | [5.188.108.228](https://vuldb.com/?ip.5.188.108.228) | xc5.exclusivacondominios.com | MoonBounce | High
7 | [5.189.222.33](https://vuldb.com/?ip.5.189.222.33) | spain466.es | MoonBounce | High
8 | [23.67.95.153](https://vuldb.com/?ip.23.67.95.153) | a23-67-95-153.deploy.static.akamaitechnologies.com | - | High
9 | [43.255.191.255](https://vuldb.com/?ip.43.255.191.255) | - | - | High
10 | [45.76.6.149](https://vuldb.com/?ip.45.76.6.149) | 45.76.6.149.vultr.com | - | Medium
11 | [45.76.75.219](https://vuldb.com/?ip.45.76.75.219) | 45.76.75.219.vultr.com | - | Medium
12 | [45.128.132.6](https://vuldb.com/?ip.45.128.132.6) | - | MoonBounce | High
13 | [45.128.135.15](https://vuldb.com/?ip.45.128.135.15) | - | MoonBounce | High
14 | [45.138.157.78](https://vuldb.com/?ip.45.138.157.78) | srv1.fincantleri.co | - | High
15 | [61.78.62.21](https://vuldb.com/?ip.61.78.62.21) | - | - | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by APT41. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT41. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/blade-log/api/list` | High
2 | File | `/category_view.php` | High
3 | File | `/cgi-bin/system_mgr.cgi` | High
4 | File | `/debug/pprof` | Medium
5 | File | `/etc/config/rpcd` | High
6 | File | `/forum/away.php` | High
7 | File | `/get_getnetworkconf.cgi` | High
8 | File | `/lists/admin/` | High
9 | File | `/login.cgi?logout=1` | High
10 | File | `/module/admin_logs` | High
11 | File | `/public/login.htm` | High
12 | File | `/public/plugins/` | High
13 | File | `/replication` | Medium
14 | File | `/SASWebReportStudio/logonAndRender.do` | High
15 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
16 | File | `/secure/admin/ViewInstrumentation.jspa` | High
17 | File | `/start-stop` | Medium
18 | File | `/tmp/app/.env` | High
19 | File | `/uncpath/` | Medium
20 | File | `/upload` | Low
21 | File | `/usr/bin/pkexec` | High
22 | File | `/WEB-INF/web.xml` | High
23 | File | `/wp-admin/admin-ajax.php` | High
24 | File | `/_next` | Low
25 | ... | ... | ...

There are 213 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.box.com/s/qtqlwejty7xz8wj8osz98webycgo5j9x
* https://github.com/blackberry/threat-research-and-intelligence/blob/main/APT41.csv
* https://github.com/eset/malware-ioc/tree/master/winnti_group
* https://media.kasperskycontenthub.com/wp-content/uploads/sites/43/2018/03/20134508/winnti-more-than-just-a-game-130410.pdf
* https://securelist.com/moonbounce-the-dark-side-of-uefi-firmware/105468/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.14/APT%2041.pdf
* https://www.fireeye.com/blog/threat-research/2020/03/apt41-initiates-global-intrusion-campaign-using-multiple-exploits.html
* https://www.threatminer.org/report.php?q=OfPigsandMalwareExaminingaPossibleMemberoftheWinntiGroup-TrendMicro.pdf&y=2017
* https://www.threatminer.org/report.php?q=WinntiAbusesGitHubforC&CCommunications-TrendMicro.pdf&y=2017
* https://www.threatminer.org/report.php?q=WinntiEvolution-GoingOpenSource-Protectwise.pdf&y=2017
* https://www.welivesecurity.com/2020/05/21/no-game-over-winnti-group/
* https://www.welivesecurity.com/2021/03/10/exchange-servers-under-siege-10-apt-groups/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
