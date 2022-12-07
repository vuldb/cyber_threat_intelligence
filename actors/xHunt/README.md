# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [ES](https://vuldb.com/?country.es)
* ...

There are 34 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xHunt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | BumbleBee | High
2 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | BumbleBee | High
3 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | BumbleBee | High
4 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | BumbleBee | High
5 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | BumbleBee | High
6 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | BumbleBee | High
7 | [85.203.46.99](https://vuldb.com/?ip.85.203.46.99) | - | BumbleBee | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xHunt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-87 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.../gogo/` | Medium
2 | File | `.procmailrc` | Medium
3 | File | `/admin/` | Low
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/communitymanagement.php` | High
6 | File | `/admin/extended` | High
7 | File | `/admin/featured.php` | High
8 | File | `/admin/generalsettings.php` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/newsletter1.php` | High
11 | File | `/admin/payment.php` | High
12 | File | `/admin/renewaldue.php` | High
13 | File | `/admin/students/manage.php` | High
14 | File | `/admin/students/view_student.php` | High
15 | File | `/admin/usermanagement.php` | High
16 | File | `/api/addusers` | High
17 | File | `/api/user/upsert/<uuid>` | High
18 | File | `/bits/stl_vector.h` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/common/info.cgi` | High
21 | File | `/dashboard/add-portfolio.php` | High
22 | File | `/dashboard/updatelogo.php` | High
23 | File | `/designer/add/layout` | High
24 | File | `/filemanager/upload/drop` | High
25 | File | `/foms/place-order.php` | High
26 | File | `/getImage` | Medium
27 | File | `/goform/wizard_end` | High
28 | File | `/h/calendar` | Medium
29 | File | `/h/compose` | Medium
30 | File | `/h/search?action=voicemail&action=listen` | High
31 | File | `/htmldoc/htmldoc/html.cxx` | High
32 | File | `/index.php` | Medium
33 | File | `/librarian/bookdetails.php` | High
34 | File | `/login.php` | Medium
35 | File | `/loginVaLidation.php` | High
36 | File | `/manage-apartment.php` | High
37 | File | `/manager/index.php` | High
38 | File | `/mcategory.php` | High
39 | File | `/mkshop/Men/profile.php` | High
40 | File | `/new` | Low
41 | File | `/Noxen-master/users.php` | High
42 | File | `/opac/Actions.php?a=login` | High
43 | File | `/out.php` | Medium
44 | File | `/pages/animals.php` | High
45 | ... | ... | ...

There are 389 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
