# PrivateLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PrivateLoader](https://vuldb.com/?actor.privateloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.privateloader](https://vuldb.com/?actor.privateloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PrivateLoader:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PrivateLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.181.80.133](https://vuldb.com/?ip.5.181.80.133) | navbarlatino.alarmedbook.de | - | High
2 | [5.182.36.101](https://vuldb.com/?ip.5.182.36.101) | vz.darytelecom.ru | - | High
3 | [79.174.12.174](https://vuldb.com/?ip.79.174.12.174) | king420.lazy.fvds.ru | - | High
4 | [89.38.131.151](https://vuldb.com/?ip.89.38.131.151) | no-reverse-yet.local | - | High
5 | [89.38.131.155](https://vuldb.com/?ip.89.38.131.155) | no-reverse-yet.local | - | High
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

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

There are 25 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PrivateLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin.php/singer/admin/singer/del` | High
3 | File | `/admin/?page=product/manage_product&id=2` | High
4 | File | `/Admin/add-student.php` | High
5 | File | `/admin/index.PHP` | High
6 | File | `/admin/transactions/update_status.php` | High
7 | File | `/api/user/password/sent-reset-email` | High
8 | File | `/baseOpLog.do` | High
9 | File | `/cgi/get_param.cgi` | High
10 | File | `/classes/Users.php` | High
11 | File | `/common/download_agent_installer.php` | High
12 | File | `/common/info.cgi` | High
13 | File | `/common/logViewer/logViewer.jsf` | High
14 | File | `/common/run_cross_report.php` | High
15 | File | `/Config/SaveUploadedHotspotLogoFile` | High
16 | File | `/confirm` | Medium
17 | File | `/controller/Index.php` | High
18 | File | `/cwc/login` | Medium
19 | File | `/debug/pprof` | Medium
20 | File | `/download` | Medium
21 | File | `/EXCU_SHELL` | Medium
22 | File | `/foms/all-orders.php?status=Cancelled%20by%20Customer` | High
23 | File | `/goform/addressNat` | High
24 | File | `/goform/NatStaticSetting` | High
25 | File | `/goform/setMacFilterCfg` | High
26 | File | `/goform/SysToolChangePwd` | High
27 | File | `/goform/WifiBasicSet` | High
28 | File | `/GponForm/device_Form?script/` | High
29 | File | `/HNAP1` | Low
30 | File | `/home/resume/index` | High
31 | File | `/includes/lib/detail.php` | High
32 | File | `/includes/lib/get.php` | High
33 | File | `/includes/lib/tree.php` | High
34 | File | `/includes/rrdtool.inc.php` | High
35 | File | `/index.php?action=seomatic/file/seo-file-link` | High
36 | File | `/iwguestbook/admin/badwords_edit.asp` | High
37 | File | `/iwguestbook/admin/messages_edit.asp` | High
38 | File | `/MagickCore/enhance.c` | High
39 | File | `/MagickCore/quantize.c` | High
40 | ... | ... | ...

There are 344 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
