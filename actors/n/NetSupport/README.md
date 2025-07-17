# NetSupport - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [NetSupport](https://vuldb.com/?actor.netsupport). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.netsupport](https://vuldb.com/?actor.netsupport)

## Campaigns

The following _campaigns_ are known and can be associated with NetSupport:

* ClickFix

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with NetSupport:

* [LA](https://vuldb.com/?country.la)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of NetSupport.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.156.60](https://vuldb.com/?ip.5.181.156.60) | no-rdns.mivocloud.com | - | High
2 | [5.181.159.28](https://vuldb.com/?ip.5.181.159.28) | no-rdns.mivocloud.com | - | High
3 | [5.181.159.137](https://vuldb.com/?ip.5.181.159.137) | 5-181-159-137.mivocloud.com | - | High
4 | [23.23.49.179](https://vuldb.com/?ip.23.23.49.179) | ec2-23-23-49-179.compute-1.amazonaws.com | ClickFix | Medium
5 | [50.87.146.66](https://vuldb.com/?ip.50.87.146.66) | 50-87-146-66.unifiedlayer.com | ClickFix | High
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _NetSupport_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by NetSupport. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/dl_sendmail.php` | High
2 | File | `/admin/edit_subject.php` | High
3 | File | `/admin/file_manager/export` | High
4 | File | `/admin/index2.html` | High
5 | File | `/adminPage/conf/reload` | High
6 | File | `/admin_topic.php?action=delall` | High
7 | File | `/api/baskets/{name}` | High
8 | File | `/api/cron/settings/setJob/` | High
9 | File | `/api/RecordingList/DownloadRecord?file=` | High
10 | File | `/api/v2/cli/commands` | High
11 | File | `/api2/html/` | Medium
12 | File | `/apply.cgi` | Medium
13 | File | `/backend/admin/his_admin_register_patient.php` | High
14 | File | `/bitrix/admin/ldap_server_edit.php` | High
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/cgi-bin/koha/catalogue/search.pl` | High
17 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
18 | File | `/DXR.axd` | Medium
19 | File | `/forum/away.php` | High
20 | File | `/gena.cgi` | Medium
21 | File | `/h/rest` | Low
22 | File | `/index.php` | Medium
23 | File | `/index/ajax/lang` | High
24 | File | `/log/decodmail.php` | High
25 | File | `/login.php?m=admin&c=Field&a=channel_edit` | High
26 | File | `/log_proxy` | Medium
27 | File | `/mailcleaner.php/getStats` | High
28 | File | `/members/poster.php` | High
29 | File | `/mfsNotice/page` | High
30 | File | `/netflow/jspui/editProfile.jsp` | High
31 | File | `/novel/bookSetting/list` | High
32 | File | `/novel/userFeedback/list` | High
33 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
34 | File | `/owa/auth/logon.aspx` | High
35 | File | `/php/ping.php` | High
36 | ... | ... | ...

There are 310 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://pastebin.com/iqcg0Ys7
* https://urlhaus.abuse.ch/url/3519140/
* https://urlhaus.abuse.ch/url/3519203/
* https://urlhaus.abuse.ch/url/3536229/
* https://urlhaus.abuse.ch/url/3543173/
* https://urlhaus.abuse.ch/url/3543176/
* https://www.cybereason.com/blog/net-support-rat-wordpress-clickfix
* https://www.domaintools.com/resources/blog/a-website-attacked/
* https://www.malware-traffic-analysis.net/2025/06/18/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
