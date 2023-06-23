# Nymaim - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nymaim](https://vuldb.com/?actor.nymaim). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nymaim](https://vuldb.com/?actor.nymaim)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nymaim:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 16 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nymaim. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `.travis.yml` | Medium
3 | File | `/+CSCOE+/logon.html` | High
4 | File | `/?p=products` | Medium
5 | File | `/admin.php/accessory/filesdel.html` | High
6 | File | `/admin/?page=user/manage` | High
7 | File | `/admin/add-new.php` | High
8 | File | `/admin/doctors.php` | High
9 | File | `/admin/submit-articles` | High
10 | File | `/alphaware/summary.php` | High
11 | File | `/api/` | Low
12 | File | `/api/admin/store/product/list` | High
13 | File | `/api/stl/actions/search` | High
14 | File | `/api/v2/cli/commands` | High
15 | File | `/attachments` | Medium
16 | File | `/backup.pl` | Medium
17 | File | `/bin/ate` | Medium
18 | File | `/bin/boa` | Medium
19 | File | `/boat/login.php` | High
20 | File | `/bsms_ci/index.php/book` | High
21 | File | `/cgi-bin` | Medium
22 | File | `/cgi-bin/wlogin.cgi` | High
23 | File | `/classes/Master.php?f=delete_reservation` | High
24 | File | `/context/%2e/WEB-INF/web.xml` | High
25 | File | `/debug/pprof` | Medium
26 | File | `/DXR.axd` | Medium
27 | File | `/env` | Low
28 | File | `/etc/hosts` | Medium
29 | File | `/forum/away.php` | High
30 | File | `/goform/formWPS` | High
31 | File | `/goform/wizard_end` | High
32 | File | `/inc/campaign/count_of_send.php` | High
33 | File | `/medicines/profile.php` | High
34 | File | `/mgmt/tm/util/bash` | High
35 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
36 | File | `/php-sms/admin/?page=user/manage_user` | High
37 | File | `/proxy` | Low
38 | File | `/rdms/admin/?page=user/manage_user` | High
39 | File | `/reservation/add_message.php` | High
40 | File | `/secure/QueryComponent!Default.jspa` | High
41 | File | `/shell` | Low
42 | File | `/spip.php` | Medium
43 | File | `/templates/importinline.vm` | High
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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
