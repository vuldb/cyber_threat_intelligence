# Ghost RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ghost RAT](https://vuldb.com/?actor.ghost_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ghost_rat](https://vuldb.com/?actor.ghost_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ghost RAT:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ghost RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.64.219](https://vuldb.com/?ip.2.58.64.219) | - | - | High
2 | [3.13.191.225](https://vuldb.com/?ip.3.13.191.225) | ec2-3-13-191-225.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.14.182.203](https://vuldb.com/?ip.3.14.182.203) | ec2-3-14-182-203.us-east-2.compute.amazonaws.com | - | Medium
4 | [3.17.7.232](https://vuldb.com/?ip.3.17.7.232) | ec2-3-17-7-232.us-east-2.compute.amazonaws.com | - | Medium
5 | [3.22.30.40](https://vuldb.com/?ip.3.22.30.40) | ec2-3-22-30-40.us-east-2.compute.amazonaws.com | - | Medium
6 | [3.134.39.220](https://vuldb.com/?ip.3.134.39.220) | ec2-3-134-39-220.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.134.125.175](https://vuldb.com/?ip.3.134.125.175) | ec2-3-134-125-175.us-east-2.compute.amazonaws.com | - | Medium
8 | [3.141.177.1](https://vuldb.com/?ip.3.141.177.1) | ec2-3-141-177-1.us-east-2.compute.amazonaws.com | - | Medium
9 | [3.142.81.166](https://vuldb.com/?ip.3.142.81.166) | ec2-3-142-81-166.us-east-2.compute.amazonaws.com | - | Medium
10 | [13.58.157.220](https://vuldb.com/?ip.13.58.157.220) | ec2-13-58-157-220.us-east-2.compute.amazonaws.com | - | Medium
11 | [18.189.106.45](https://vuldb.com/?ip.18.189.106.45) | ec2-18-189-106-45.us-east-2.compute.amazonaws.com | - | Medium
12 | [23.106.215.217](https://vuldb.com/?ip.23.106.215.217) | - | - | High
13 | [23.225.73.110](https://vuldb.com/?ip.23.225.73.110) | - | - | High
14 | [23.251.41.162](https://vuldb.com/?ip.23.251.41.162) | - | - | High
15 | [38.47.204.154](https://vuldb.com/?ip.38.47.204.154) | - | - | High
16 | [38.181.58.21](https://vuldb.com/?ip.38.181.58.21) | uhn19.pm.com | - | High
17 | [39.109.113.141](https://vuldb.com/?ip.39.109.113.141) | - | - | High
18 | [43.129.192.59](https://vuldb.com/?ip.43.129.192.59) | - | - | High
19 | ... | ... | ... | ...

There are 74 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ghost RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ghost RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/advanced-tools/nova/bin/netwatch` | High
2 | File | `/api/admin/system/store/order/list` | High
3 | File | `/batm/app/admin/standalone/deployments` | High
4 | File | `/cwp_{SESSION_HASH}/admin/loader_ajax.php` | High
5 | File | `/files/$username/Myfolder/Mysubfolder/shared.txt` | High
6 | File | `/forum/away.php` | High
7 | File | `/group1/uploa` | High
8 | File | `/see_more_details.php` | High
9 | ... | ... | ...

There are 63 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/81b90352-c3d4-4094-8e38-86dc4110411d/
* https://app.any.run/tasks/571ba149-8de2-4b77-af61-c7fc259eacc3
* https://bazaar.abuse.ch/sample/78be65f626e4a9e81c655b36c96dacc8898287d4954cbffd98788e602369f8ca/
* https://bazaar.abuse.ch/sample/133224bb212564ed0b687341512fa57fe2a55e54defededb5517ac8d8b239677/
* https://bazaar.abuse.ch/sample/ca15a055b2e1d06a8fbd3a22341aeda29bbc19688b778dc3a15c615f0367bc21/
* https://mobile.twitter.com/1ZRR4H/status/1523791593278345217
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
