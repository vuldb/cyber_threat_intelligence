# GuLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GuLoader](https://vuldb.com/?actor.guloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.guloader](https://vuldb.com/?actor.guloader)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GuLoader:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GuLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.2.75.164](https://vuldb.com/?ip.5.2.75.164) | - | - | High
2 | [5.8.8.100](https://vuldb.com/?ip.5.8.8.100) | - | - | High
3 | [5.255.110.224](https://vuldb.com/?ip.5.255.110.224) | - | - | High
4 | [23.254.227.202](https://vuldb.com/?ip.23.254.227.202) | client-23-254-227-202.hostwindsdns.com | - | High
5 | [23.254.227.205](https://vuldb.com/?ip.23.254.227.205) | client-23-254-227-205.hostwindsdns.com | - | High
6 | [23.254.227.214](https://vuldb.com/?ip.23.254.227.214) | pornytop.com | - | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GuLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
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
6 | File | `/adminPage/conf/reload` | High
7 | File | `/admin_giant/add_team_member.php` | High
8 | File | `/api/baskets/{name}` | High
9 | File | `/api/v2/cli/commands` | High
10 | File | `/cgi-bin/koha/catalogue/search.pl` | High
11 | File | `/cgi/get_param.cgi` | High
12 | File | `/common/download_agent_installer.php` | High
13 | File | `/common/info.cgi` | High
14 | File | `/common/run_cross_report.php` | High
15 | File | `/connectors/index.php` | High
16 | File | `/dashboard/add-portfolio.php` | High
17 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
18 | File | `/DXR.axd` | Medium
19 | File | `/EXCU_SHELL` | Medium
20 | File | `/forum/away.php` | High
21 | File | `/get_getnetworkconf.cgi` | High
22 | File | `/ghost/preview` | High
23 | File | `/goform/addressNat` | High
24 | File | `/goform/NatStaticSetting` | High
25 | File | `/goform/setmac` | High
26 | File | `/index/ajax/lang` | High
27 | File | `/integrations.json` | High
28 | File | `/jerry-core/ecma/base/ecma-helpers-conversion.c` | High
29 | File | `/lists/admin/` | High
30 | File | `/log/decodmail.php` | High
31 | File | `/login` | Low
32 | File | `/mfsNotice/page` | High
33 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
34 | File | `/novel/bookSetting/list` | High
35 | File | `/novel/userFeedback/list` | High
36 | File | `/nssys/common/filehandle` | High
37 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
38 | File | `/opt/vyatta/share/vyatta-cfg/templates/system/static-host-mapping/host-name/node.def` | High
39 | File | `/owa/auth/logon.aspx` | High
40 | File | `/php-sms/admin/?page=services/manage_service` | High
41 | File | `/phppath/php` | Medium
42 | File | `/register.php` | High
43 | File | `/sdm-ws-rest/preconfiguration` | High
44 | File | `/services/details.asp` | High
45 | File | `/settings` | Medium
46 | File | `/spip.php` | Medium
47 | File | `/uapi/doc` | Medium
48 | File | `/ueditor/net/controller.ashx?action=catchimage` | High
49 | File | `/uncpath/` | Medium
50 | File | `/updownload/t.report` | High
51 | ... | ... | ...

There are 446 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://any.run/cybersecurity-blog/deobfuscating-guloader/
* https://asec.ahnlab.com/en/36042/
* https://asec.ahnlab.com/en/36294/
* https://asec.ahnlab.com/en/36785/
* https://asec.ahnlab.com/en/38942/
* https://asec.ahnlab.com/en/40283/
* https://asec.ahnlab.com/en/48640/
* https://asec.ahnlab.com/en/51274/
* https://asec.ahnlab.com/en/52488/
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
