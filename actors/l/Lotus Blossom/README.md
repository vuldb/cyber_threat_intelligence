# Lotus Blossom - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lotus Blossom](https://vuldb.com/?actor.lotus_blossom). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lotus_blossom](https://vuldb.com/?actor.lotus_blossom)

## Campaigns

The following _campaigns_ are known and can be associated with Lotus Blossom:

* Emissary
* Sagerunex

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lotus Blossom:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lotus Blossom.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.234.63.197](https://vuldb.com/?ip.23.234.63.197) | - | - | High
2 | [27.255.64.231](https://vuldb.com/?ip.27.255.64.231) | - | - | High
3 | [43.252.161.22](https://vuldb.com/?ip.43.252.161.22) | - | Sagerunex | High
4 | [43.254.217.138](https://vuldb.com/?ip.43.254.217.138) | - | Sagerunex | High
5 | [43.254.218.69](https://vuldb.com/?ip.43.254.218.69) | - | Sagerunex | High
6 | [43.255.104.100](https://vuldb.com/?ip.43.255.104.100) | ecs-43-255-104-100.compute.hwclouds-dns.com | Sagerunex | High
7 | [45.32.127.121](https://vuldb.com/?ip.45.32.127.121) | 45.32.127.121.vultrusercontent.com | Sagerunex | Medium
8 | [45.32.127.212](https://vuldb.com/?ip.45.32.127.212) | 45.32.127.212.vultrusercontent.com | Sagerunex | Medium
9 | [45.64.113.130](https://vuldb.com/?ip.45.64.113.130) | - | - | High
10 | [46.251.237.59](https://vuldb.com/?ip.46.251.237.59) | - | - | High
11 | [50.7.11.10](https://vuldb.com/?ip.50.7.11.10) | yem1.entregadorvirtual9.com | - | High
12 | [58.64.183.92](https://vuldb.com/?ip.58.64.183.92) | - | - | High
13 | [58.64.193.166](https://vuldb.com/?ip.58.64.193.166) | - | Sagerunex | High
14 | [58.64.193.225](https://vuldb.com/?ip.58.64.193.225) | - | Sagerunex | High
15 | [59.6.2.16](https://vuldb.com/?ip.59.6.2.16) | - | - | High
16 | ... | ... | ... | ...

There are 62 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lotus Blossom_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lotus Blossom. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin.php?page=cat_list` | High
4 | File | `/admin/pages/` | High
5 | File | `/admins` | Low
6 | File | `/ajax/getBasicInfo.php` | High
7 | File | `/analysisProject/pagingQueryData` | High
8 | File | `/api/admin/system/store/order/list` | High
9 | File | `/app/admin/controller/api/Plugs.php` | High
10 | File | `/assets/ctx` | Medium
11 | File | `/cgi-bin/cstecgi.cgi` | High
12 | File | `/cgi-bin/wapopen` | High
13 | File | `/cgi-bin/wlogin.cgi` | High
14 | File | `/clientdetails/admin/regester.php` | High
15 | File | `/csms/?page=contact_us` | High
16 | File | `/etc/ajenti/config.yml` | High
17 | File | `/farm/product.php` | High
18 | File | `/forum/away.php` | High
19 | File | `/goform/telnet` | High
20 | File | `/index/ajax/lang` | High
21 | File | `/jmreport/loadTableData` | High
22 | File | `/lms/admin.php` | High
23 | File | `/manage_block.php` | High
24 | File | `/modules/profile/index.php` | High
25 | File | `/onlDragDatasetHead/getTotalData` | High
26 | File | `/onvif/device_service` | High
27 | File | `/ptippage.cgi` | High
28 | File | `/question` | Medium
29 | File | `/rom-0` | Low
30 | File | `/swdHGFizaW.php/general/attachment/edit/ids/4?dialog=1` | High
31 | File | `/tmp/out` | Medium
32 | File | `/tmp/phpglibccheck` | High
33 | File | `/uncpath/` | Medium
34 | File | `/update-image1.php` | High
35 | File | `/upload` | Low
36 | File | `/v1/operador/` | High
37 | File | `/var/tmp/sess_*` | High
38 | File | `/vmi/manager/engine/management/commands/apns_worker.py` | High
39 | File | `/[admins_url].php/general/attachment/edit/ids/4?dialog=1` | High
40 | File | `action.php` | Medium
41 | File | `actionphp/download.File.php` | High
42 | ... | ... | ...

There are 363 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/lotus-blossom-espionage-group/
* https://securelist.com/the-spring-dragon-apt/70726/
* https://unit42.paloaltonetworks.com/attack-on-french-diplomat-linked-to-operation-lotus-blossom/
* https://unit42.paloaltonetworks.com/emissary-trojan-changelog-did-operation-lotus-blossom-cause-it-to-evolve/
* https://www.paloaltonetworks.com/resources/research/unit42-operation-lotus-blossom.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
