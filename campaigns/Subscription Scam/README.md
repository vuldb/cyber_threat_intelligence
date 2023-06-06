# Subscription Scam - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Subscription Scam_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Subscription Scam:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)

## Actors

These _actors_ are associated with Subscription Scam or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Subscription Scam.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.238.40.28](https://vuldb.com/?ip.23.238.40.28) | hwsrv-979679.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
2 | [23.238.40.29](https://vuldb.com/?ip.23.238.40.29) | hwsrv-979677.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
3 | [23.238.40.30](https://vuldb.com/?ip.23.238.40.30) | hwsrv-979678.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
4 | [23.238.40.31](https://vuldb.com/?ip.23.238.40.31) | hwsrv-979680.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
5 | [23.238.40.32](https://vuldb.com/?ip.23.238.40.32) | hwsrv-979681.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
6 | [23.254.227.79](https://vuldb.com/?ip.23.254.227.79) | client-23-254-227-79.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
7 | [23.254.228.211](https://vuldb.com/?ip.23.254.228.211) | hwsrv-981934.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
8 | [23.254.229.90](https://vuldb.com/?ip.23.254.229.90) | client-23-254-229-90.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
9 | [104.168.135.71](https://vuldb.com/?ip.104.168.135.71) | hwsrv-975503.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
10 | [104.168.164.244](https://vuldb.com/?ip.104.168.164.244) | client-104-168-164-244.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
11 | [104.168.171.104](https://vuldb.com/?ip.104.168.171.104) | hwsrv-979189.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
12 | [104.168.171.231](https://vuldb.com/?ip.104.168.171.231) | hwsrv-979190.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
13 | [104.168.201.87](https://vuldb.com/?ip.104.168.201.87) | client-104-168-201-87.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
14 | [104.168.201.100](https://vuldb.com/?ip.104.168.201.100) | client-104-168-201-100.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
15 | [104.168.201.129](https://vuldb.com/?ip.104.168.201.129) | client-104-168-201-129.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
16 | [104.168.204.231](https://vuldb.com/?ip.104.168.204.231) | client-104-168-204-231.hostwindsdns.com | [Luna Moth](https://vuldb.com/?actor.luna_moth) | High
17 | ... | ... | ... | ...

There are 63 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Subscription Scam. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Subscription Scam. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/ajax-files/followBoard.php` | High
2 | File | `/forum/away.php` | High
3 | File | `/includes/lib/detail.php` | High
4 | File | `/modules/projects/vw_files.php` | High
5 | File | `/see_more_details.php` | High
6 | File | `/server-status` | High
7 | File | `add-services.php` | High
8 | File | `admin.php` | Medium
9 | File | `admin/index.php` | High
10 | File | `admin/models/Galleries.php` | High
11 | File | `affich.php` | Medium
12 | File | `affiliate-preview.php` | High
13 | File | `akocomments.php` | High
14 | File | `album_portal.php` | High
15 | File | `application/modules/admin/views/ecommerce/products.php` | High
16 | File | `apps/app_article/controller/rating.php` | High
17 | File | `app\Http\Controllers\Backend\ProfileController.php` | High
18 | File | `auktion.cgi` | Medium
19 | File | `basket.php` | Medium
20 | File | `big.php` | Low
21 | File | `category_list.php` | High
22 | File | `closeup.php` | Medium
23 | File | `cng.sys` | Low
24 | ... | ... | ...

There are 201 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.sygnia.co/luna-moth-false-subscription-scams

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
