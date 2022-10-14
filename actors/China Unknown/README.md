# China Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [China Unknown](https://vuldb.com/?actor.china_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.china_unknown](https://vuldb.com/?actor.china_unknown)

## Campaigns

The following _campaigns_ are known and can be associated with China Unknown:

* Dragon Castling
* ProxyNotShell
* RedXOR
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with China Unknown:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [JP](https://vuldb.com/?country.jp)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of China Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | ProxyNotShell | High
2 | [23.106.123.196](https://vuldb.com/?ip.23.106.123.196) | - | Dragon Castling | High
3 | [23.106.124.136](https://vuldb.com/?ip.23.106.124.136) | - | Dragon Castling | High
4 | [34.92.228.216](https://vuldb.com/?ip.34.92.228.216) | 216.228.92.34.bc.googleusercontent.com | RedXOR | Medium
5 | [43.129.177.152](https://vuldb.com/?ip.43.129.177.152) | - | - | High
6 | [43.134.194.237](https://vuldb.com/?ip.43.134.194.237) | - | - | High
7 | [43.154.74.7](https://vuldb.com/?ip.43.154.74.7) | - | - | High
8 | [43.154.85.5](https://vuldb.com/?ip.43.154.85.5) | - | - | High
9 | [43.154.88.192](https://vuldb.com/?ip.43.154.88.192) | - | - | High
10 | [45.61.137.211](https://vuldb.com/?ip.45.61.137.211) | - | Russia | High
11 | [45.76.218.247](https://vuldb.com/?ip.45.76.218.247) | 45.76.218.247.vultrusercontent.com | - | High
12 | [45.77.178.47](https://vuldb.com/?ip.45.77.178.47) | 45.77.178.47.vultrusercontent.com | - | High
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _China Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-35 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by China Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Admin/add-student.php` | High
2 | File | `/admin/article/list_approve` | High
3 | File | `/admin/client_assign.php` | High
4 | File | `/admin/client_edit.php` | High
5 | File | `/admin/contact/list` | High
6 | File | `/admin/feature_edit.php` | High
7 | File | `/admin/foldernotice/list` | High
8 | File | `/admin/image/list` | High
9 | File | `/admin/imagealbum/list` | High
10 | File | `/admin/select.php` | High
11 | File | `/admin/sendmailto.php?tomail=&groupid=` | High
12 | File | `/admin/site/list` | High
13 | File | `/admin/subnets/ripe-query.php` | High
14 | File | `/admin/update_currency.php` | High
15 | File | `/admin/video/list` | High
16 | File | `/admin_book.php` | High
17 | File | `/api/upload-resource` | High
18 | File | `/authUserAction!edit.action` | High
19 | File | `/bin/httpd` | Medium
20 | File | `/buspassms/download-pass.php` | High
21 | File | `/carbon/ndatasource/validateconnection/ajaxprocessor.jsp` | High
22 | File | `/card/in-card.php` | High
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/confirm` | Medium
25 | ... | ... | ...

There are 206 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/431/scarab-mustang-panda-space-pirates-apt-iocs/
* https://blog.malwarebytes.com/malwarebytes-news/2022/05/unknown-apt-group-has-targeted-russia-repeatedly-since-ukraine-invasion/
* https://blog.talosintelligence.com/2019/08/china-chopper-still-active-9-years-later.html
* https://community.blueliv.com/#!/s/6025590982df413ea934bd9a
* https://github.com/avast/ioc/tree/master/OperationDragonCastling
* https://research.checkpoint.com/2022/chinese-actor-takes-aim-armed-with-nim-language-and-bizarro-aes/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.03.10(1)/RedXOR.pdf
* https://www.gteltsc.vn/blog/warning-new-attack-campaign-utilized-a-new-0day-rce-vulnerability-on-microsoft-exchange-server-12715.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
