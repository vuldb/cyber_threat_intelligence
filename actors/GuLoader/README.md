# GuLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GuLoader](https://vuldb.com/?actor.guloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.guloader](https://vuldb.com/?actor.guloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GuLoader:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GuLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.75.164](https://vuldb.com/?ip.5.2.75.164) | - | - | High
2 | [5.8.8.100](https://vuldb.com/?ip.5.8.8.100) | - | - | High
3 | [23.254.227.202](https://vuldb.com/?ip.23.254.227.202) | client-23-254-227-202.hostwindsdns.com | - | High
4 | [23.254.227.205](https://vuldb.com/?ip.23.254.227.205) | client-23-254-227-205.hostwindsdns.com | - | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GuLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GuLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/admin/ajax.php` | High
3 | File | `/admin/ajax.php?action=save_window` | High
4 | File | `/admin/dl_sendmail.php` | High
5 | File | `/admin/index2.html` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/v2/cli/commands` | High
8 | File | `/cgi/get_param.cgi` | High
9 | File | `/common/download_agent_installer.php` | High
10 | File | `/common/run_cross_report.php` | High
11 | File | `/connectors/index.php` | High
12 | File | `/dashboard/add-portfolio.php` | High
13 | File | `/DXR.axd` | Medium
14 | File | `/EXCU_SHELL` | Medium
15 | File | `/forum/away.php` | High
16 | File | `/ghost/preview` | High
17 | File | `/goform/addressNat` | High
18 | File | `/goform/NatStaticSetting` | High
19 | File | `/jerry-core/ecma/base/ecma-helpers-conversion.c` | High
20 | File | `/login` | Low
21 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
22 | File | `/novel/bookSetting/list` | High
23 | File | `/novel/userFeedback/list` | High
24 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
25 | File | `/opt/vyatta/share/vyatta-cfg/templates/system/static-host-mapping/host-name/node.def` | High
26 | File | `/owa/auth/logon.aspx` | High
27 | File | `/php-sms/admin/?page=services/manage_service` | High
28 | File | `/sdm-ws-rest/preconfiguration` | High
29 | File | `/settings` | Medium
30 | File | `/spip.php` | Medium
31 | File | `/uapi/doc` | Medium
32 | File | `/uncpath/` | Medium
33 | File | `/updownload/t.report` | High
34 | File | `/vendor/htmlawed/htmlawed/htmLawedTest.php` | High
35 | File | `/woocommerce-stock-manager/trunk/admin/views/import-export.php` | High
36 | ... | ... | ...

There are 305 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://any.run/cybersecurity-blog/deobfuscating-guloader/
* https://asec.ahnlab.com/en/36042/
* https://asec.ahnlab.com/en/36294/
* https://asec.ahnlab.com/en/36785/
* https://asec.ahnlab.com/en/38942/
* https://github.com/sophoslabs/IoCs/blob/master/Troj_GuLoader.csv
* https://isc.sans.edu/diary/GuLoader+or+DBatLoaderModiLoaderstyle+infection+for+Remcos+RAT/29990
* https://research.checkpoint.com/2023/unveiling-the-shadows-the-dark-alliance-between-guloader-and-remcos/
* https://www.elastic.co/security-labs/getting-gooey-with-guloader-downloader

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
