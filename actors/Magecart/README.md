# Magecart - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Magecart](https://vuldb.com/?actor.magecart). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.magecart](https://vuldb.com/?actor.magecart)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Magecart:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
7 | [5.135.247.141](https://vuldb.com/?ip.5.135.247.141) | ip141.ip-5-135-247.eu | - | High
8 | [5.135.247.142](https://vuldb.com/?ip.5.135.247.142) | ip142.ip-5-135-247.eu | - | High
9 | [5.188.44.32](https://vuldb.com/?ip.5.188.44.32) | - | - | High
10 | [8.209.70.103](https://vuldb.com/?ip.8.209.70.103) | - | - | High
11 | [8.211.0.55](https://vuldb.com/?ip.8.211.0.55) | - | - | High
12 | [8.211.5.139](https://vuldb.com/?ip.8.211.5.139) | - | - | High
13 | [24.3.29.37](https://vuldb.com/?ip.24.3.29.37) | c-24-3-29-37.hsd1.pa.comcast.net | - | High
14 | [28.23.5.5](https://vuldb.com/?ip.28.23.5.5) | - | - | High
15 | [35.14.69.4](https://vuldb.com/?ip.35.14.69.4) | - | - | High
16 | [35.246.189.253](https://vuldb.com/?ip.35.246.189.253) | 253.189.246.35.bc.googleusercontent.com | - | Medium
17 | [36.85.5.5](https://vuldb.com/?ip.36.85.5.5) | - | - | High
18 | [36.86.5.5](https://vuldb.com/?ip.36.86.5.5) | - | - | High
19 | [37.59.47.208](https://vuldb.com/?ip.37.59.47.208) | ns3000975.ip-37-59-47.eu | - | High
20 | [44.35.8.8](https://vuldb.com/?ip.44.35.8.8) | - | - | High
21 | [45.197.141.250](https://vuldb.com/?ip.45.197.141.250) | - | - | High
22 | ... | ... | ... | ...

There are 86 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Magecart_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Magecart. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/accessory/filesdel.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/admin/login.php` | High
8 | File | `/admin/submit-articles` | High
9 | File | `/ad_js.php` | Medium
10 | File | `/alphaware/summary.php` | High
11 | File | `/api/` | Low
12 | File | `/api/admin/store/product/list` | High
13 | File | `/api/baskets/{name}` | High
14 | File | `/api/stl/actions/search` | High
15 | File | `/api/v2/cli/commands` | High
16 | File | `/attachments` | Medium
17 | File | `/bin/ate` | Medium
18 | File | `/boat/login.php` | High
19 | File | `/booking/show_bookings/` | High
20 | File | `/bsms_ci/index.php/book` | High
21 | File | `/cgi-bin` | Medium
22 | File | `/cgi-bin/luci/api/wireless` | High
23 | File | `/cgi-bin/wlogin.cgi` | High
24 | File | `/Content/Template/root/reverse-shell.aspx` | High
25 | File | `/context/%2e/WEB-INF/web.xml` | High
26 | File | `/dashboard/add-blog.php` | High
27 | File | `/debian/patches/load_ppp_generic_if_needed` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/env` | Low
30 | File | `/etc/hosts` | Medium
31 | File | `/forum/away.php` | High
32 | File | `/goform/setmac` | High
33 | File | `/goform/wizard_end` | High
34 | File | `/group1/uploa` | High
35 | File | `/inc/parser/xhtml.php` | High
36 | File | `/manage-apartment.php` | High
37 | File | `/medicines/profile.php` | High
38 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
39 | File | `/pages/apply_vacancy.php` | High
40 | File | `/php-sms/admin/?page=user/manage_user` | High
41 | File | `/proxy` | Low
42 | File | `/requests.php` | High
43 | File | `/reservation/add_message.php` | High
44 | File | `/resources//../` | High
45 | File | `/Session` | Medium
46 | ... | ... | ...

There are 394 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
