# PrivateLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PrivateLoader](https://vuldb.com/?actor.privateloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.privateloader](https://vuldb.com/?actor.privateloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PrivateLoader:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [DE](https://vuldb.com/?country.de)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PrivateLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.80.133](https://vuldb.com/?ip.5.181.80.133) | navbarlatino.alarmedbook.de | - | High
2 | [5.182.36.101](https://vuldb.com/?ip.5.182.36.101) | vz.darytelecom.ru | - | High
3 | [45.15.156.229](https://vuldb.com/?ip.45.15.156.229) | - | - | High
4 | [79.174.12.174](https://vuldb.com/?ip.79.174.12.174) | king420.lazy.fvds.ru | - | High
5 | [85.208.136.10](https://vuldb.com/?ip.85.208.136.10) | - | - | High
6 | [89.38.131.151](https://vuldb.com/?ip.89.38.131.151) | no-reverse-yet.local | - | High
7 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PrivateLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PrivateLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/admin.php/singer/admin/singer/del` | High
4 | File | `/admin/?page=product/manage_product&id=2` | High
5 | File | `/Admin/add-student.php` | High
6 | File | `/admin/index.PHP` | High
7 | File | `/admin/transactions/update_status.php` | High
8 | File | `/api/user/password/sent-reset-email` | High
9 | File | `/baseOpLog.do` | High
10 | File | `/bl-plugins/backup/plugin.php` | High
11 | File | `/cgi-bin/nightled.cgi` | High
12 | File | `/cgi/get_param.cgi` | High
13 | File | `/classes/Users.php` | High
14 | File | `/common/download_agent_installer.php` | High
15 | File | `/common/info.cgi` | High
16 | File | `/common/logViewer/logViewer.jsf` | High
17 | File | `/common/run_cross_report.php` | High
18 | File | `/Config/SaveUploadedHotspotLogoFile` | High
19 | File | `/confirm` | Medium
20 | File | `/controller/Index.php` | High
21 | File | `/cwc/login` | Medium
22 | File | `/debug/pprof` | Medium
23 | File | `/etc/master.passwd` | High
24 | File | `/etc/passwd` | Medium
25 | File | `/EXCU_SHELL` | Medium
26 | File | `/foms/all-orders.php?status=Cancelled%20by%20Customer` | High
27 | File | `/goform/addressNat` | High
28 | File | `/goform/NatStaticSetting` | High
29 | File | `/goform/setMacFilterCfg` | High
30 | File | `/goform/SysToolChangePwd` | High
31 | File | `/goform/WifiBasicSet` | High
32 | File | `/HNAP1` | Low
33 | File | `/home/resume/index` | High
34 | File | `/index.php?action=seomatic/file/seo-file-link` | High
35 | File | `/iwguestbook/admin/badwords_edit.asp` | High
36 | File | `/iwguestbook/admin/messages_edit.asp` | High
37 | File | `/MagickCore/enhance.c` | High
38 | File | `/MagickCore/quantize.c` | High
39 | File | `/MagickCore/statistic.c` | High
40 | File | `/ofrs/admin/?page=reports` | High
41 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
42 | File | `/page.php` | Medium
43 | File | `/pages/permit/permit.php` | High
44 | File | `/pet_shop/classes/Master.php?f=delete_category` | High
45 | File | `/php-sms/admin/?page=services/manage_service` | High
46 | File | `/ping.html` | Medium
47 | File | `/plugin/jcapture/applet.php` | High
48 | File | `/query` | Low
49 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
50 | File | `/secure/admin/RestoreDefaults.jspa` | High
51 | File | `/services/view_service.php` | High
52 | File | `/sistema/flash/reboot` | High
53 | File | `/spip.php` | Medium
54 | ... | ... | ...

There are 468 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/107bbcf1-8d11-4f08-bcc0-56e6421de94b
* https://community.blueliv.com/#!/s/6274c2b082df417a00331684
* https://community.blueliv.com/#!/s/63280e7d82df417ed0331974
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/20220914_privateloader_IOC.csv
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
