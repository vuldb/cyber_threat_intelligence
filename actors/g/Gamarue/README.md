# Gamarue - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Gamarue](https://vuldb.com/?actor.gamarue). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gamarue](https://vuldb.com/?actor.gamarue)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gamarue:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gamarue.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.35.249.46](https://vuldb.com/?ip.5.35.249.46) | redirect.haribo.com | - | High
2 | [5.154.191.57](https://vuldb.com/?ip.5.154.191.57) | - | - | High
3 | [5.159.57.195](https://vuldb.com/?ip.5.159.57.195) | www-riedle.transfermarkt.de | - | High
4 | [20.186.50.83](https://vuldb.com/?ip.20.186.50.83) | - | - | High
5 | [37.187.0.40](https://vuldb.com/?ip.37.187.0.40) | ns3108067.ip-37-187-0.eu | - | High
6 | [40.70.224.146](https://vuldb.com/?ip.40.70.224.146) | - | - | High
7 | [40.81.11.194](https://vuldb.com/?ip.40.81.11.194) | - | - | High
8 | [40.91.94.203](https://vuldb.com/?ip.40.91.94.203) | - | - | High
9 | [45.8.124.25](https://vuldb.com/?ip.45.8.124.25) | free.gbnhost.com | - | High
10 | [45.122.138.6](https://vuldb.com/?ip.45.122.138.6) | - | - | High
11 | [45.128.204.36](https://vuldb.com/?ip.45.128.204.36) | - | - | High
12 | [45.128.207.237](https://vuldb.com/?ip.45.128.207.237) | - | - | High
13 | [46.45.169.106](https://vuldb.com/?ip.46.45.169.106) | 46-45-169-106.turkrdns.com | - | High
14 | [46.249.38.155](https://vuldb.com/?ip.46.249.38.155) | - | - | High
15 | [46.254.21.69](https://vuldb.com/?ip.46.254.21.69) | h13.ihc.ru | - | High
16 | [50.116.23.211](https://vuldb.com/?ip.50.116.23.211) | www.eqnic.net | - | High
17 | [51.195.53.221](https://vuldb.com/?ip.51.195.53.221) | ip221.ip-51-195-53.eu | - | High
18 | [52.137.90.34](https://vuldb.com/?ip.52.137.90.34) | - | - | High
19 | [52.230.217.195](https://vuldb.com/?ip.52.230.217.195) | - | - | High
20 | ... | ... | ... | ...

There are 76 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Gamarue_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gamarue. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/?p=products` | Medium
3 | File | `/admin/config.php?display=disa&view=form` | High
4 | File | `/admin/settings.php` | High
5 | File | `/admin/settings/sites/new` | High
6 | File | `/ajax/networking/get_netcfg.php` | High
7 | File | `/api/admin/store/product/save` | High
8 | File | `/app/admin/nat/item-add-submit.php` | High
9 | File | `/app/sys1.php` | High
10 | File | `/bin/sh` | Low
11 | File | `/cgi-bin/adm.cgi` | High
12 | File | `/cgi-bin/wlogin.cgi` | High
13 | File | `/config/netconf.cmd` | High
14 | File | `/customer_support/ajax.php?action=save_ticket` | High
15 | File | `/folder/list` | Medium
16 | File | `/group/comment` | High
17 | File | `/index.php?r=admin/database/index/updatesurveylocalesettings_generalsettings` | High
18 | File | `/index/ajax/lang` | High
19 | File | `/ipms/imageConvert/image` | High
20 | File | `/librarian/bookdetails.php` | High
21 | File | `/log/decodmail.php` | High
22 | File | `/lookin/info` | Medium
23 | File | `/manage_inv.php` | High
24 | File | `/plugins/servlet/jira-blockers/` | High
25 | File | `/ptipupgrade.cgi` | High
26 | File | `/public/login.htm` | High
27 | File | `/register.do` | Medium
28 | File | `/request.php` | Medium
29 | File | `/sessions/sess_<sessionid>` | High
30 | File | `/sysmanage/edit_manageadmin.php` | High
31 | File | `/themes/<php_file_name>` | High
32 | File | `/tmp/speedtest_urls.xml` | High
33 | File | `/uncpath/` | Medium
34 | File | `/upload` | Low
35 | File | `/var/log/nginx` | High
36 | ... | ... | ...

There are 305 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0907-0914.html
* https://blog.talosintelligence.com/2019/06/threat-roundup-0621-0628.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0628-0705.html
* https://blog.talosintelligence.com/2019/12/threat-roundup-1206-1213.html
* https://blog.talosintelligence.com/2020/10/threat-roundup-1023-1030.html
* https://blog.talosintelligence.com/2020/12/threat-roundup-1211-1218.html
* https://blog.talosintelligence.com/2021/01/threat-roundup-0115-0122.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0212-0219.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0827-0903.html
* https://blog.talosintelligence.com/2022/01/threat-roundup-0121-0128.html
* https://blog.talosintelligence.com/2022/06/threat-roundup-0617-0624.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
