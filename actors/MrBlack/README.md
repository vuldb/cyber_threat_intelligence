# MrBlack - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MrBlack](https://vuldb.com/?actor.mrblack). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mrblack](https://vuldb.com/?actor.mrblack)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MrBlack:

* [US](https://vuldb.com/?country.us)
* [PL](https://vuldb.com/?country.pl)
* [ES](https://vuldb.com/?country.es)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MrBlack.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [101.33.238.116](https://vuldb.com/?ip.101.33.238.116) | - | - | High
2 | [119.91.92.254](https://vuldb.com/?ip.119.91.92.254) | - | - | High
3 | [154.38.107.204](https://vuldb.com/?ip.154.38.107.204) | - | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MrBlack_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MrBlack. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `'phpshell.php` | High
2 | File | `.mscreenrc` | Medium
3 | File | `/admin/` | Low
4 | File | `/admin/edit.php` | High
5 | File | `/admin/moduleinterface.php` | High
6 | File | `/admin/powerline` | High
7 | File | `/admin/subnets/ripe-query.php` | High
8 | File | `/adminlogin.asp` | High
9 | File | `/cgi-bin/system_mgr.cgi` | High
10 | File | `/classes/Master.php?f=delete_message` | High
11 | File | `/cms/process.php` | High
12 | File | `/common/info.cgi` | High
13 | File | `/controller/pay.class.php` | High
14 | File | `/insurance/clientStatus.php` | High
15 | File | `/jart/prj3/solve_direct/main.jart` | High
16 | File | `/linkedcontent/listfiles.php` | High
17 | File | `/module/admin_notifiers/rules.php` | High
18 | File | `/sendKey` | Medium
19 | File | `/service-list` | High
20 | File | `/supervisor/procesa_carga.php` | High
21 | File | `/timeline2.php` | High
22 | File | `/usr/bin/tddp` | High
23 | File | `/usr/etc/rpc.passwd` | High
24 | File | `/wp-content/plugins/forum-server/feed.php` | High
25 | File | `add_edit_event.php` | High
26 | File | `admin.php` | Medium
27 | File | `admin/adminfunctions.php` | High
28 | File | `admin/event_edit.php` | High
29 | File | `admin/Index/write.html` | High
30 | File | `admin/manage-comments.php` | High
31 | File | `admin/moduleinterface.php` | High
32 | File | `admin/moduleinterface.php.` | High
33 | File | `admin/partials/custom/egoi-for-wp-form_egoi.php` | High
34 | File | `admincp/attachment.php` | High
35 | File | `admin_class.php` | High
36 | File | `all-offers/` | Medium
37 | File | `api/openUrlInDefaultBrowser` | High
38 | File | `apply.cgi` | Medium
39 | File | `arch/arm64/kernel/entry.S` | High
40 | File | `as2guiie.cab` | Medium
41 | File | `backupsettings.conf` | High
42 | File | `badword.asp` | Medium
43 | File | `base_local_rules.php` | High
44 | File | `bfd/mach-o.c` | Medium
45 | File | `booker_details.php` | High
46 | File | `bpcd.exe` | Medium
47 | File | `BrudaNews/BrudaGB` | High
48 | File | `calAdd.php` | Medium
49 | File | `calendar.php` | Medium
50 | File | `cardreader.cpp` | High
51 | File | `cgi-bin/passrec.asp` | High
52 | File | `cgi/cron.php` | Medium
53 | ... | ... | ...

There are 461 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/54f921af0167fd1acb4dbb581632fc4d6fae9666e10117ead5b6e8e8517c5131/
* https://bazaar.abuse.ch/sample/54fed4d05e21995a1359e2482d29cc429a7ce470a6f1a438e763852a27c8de37/
* https://bazaar.abuse.ch/sample/60ff13e27dad5e6eadb04011aa653a15e1a07200b6630fdd0d0d72a9ba797d68/
* https://bazaar.abuse.ch/sample/92b5c61f622ef910bbc8b54aefb5d85d89fbf56b85e0f1bba3783bfd4374cf05/
* https://bazaar.abuse.ch/sample/d69f386b9b1ad223837ddee2f65a14e5beb9c154669dc2e21b31ac79f7838113
* https://bazaar.abuse.ch/sample/ef25e5a8a35482a1dde914a60a9239c2ba3dd2dbd287af7791430c394d46160a/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
