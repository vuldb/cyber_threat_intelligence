# Lotus Blossom - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lotus Blossom](https://vuldb.com/?actor.lotus_blossom). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lotus_blossom](https://vuldb.com/?actor.lotus_blossom)

## Campaigns

The following _campaigns_ are known and can be associated with Lotus Blossom:

* Emissary

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lotus Blossom:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lotus Blossom.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.234.63.197](https://vuldb.com/?ip.23.234.63.197) | - | - | High
2 | [27.255.64.231](https://vuldb.com/?ip.27.255.64.231) | - | - | High
3 | [45.64.113.130](https://vuldb.com/?ip.45.64.113.130) | - | - | High
4 | [46.251.237.59](https://vuldb.com/?ip.46.251.237.59) | - | - | High
5 | [50.7.11.10](https://vuldb.com/?ip.50.7.11.10) | yem1.entregadorvirtual9.com | - | High
6 | [58.64.183.92](https://vuldb.com/?ip.58.64.183.92) | - | - | High
7 | [59.6.2.16](https://vuldb.com/?ip.59.6.2.16) | - | - | High
8 | [59.188.247.32](https://vuldb.com/?ip.59.188.247.32) | - | - | High
9 | [61.58.31.102](https://vuldb.com/?ip.61.58.31.102) | - | - | High
10 | [95.154.195.152](https://vuldb.com/?ip.95.154.195.152) | hrms.blinkgator.net | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lotus Blossom_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lotus Blossom. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/pages/` | High
3 | File | `/admins` | Low
4 | File | `/ajax/getBasicInfo.php` | High
5 | File | `/analysisProject/pagingQueryData` | High
6 | File | `/api/admin/system/store/order/list` | High
7 | File | `/cgi-bin/cstecgi.cgi` | High
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/cgi-bin/wlogin.cgi` | High
10 | File | `/clientdetails/admin/regester.php` | High
11 | File | `/csms/?page=contact_us` | High
12 | File | `/etc/ajenti/config.yml` | High
13 | File | `/farm/product.php` | High
14 | File | `/forum/away.php` | High
15 | File | `/goform/telnet` | High
16 | File | `/modules/profile/index.php` | High
17 | File | `/ptippage.cgi` | High
18 | File | `/rom-0` | Low
19 | File | `/tmp/out` | Medium
20 | File | `/tmp/phpglibccheck` | High
21 | File | `/uncpath/` | Medium
22 | File | `/upload` | Low
23 | File | `/v1/operador/` | High
24 | File | `/var/tmp/sess_*` | High
25 | File | `/vmi/manager/engine/management/commands/apns_worker.py` | High
26 | File | `action.php` | Medium
27 | File | `actionphp/download.File.php` | High
28 | File | `add_comment.php` | High
29 | File | `admin/admin.php` | High
30 | File | `admin/content.php` | High
31 | File | `admin/index.php?id=users/action=edit/user_id=1` | High
32 | File | `admin/memberviewdetails.php` | High
33 | File | `admin/src/containers/InputModalStepperProvider/index.js` | High
34 | File | `admin_gallery.php3` | High
35 | File | `affich.php` | Medium
36 | File | `agent/Core/Controller/SendRequest.cpp` | High
37 | File | `ajax/telemetry.php` | High
38 | File | `akeyActivationLogin.do` | High
39 | File | `album_portal.php` | High
40 | File | `apache-auth.conf` | High
41 | File | `askapache-firefox-adsense.php` | High
42 | File | `attachment.cgi` | High
43 | File | `blueprints/sections/edit/1` | High
44 | ... | ... | ...

There are 384 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/the-spring-dragon-apt/70726/
* https://unit42.paloaltonetworks.com/attack-on-french-diplomat-linked-to-operation-lotus-blossom/
* https://unit42.paloaltonetworks.com/emissary-trojan-changelog-did-operation-lotus-blossom-cause-it-to-evolve/
* https://www.paloaltonetworks.com/resources/research/unit42-operation-lotus-blossom.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
