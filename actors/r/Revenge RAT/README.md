# Revenge RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Revenge RAT](https://vuldb.com/?actor.revenge_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revenge_rat](https://vuldb.com/?actor.revenge_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Revenge RAT:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Revenge RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.138.180.119](https://vuldb.com/?ip.3.138.180.119) | ec2-3-138-180-119.us-east-2.compute.amazonaws.com | - | Medium
2 | [5.39.19.8](https://vuldb.com/?ip.5.39.19.8) | - | - | High
3 | [18.228.165.84](https://vuldb.com/?ip.18.228.165.84) | ec2-18-228-165-84.sa-east-1.compute.amazonaws.com | - | Medium
4 | [18.228.173.171](https://vuldb.com/?ip.18.228.173.171) | ec2-18-228-173-171.sa-east-1.compute.amazonaws.com | - | Medium
5 | [18.228.214.231](https://vuldb.com/?ip.18.228.214.231) | ec2-18-228-214-231.sa-east-1.compute.amazonaws.com | - | Medium
6 | [18.231.150.177](https://vuldb.com/?ip.18.231.150.177) | ec2-18-231-150-177.sa-east-1.compute.amazonaws.com | - | Medium
7 | [18.231.151.211](https://vuldb.com/?ip.18.231.151.211) | ec2-18-231-151-211.sa-east-1.compute.amazonaws.com | - | Medium
8 | [23.237.25.123](https://vuldb.com/?ip.23.237.25.123) | - | - | High
9 | [37.0.11.45](https://vuldb.com/?ip.37.0.11.45) | - | - | High
10 | [38.132.101.45](https://vuldb.com/?ip.38.132.101.45) | - | - | High
11 | [40.127.163.74](https://vuldb.com/?ip.40.127.163.74) | - | - | High
12 | [42.118.133.241](https://vuldb.com/?ip.42.118.133.241) | - | - | High
13 | ... | ... | ... | ...

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Revenge RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Revenge RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `/?Key=PhoneRequestAuthorization` | High
3 | File | `/account/ResetPassword` | High
4 | File | `/admin/?/layout/add` | High
5 | File | `/admin/dialog/select_images_post.php` | High
6 | File | `/admin/index.html` | High
7 | File | `/admin/pass-bwdates-reports-details.php` | High
8 | File | `/admin/syslog` | High
9 | File | `/admin_giant/add_team_member.php` | High
10 | File | `/ajax.php` | Medium
11 | File | `/bin/login` | Medium
12 | File | `/cgi-bin/cstecgi.cgi` | High
13 | File | `/cgi-bin/ExportALLSettings.sh` | High
14 | File | `/cgi-bin/hd_config.cgi` | High
15 | File | `/classes/Master.php` | High
16 | File | `/classes/Master.php?f=delete_category` | High
17 | File | `/common/info.cgi` | High
18 | File | `/control/forgot_pass.php` | High
19 | File | `/course/filterRecords/` | High
20 | File | `/download/image` | High
21 | File | `/DXR.axd` | Medium
22 | File | `/endpoint/delete.php` | High
23 | File | `/etc/sudoers` | Medium
24 | File | `/fhconf/umconfig.txt` | High
25 | File | `/forum/away.php` | High
26 | File | `/get_getnetworkconf.cgi` | High
27 | File | `/goform/setmac` | High
28 | File | `/horde/util/go.php` | High
29 | File | `/hrm/controller/employee.php` | High
30 | File | `/include/chart_generator.php` | High
31 | File | `/includes/` | Medium
32 | File | `/index.php/admin` | High
33 | File | `/integrations.json` | High
34 | File | `/login/signOut` | High
35 | File | `/manage_block.php` | High
36 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
37 | File | `/product.php` | Medium
38 | File | `/public` | Low
39 | File | `/public/login.htm` | High
40 | File | `/report/ParkChargeRecord/GetDataList` | High
41 | File | `/spip.php` | Medium
42 | File | `/uncpath/` | Medium
43 | File | `/users/admin/user_activity.php` | High
44 | File | `/usr/local/www/pkg.php` | High
45 | File | `/var/www/rhcert` | High
46 | File | `/vendor/htmlawed/htmlawed/htmLawedTest.php` | High
47 | ... | ... | ...

There are 411 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/013fefe1917cdeedc66a5e4bee5417894491591296a91a507224ae5af9618cda/
* https://threatfox.abuse.ch
* https://tria.ge/231218-shv6tscgh3

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
