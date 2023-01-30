# Mikey - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mikey](https://vuldb.com/?actor.mikey). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mikey](https://vuldb.com/?actor.mikey)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mikey:

* [IN](https://vuldb.com/?country.in)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mikey.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.208.22.49](https://vuldb.com/?ip.8.208.22.49) | - | - | High
2 | [20.45.1.107](https://vuldb.com/?ip.20.45.1.107) | - | - | High
3 | [24.35.232.189](https://vuldb.com/?ip.24.35.232.189) | 24-35-232-189.fidnet.com | - | High
4 | [24.42.115.69](https://vuldb.com/?ip.24.42.115.69) | - | - | High
5 | [40.67.189.14](https://vuldb.com/?ip.40.67.189.14) | - | - | High
6 | [40.90.247.210](https://vuldb.com/?ip.40.90.247.210) | - | - | High
7 | [40.91.124.111](https://vuldb.com/?ip.40.91.124.111) | - | - | High
8 | [43.231.4.7](https://vuldb.com/?ip.43.231.4.7) | - | - | High
9 | [43.241.73.221](https://vuldb.com/?ip.43.241.73.221) | kt-spk-a917.pointdnshere.com | - | High
10 | [46.4.52.109](https://vuldb.com/?ip.46.4.52.109) | witntech.dev | - | High
11 | [46.29.160.26](https://vuldb.com/?ip.46.29.160.26) | savewindow.ru | - | High
12 | [46.128.161.129](https://vuldb.com/?ip.46.128.161.129) | 46.128.161.129.dyn.pyur.net | - | High
13 | [46.249.59.122](https://vuldb.com/?ip.46.249.59.122) | mailer.abbbccc.com | - | High
14 | [49.124.15.147](https://vuldb.com/?ip.49.124.15.147) | - | - | High
15 | [52.1.22.171](https://vuldb.com/?ip.52.1.22.171) | ec2-52-1-22-171.compute-1.amazonaws.com | - | Medium
16 | [52.36.131.229](https://vuldb.com/?ip.52.36.131.229) | ec2-52-36-131-229.us-west-2.compute.amazonaws.com | - | Medium
17 | [54.183.102.22](https://vuldb.com/?ip.54.183.102.22) | ec2-54-183-102-22.us-west-1.compute.amazonaws.com | - | Medium
18 | [54.248.125.247](https://vuldb.com/?ip.54.248.125.247) | ec2-54-248-125-247.ap-northeast-1.compute.amazonaws.com | - | Medium
19 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mikey_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mikey. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/../conf/config.properties` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/?ajax-request=jnews` | High
4 | File | `/Admin/add-student.php` | High
5 | File | `/admin/blog/blogcategory/add/?_to_field=id&_popup=1` | High
6 | File | `/appliance/users?action=edit` | High
7 | File | `/cgi-bin/wlogin.cgi` | High
8 | File | `/componetns/user/class.user.php` | High
9 | File | `/cwc/login` | Medium
10 | File | `/etc/tomcat8/Catalina/attack` | High
11 | File | `/forum/away.php` | High
12 | File | `/front/document.form.php` | High
13 | File | `/goform/wizard_end` | High
14 | File | `/ims/login.php` | High
15 | File | `/include/chart_generator.php` | High
16 | File | `/Items/*/RemoteImages/Download` | High
17 | File | `/mhds/clinic/view_details.php` | High
18 | File | `/out.php` | Medium
19 | File | `/rest/api/latest/projectvalidate/key` | High
20 | File | `/rest/collectors/1.0/template/custom` | High
21 | File | `/search.php` | Medium
22 | File | `/ServletAPI/accounts/login` | High
23 | File | `/uncpath/` | Medium
24 | File | `/user/login/oauth` | High
25 | File | `/usr/bin/pkexec` | High
26 | File | `/usr/www/ja/mnt_cmd.cgi` | High
27 | File | `/var/log/messages` | High
28 | File | `/vendor/htmlawed/htmlawed/htmLawedTest.php` | High
29 | File | `/websocket/exec` | High
30 | ... | ... | ...

There are 250 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/10/threat-roundup-1012-1019.html
* https://blog.talosintelligence.com/2018/11/threat-roundup-1019-1102.html
* https://blog.talosintelligence.com/2019/02/threat-roundup-0125-0201.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0419-to-0426.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0214-0221.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0522-0529.html
* https://blog.talosintelligence.com/2020/06/threat-roundup-0529-0605.html
* https://blog.talosintelligence.com/threat-roundup-1028-1104/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
