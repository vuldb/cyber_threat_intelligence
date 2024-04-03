# Magecart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magecart](https://vuldb.com/?actor.magecart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magecart](https://vuldb.com/?actor.magecart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magecart:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Magecart.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.1.6](https://vuldb.com/?ip.1.3.1.6) | - | - | High
2 | [1.3.2.8](https://vuldb.com/?ip.1.3.2.8) | - | - | High
3 | [1.45.76.1](https://vuldb.com/?ip.1.45.76.1) | - | - | High
4 | [2.1.5.3](https://vuldb.com/?ip.2.1.5.3) | - | - | High
5 | [3.1.5.3](https://vuldb.com/?ip.3.1.5.3) | ec2-3-1-5-3.ap-southeast-1.compute.amazonaws.com | - | Medium
6 | [5.4.8.1](https://vuldb.com/?ip.5.4.8.1) | dynamic-005-004-008-001.5.4.pool.telefonica.de | - | High
7 | [5.45.83.223](https://vuldb.com/?ip.5.45.83.223) | - | - | High
8 | [5.135.247.141](https://vuldb.com/?ip.5.135.247.141) | ip141.ip-5-135-247.eu | - | High
9 | [5.135.247.142](https://vuldb.com/?ip.5.135.247.142) | ip142.ip-5-135-247.eu | - | High
10 | [5.188.44.32](https://vuldb.com/?ip.5.188.44.32) | - | - | High
11 | [5.252.177.247](https://vuldb.com/?ip.5.252.177.247) | 5-252-177-247.mivocloud.com | - | High
12 | [8.209.70.103](https://vuldb.com/?ip.8.209.70.103) | - | - | High
13 | [8.211.0.55](https://vuldb.com/?ip.8.211.0.55) | - | - | High
14 | [8.211.5.139](https://vuldb.com/?ip.8.211.5.139) | - | - | High
15 | [24.3.29.37](https://vuldb.com/?ip.24.3.29.37) | c-24-3-29-37.hsd1.pa.comcast.net | - | High
16 | [28.23.5.5](https://vuldb.com/?ip.28.23.5.5) | - | - | High
17 | [35.14.69.4](https://vuldb.com/?ip.35.14.69.4) | - | - | High
18 | [35.246.189.253](https://vuldb.com/?ip.35.246.189.253) | 253.189.246.35.bc.googleusercontent.com | - | Medium
19 | [36.85.5.5](https://vuldb.com/?ip.36.85.5.5) | - | - | High
20 | [36.86.5.5](https://vuldb.com/?ip.36.86.5.5) | - | - | High
21 | [37.1.213.121](https://vuldb.com/?ip.37.1.213.121) | - | - | High
22 | [37.59.47.208](https://vuldb.com/?ip.37.59.47.208) | ns3000975.ip-37-59-47.eu | - | High
23 | [37.252.1.225](https://vuldb.com/?ip.37.252.1.225) | introstock.com | - | High
24 | ... | ... | ... | ...

There are 92 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Magecart_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magecart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/?p=products` | Medium
3 | File | `/admin/controller/JobLogController.java` | High
4 | File | `/admin/login.php` | High
5 | File | `/api/baskets/{name}` | High
6 | File | `/api/stl/actions/search` | High
7 | File | `/api/sys/login` | High
8 | File | `/api/sys/set_passwd` | High
9 | File | `/api/trackedEntityInstances` | High
10 | File | `/api/v2/cli/commands` | High
11 | File | `/aux` | Low
12 | File | `/bin/ate` | Medium
13 | File | `/booking/show_bookings/` | High
14 | File | `/cgi-bin` | Medium
15 | File | `/cgi-bin/wlogin.cgi` | High
16 | File | `/changePassword` | High
17 | File | `/Content/Template/root/reverse-shell.aspx` | High
18 | File | `/dashboard/add-blog.php` | High
19 | File | `/data/remove` | Medium
20 | File | `/debug/pprof` | Medium
21 | File | `/ecshop/admin/template.php` | High
22 | File | `/env` | Low
23 | File | `/etc/passwd` | Medium
24 | File | `/forum/away.php` | High
25 | File | `/goform/net\_Web\_get_value` | High
26 | File | `/group1/uploa` | High
27 | File | `/inc/parser/xhtml.php` | High
28 | File | `/index.php` | Medium
29 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
30 | File | `/php-sms/admin/?page=user/manage_user` | High
31 | File | `/resources//../` | High
32 | File | `/testConnection` | High
33 | File | `/tmp/ppd.trace` | High
34 | File | `/uncpath/` | Medium
35 | File | `/user/inc/workidajax.php` | High
36 | File | `/user/updatePwd` | High
37 | File | `/userLogin.asp` | High
38 | ... | ... | ...

There are 326 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2020/08/analysis-of-recent-magecart-campaign.html
* https://blog.bushidotoken.net/2020/12/analysis-of-meyhod-javascript-web.html
* https://blog.bushidotoken.net/2021/04/mo-money-mo-magecart.html
* https://blog.malwarebytes.com/threat-intelligence/2021/09/the-many-tentacles-of-magecart-group-8/
* https://blog.malwarebytes.com/threat-intelligence/2022/06/client-side-magecart-attacks-still-around-but-more-covert/
* https://blog.usejournal.com/sesame-street-volusion-customers-are-comprised-how-the-cookie-monster-is-stealing-cc-numbers-21eb51ec613b
* https://community.blueliv.com/#!/s/614c62f382df414169331f64
* https://github.com/blackorbird/APT_REPORT/tree/master/Magecart
* https://sansec.io/research/malware-persistence-via-telegram-and-github
* https://search.censys.io/hosts/5.45.83.223
* https://search.censys.io/hosts/5.252.177.247
* https://search.censys.io/hosts/37.1.213.121
* https://search.censys.io/hosts/37.252.1.225
* https://search.censys.io/hosts/45.153.48.176
* https://search.censys.io/hosts/66.11.117.40
* https://search.censys.io/hosts/91.92.250.214

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
