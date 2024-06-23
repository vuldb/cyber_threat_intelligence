# MrBlack - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MrBlack](https://vuldb.com/?actor.mrblack). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mrblack](https://vuldb.com/?actor.mrblack)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MrBlack:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MrBlack.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [101.33.238.116](https://vuldb.com/?ip.101.33.238.116) | - | - | High
2 | [119.91.92.254](https://vuldb.com/?ip.119.91.92.254) | - | - | High
3 | [154.38.107.204](https://vuldb.com/?ip.154.38.107.204) | - | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MrBlack_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MrBlack. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `'phpshell.php` | High
2 | File | `.backup/` | Medium
3 | File | `.mscreenrc` | Medium
4 | File | `/admin/edit.php` | High
5 | File | `/admin/powerline` | High
6 | File | `/admin/subnets/ripe-query.php` | High
7 | File | `/aya/module/admin/ust_tab_e.inc.php` | High
8 | File | `/cgi-bin/portal` | High
9 | File | `/cgi-bin/system_mgr.cgi` | High
10 | File | `/classes/Master.php?f=delete_message` | High
11 | File | `/controller/pay.class.php` | High
12 | File | `/forgetpassword.php` | High
13 | File | `/goform/Diagnosis` | High
14 | File | `/HNAP1` | Low
15 | File | `/index.php` | Medium
16 | File | `/insurance/clientStatus.php` | High
17 | File | `/jart/prj3/solve_direct/main.jart` | High
18 | File | `/linkedcontent/listfiles.php` | High
19 | File | `/module/admin_notifiers/rules.php` | High
20 | File | `/rapi/read_url` | High
21 | File | `/service-list` | High
22 | File | `/supervisor/procesa_carga.php` | High
23 | File | `/test/cookie/` | High
24 | File | `/timeline2.php` | High
25 | File | `/tmp/foo2zjs` | Medium
26 | File | `/tmp/kamailio_fifo` | High
27 | File | `/usr/bin/tddp` | High
28 | File | `add.php` | Low
29 | File | `addtocart.asp` | High
30 | File | `add_edit_event.php` | High
31 | File | `admin.php` | Medium
32 | File | `admin/graph_trend.php` | High
33 | File | `admin/manage-comments.php` | High
34 | File | `admin/moduleinterface.php` | High
35 | File | `adminpanel/modules/pro/inc/ajax.php` | High
36 | File | `admin\db\DoSql.php` | High
37 | File | `admin_class.php` | High
38 | File | `aide.php3` | Medium
39 | File | `ajax/ph_save.php` | High
40 | File | `all-offers/` | Medium
41 | File | `ansible.cfg` | Medium
42 | File | `Ap4EsDescriptor.cpp` | High
43 | File | `app/plug/controller/giftcontroller.php` | High
44 | File | `arch/arm/kernel/process.c` | High
45 | ... | ... | ...

There are 392 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/54f921af0167fd1acb4dbb581632fc4d6fae9666e10117ead5b6e8e8517c5131/
* https://bazaar.abuse.ch/sample/54fed4d05e21995a1359e2482d29cc429a7ce470a6f1a438e763852a27c8de37/
* https://bazaar.abuse.ch/sample/60ff13e27dad5e6eadb04011aa653a15e1a07200b6630fdd0d0d72a9ba797d68/
* https://bazaar.abuse.ch/sample/92b5c61f622ef910bbc8b54aefb5d85d89fbf56b85e0f1bba3783bfd4374cf05/
* https://bazaar.abuse.ch/sample/d8d522f2f72de16a235c17b6d32bad930d2a21a8c2664a76880c9b4b53ec1b58/
* https://bazaar.abuse.ch/sample/d69f386b9b1ad223837ddee2f65a14e5beb9c154669dc2e21b31ac79f7838113
* https://bazaar.abuse.ch/sample/ef25e5a8a35482a1dde914a60a9239c2ba3dd2dbd287af7791430c394d46160a/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
