# Mekotio - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Mekotio](https://vuldb.com/?actor.mekotio). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.mekotio](https://vuldb.com/?actor.mekotio)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mekotio:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mekotio.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [4.240.84.251](https://vuldb.com/?ip.4.240.84.251) | - | - | High
2 | [5.181.156.86](https://vuldb.com/?ip.5.181.156.86) | 5-181-156-86.mivocloud.com | - | High
3 | [13.66.15.167](https://vuldb.com/?ip.13.66.15.167) | - | - | High
4 | [15.228.13.156](https://vuldb.com/?ip.15.228.13.156) | ec2-15-228-13-156.sa-east-1.compute.amazonaws.com | - | Medium
5 | [15.228.16.45](https://vuldb.com/?ip.15.228.16.45) | ec2-15-228-16-45.sa-east-1.compute.amazonaws.com | - | Medium
6 | [15.228.46.182](https://vuldb.com/?ip.15.228.46.182) | ec2-15-228-46-182.sa-east-1.compute.amazonaws.com | - | Medium
7 | [15.229.1.40](https://vuldb.com/?ip.15.229.1.40) | ec2-15-229-1-40.sa-east-1.compute.amazonaws.com | - | Medium
8 | [15.229.26.142](https://vuldb.com/?ip.15.229.26.142) | ec2-15-229-26-142.sa-east-1.compute.amazonaws.com | - | Medium
9 | [18.118.78.11](https://vuldb.com/?ip.18.118.78.11) | ec2-18-118-78-11.us-east-2.compute.amazonaws.com | - | Medium
10 | [18.223.102.186](https://vuldb.com/?ip.18.223.102.186) | ec2-18-223-102-186.us-east-2.compute.amazonaws.com | - | Medium
11 | [18.231.161.239](https://vuldb.com/?ip.18.231.161.239) | ec2-18-231-161-239.sa-east-1.compute.amazonaws.com | - | Medium
12 | [20.5.65.48](https://vuldb.com/?ip.20.5.65.48) | - | - | High
13 | [20.25.181.202](https://vuldb.com/?ip.20.25.181.202) | - | - | High
14 | [20.38.37.160](https://vuldb.com/?ip.20.38.37.160) | - | - | High
15 | [20.121.119.89](https://vuldb.com/?ip.20.121.119.89) | - | - | High
16 | [20.206.121.1](https://vuldb.com/?ip.20.206.121.1) | - | - | High
17 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mekotio_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mekotio. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `..\WWWRoot\CustomPages\aspshell.asp` | High
2 | File | `/account/details.php` | High
3 | File | `/admin/` | Low
4 | File | `/admin/ajax.php?action=save_window` | High
5 | File | `/admin/general/change-lang` | High
6 | File | `/admin/group` | Medium
7 | File | `/admin/launch_time.php` | High
8 | File | `/admin/moduleinterface.php` | High
9 | File | `/admin/payment.php` | High
10 | File | `/api/v1/snapshots` | High
11 | File | `/artist-display.php` | High
12 | File | `/BRS_netgear_success.html` | High
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/controllers/MgrDiagnosticTools.php` | High
15 | File | `/czarnews/cn_users.php` | High
16 | File | `/designer/add/layout` | High
17 | File | `/dev/zero` | Medium
18 | File | `/etc/waipass` | Medium
19 | File | `/index.php` | Medium
20 | File | `/manager/index.php` | High
21 | File | `/message/ajax/send/` | High
22 | File | `/mgmt/tm/util/bash` | High
23 | File | `/myAccount` | Medium
24 | File | `/ndmComponents.js` | High
25 | File | `/real-estate-script/search_property.php` | High
26 | File | `/recordings/index.php` | High
27 | File | `/roomtype-details.php` | High
28 | File | `/search.php` | Medium
29 | File | `/searchJob.php` | High
30 | File | `/secure/QueryComponent!Default.jspa` | High
31 | File | `/see_more_details.php` | High
32 | File | `/StartingPage/link_req_2.php` | High
33 | File | `/storage.html` | High
34 | File | `/tools/required/files/importers/imageeditor` | High
35 | File | `/uncpath/` | Medium
36 | File | `/uploads/tags.php` | High
37 | File | `/userman/inbox.php` | High
38 | File | `/UserSelfServiceSettings.jsp` | High
39 | ... | ... | ...

There are 337 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/cb5538b08c11ad4a004b1f5668ce77a38fe574c2fb8ccaf0ebf06a548ad4144d/
* https://gblogs.cisco.com/jp/2024/02/talos-google-cloud-run-abuse/
* https://research.checkpoint.com/2021/mekotio-banker-returns-with-improved-stealth-and-ancient-encryption/
* https://threatfox.abuse.ch
* https://twitter.com/Dkavalanche/status/1623456458464702468
* https://twitter.com/Dkavalanche/status/1633256558158118913
* https://twitter.com/Dkavalanche/status/1723002138853310922
* https://twitter.com/jorgemieres/status/1717940842982223980
* https://twitter.com/Merlax_/status/1598764864738033680
* https://twitter.com/Merlax_/status/1612827626967638017
* https://twitter.com/Merlax_/status/1617705925779017729
* https://twitter.com/Merlax_/status/1626290586016792576
* https://twitter.com/Merlax_/status/1642935684292804609
* https://twitter.com/Merlax_/status/1651696436013068290
* https://twitter.com/Merlax_/status/1654904040906530817
* https://twitter.com/Merlax_/status/1657030594121826306
* https://twitter.com/Merlax_/status/1659652152543813652
* https://twitter.com/Merlax_/status/1676546469808209925
* https://twitter.com/Merlax_/status/1687558327457181696
* https://twitter.com/Merlax_/status/1732944960180158722
* https://twitter.com/SeguInfo/status/1699869450038554725
* https://twitter.com/SeguInfo/status/1703851435077587315
* https://twitter.com/SeguInfo/status/1705308358696210620
* https://twitter.com/V3n0mStrike/status/1688312316134117377
* https://www.virustotal.com/gui/file/c25dc30e13c33341aaa22ecbaa17fd28334d06089658a5521663564ee5f96b35/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
