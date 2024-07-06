# Luna Moth - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Luna Moth](https://vuldb.com/?actor.luna_moth). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.luna_moth](https://vuldb.com/?actor.luna_moth)

## Campaigns

The following _campaigns_ are known and can be associated with Luna Moth:

* Callback Phishing
* Subscription Scam

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Luna Moth:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Luna Moth.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.238.40.28](https://vuldb.com/?ip.23.238.40.28) | hwsrv-979679.hostwindsdns.com | Subscription Scam | High
2 | [23.238.40.29](https://vuldb.com/?ip.23.238.40.29) | hwsrv-979677.hostwindsdns.com | Subscription Scam | High
3 | [23.238.40.30](https://vuldb.com/?ip.23.238.40.30) | hwsrv-979678.hostwindsdns.com | Subscription Scam | High
4 | [23.238.40.31](https://vuldb.com/?ip.23.238.40.31) | hwsrv-979680.hostwindsdns.com | Subscription Scam | High
5 | [23.238.40.32](https://vuldb.com/?ip.23.238.40.32) | hwsrv-979681.hostwindsdns.com | Subscription Scam | High
6 | [23.254.227.79](https://vuldb.com/?ip.23.254.227.79) | client-23-254-227-79.hostwindsdns.com | Subscription Scam | High
7 | [23.254.228.211](https://vuldb.com/?ip.23.254.228.211) | hwsrv-981934.hostwindsdns.com | Subscription Scam | High
8 | [23.254.229.90](https://vuldb.com/?ip.23.254.229.90) | client-23-254-229-90.hostwindsdns.com | Subscription Scam | High
9 | [104.168.135.71](https://vuldb.com/?ip.104.168.135.71) | hwsrv-975503.hostwindsdns.com | Subscription Scam | High
10 | [104.168.164.244](https://vuldb.com/?ip.104.168.164.244) | client-104-168-164-244.hostwindsdns.com | Subscription Scam | High
11 | [104.168.171.104](https://vuldb.com/?ip.104.168.171.104) | hwsrv-979189.hostwindsdns.com | Subscription Scam | High
12 | [104.168.171.231](https://vuldb.com/?ip.104.168.171.231) | hwsrv-979190.hostwindsdns.com | Subscription Scam | High
13 | [104.168.201.87](https://vuldb.com/?ip.104.168.201.87) | client-104-168-201-87.hostwindsdns.com | Subscription Scam | High
14 | [104.168.201.100](https://vuldb.com/?ip.104.168.201.100) | client-104-168-201-100.hostwindsdns.com | Subscription Scam | High
15 | [104.168.201.129](https://vuldb.com/?ip.104.168.201.129) | client-104-168-201-129.hostwindsdns.com | Subscription Scam | High
16 | [104.168.204.231](https://vuldb.com/?ip.104.168.204.231) | client-104-168-204-231.hostwindsdns.com | Subscription Scam | High
17 | ... | ... | ... | ...

There are 64 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Luna Moth_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Luna Moth. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/ajax-files/followBoard.php` | High
2 | File | `/books` | Low
3 | File | `/forum/away.php` | High
4 | File | `/includes/lib/detail.php` | High
5 | File | `/modules/projects/vw_files.php` | High
6 | File | `/oauth/idp/.well-known/openid-configuration` | High
7 | File | `/out.php` | Medium
8 | File | `/resources//../` | High
9 | File | `/see_more_details.php` | High
10 | File | `/server-status` | High
11 | File | `add-services.php` | High
12 | File | `admin.php` | Medium
13 | File | `admin/index.php` | High
14 | File | `admin/models/Galleries.php` | High
15 | File | `affich.php` | Medium
16 | File | `affiliate-preview.php` | High
17 | File | `akocomments.php` | High
18 | File | `album_portal.php` | High
19 | File | `application/modules/admin/views/ecommerce/products.php` | High
20 | File | `apps/app_article/controller/rating.php` | High
21 | File | `app\Http\Controllers\Backend\ProfileController.php` | High
22 | File | `auktion.cgi` | Medium
23 | File | `basket.php` | Medium
24 | File | `big.php` | Low
25 | File | `category_list.php` | High
26 | File | `closeup.php` | Medium
27 | ... | ... | ...

There are 225 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.sygnia.co/luna-moth-false-subscription-scams
* https://unit42.paloaltonetworks.com/luna-moth-callback-phishing/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
