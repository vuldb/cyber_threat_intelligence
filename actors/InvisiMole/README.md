# InvisiMole - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [InvisiMole](https://vuldb.com/?actor.invisimole). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.invisimole](https://vuldb.com/?actor.invisimole)

## Campaigns

The following _campaigns_ are known and can be associated with InvisiMole:

* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with InvisiMole:

* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* [ES](https://vuldb.com/?country.es)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of InvisiMole.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.95.11.34](https://vuldb.com/?ip.45.95.11.34) | vds2103.zevshost.net | Ukraine | High
2 | [46.165.230.241](https://vuldb.com/?ip.46.165.230.241) | - | - | High
3 | [46.165.231.85](https://vuldb.com/?ip.46.165.231.85) | - | - | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _InvisiMole_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by InvisiMole. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\OpenVPN Connect\drivers\tap\amd64\win10` | High
2 | File | `.htaccess` | Medium
3 | File | `/.env` | Low
4 | File | `/api/CONFIG/restore` | High
5 | File | `/cgi-bin/activate.cgi` | High
6 | File | `/cgi-bin/bcm_password` | High
7 | File | `/cgi-bin/nobody` | High
8 | File | `/cgi-bin/nobody/Search.cgi` | High
9 | File | `/cgi-bin/webproc` | High
10 | File | `/config/netconf.cmd` | High
11 | File | `/etc/passwd` | Medium
12 | File | `/etc/services/INET/inet_ipv4.php` | High
13 | File | `/forum/away.php` | High
14 | File | `/get_getnetworkconf.cgi` | High
15 | File | `/goform/saveParentControlInfo` | High
16 | File | `/home.jsp` | Medium
17 | File | `/horde/util/go.php` | High
18 | File | `/include/stat/stat.php` | High
19 | File | `/login` | Low
20 | File | `/login.cgi?logout=1` | High
21 | File | `/Login.do` | Medium
22 | File | `/mifs/c/i/reg/reg.html` | High
23 | File | `/pages.php` | Medium
24 | File | `/pages/items` | Medium
25 | File | `/proc/iomem` | Medium
26 | File | `/profile/deleteWatch.do` | High
27 | File | `/show_news.php` | High
28 | File | `/status.js` | Medium
29 | File | `/tmp` | Low
30 | File | `/uncpath/` | Medium
31 | File | `/userRpm/MediaServerFoldersCfgRpm.htm` | High
32 | File | `/usr/local/ssl/openssl.cnf` | High
33 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
34 | File | `/var/log/nginx` | High
35 | File | `/wp-admin` | Medium
36 | File | `/xampp/guestbook-en.pl` | High
37 | File | `abook_database.php` | High
38 | File | `AccountStatus.jsp` | High
39 | File | `action/usermanager.htm` | High
40 | File | `add.php` | Low
41 | File | `add_comment.php` | High
42 | File | `admin.cgi?action=config_restore` | High
43 | File | `admin.php3` | Medium
44 | File | `admin/add-news.php` | High
45 | File | `admin/ajax/op_kandidat.php` | High
46 | File | `admin/gv_mail.php` | High
47 | File | `admin/manage-articles.php` | High
48 | File | `admin/manage-departments.php` | High
49 | File | `admin/systemOutOfBand.do` | High
50 | File | `ajax.php` | Medium
51 | File | `and/or` | Low
52 | File | `Annot.cc` | Medium
53 | File | `aoutx.h` | Low
54 | File | `app/application.cpp` | High
55 | File | `apply.cgi` | Medium
56 | ... | ... | ...

There are 484 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/37829
* https://github.com/eset/malware-ioc/tree/master/invisimole
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q4

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
