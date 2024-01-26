# Nymaim - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nymaim](https://vuldb.com/?actor.nymaim). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nymaim](https://vuldb.com/?actor.nymaim)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nymaim:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nymaim.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.253.131.120](https://vuldb.com/?ip.8.253.131.120) | - | - | High
2 | [8.253.132.120](https://vuldb.com/?ip.8.253.132.120) | - | - | High
3 | [34.227.185.153](https://vuldb.com/?ip.34.227.185.153) | ec2-34-227-185-153.compute-1.amazonaws.com | - | Medium
4 | [37.152.176.90](https://vuldb.com/?ip.37.152.176.90) | - | - | High
5 | [45.139.105.171](https://vuldb.com/?ip.45.139.105.171) | - | - | High
6 | [46.4.52.109](https://vuldb.com/?ip.46.4.52.109) | witntech.dev | - | High
7 | [46.47.98.128](https://vuldb.com/?ip.46.47.98.128) | 46-47-98-128.stz.ddns.bulsat.com | - | High
8 | [46.238.18.157](https://vuldb.com/?ip.46.238.18.157) | ip-46-238-18-157.home.megalan.bg | - | High
9 | [47.91.242.212](https://vuldb.com/?ip.47.91.242.212) | - | - | High
10 | [50.22.169.26](https://vuldb.com/?ip.50.22.169.26) | 1a.a9.1632.ip4.static.sl-reverse.com | - | High
11 | [51.218.181.145](https://vuldb.com/?ip.51.218.181.145) | - | - | High
12 | [52.85.144.32](https://vuldb.com/?ip.52.85.144.32) | server-52-85-144-32.iad89.r.cloudfront.net | - | High
13 | [52.114.128.43](https://vuldb.com/?ip.52.114.128.43) | - | - | High
14 | ... | ... | ... | ...

There are 52 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nymaim_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-50 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nymaim. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/?p=products` | Medium
3 | File | `/admin/controller/JobLogController.java` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/api/stl/actions/search` | High
6 | File | `/api/sys/login` | High
7 | File | `/api/sys/set_passwd` | High
8 | File | `/api/trackedEntityInstances` | High
9 | File | `/api/v2/cli/commands` | High
10 | File | `/aux` | Low
11 | File | `/bin/ate` | Medium
12 | File | `/boaform/device_reset.cgi` | High
13 | File | `/booking/show_bookings/` | High
14 | File | `/cgi-bin` | Medium
15 | File | `/changePassword` | High
16 | File | `/Content/Template/root/reverse-shell.aspx` | High
17 | File | `/dashboard/add-blog.php` | High
18 | File | `/data/remove` | Medium
19 | File | `/debug/pprof` | Medium
20 | File | `/ecshop/admin/template.php` | High
21 | File | `/env` | Low
22 | File | `/forms/doLogin` | High
23 | File | `/forum/away.php` | High
24 | File | `/group1/uploa` | High
25 | File | `/index.php` | Medium
26 | File | `/load.php` | Medium
27 | File | `/mobileredir/openApp.jsp` | High
28 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
29 | File | `/php-sms/admin/?page=user/manage_user` | High
30 | File | `/resources//../` | High
31 | File | `/secure/QueryComponent!Default.jspa` | High
32 | File | `/servlet/webacc` | High
33 | File | `/servlet/webacc?user.html` | High
34 | File | `/templates/importinline.vm` | High
35 | File | `/testConnection` | High
36 | File | `/tmp/ppd.trace` | High
37 | File | `/trx_addons/v2/get/sc_layout` | High
38 | File | `/uncpath/` | Medium
39 | File | `/uscgi-bin/users.cgi` | High
40 | File | `/user/updatePwd` | High
41 | File | `/userLogin.asp` | High
42 | File | `/vm/admin/doctors.php` | High
43 | File | `/web/entry/en/address/adrsSetUserWizard.cgi` | High
44 | ... | ... | ...

There are 377 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/06/threat-roundup-0607-0614.html
* https://blog.talosintelligence.com/2019/06/threat-roundup-0614-0621.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0712-0719.html
* https://blog.talosintelligence.com/2020/02/threat-roundup-0214-0221.html
* https://blog.talosintelligence.com/2020/03/threat-roundup-0228-0306.html
* https://blog.talosintelligence.com/2020/12/threat-roundup-1127-1204.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0528-0604.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0625-0702.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0730-0806.html
* https://tria.ge/221114-t9vvtagh7t
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
