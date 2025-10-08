# Unknown RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Unknown RAT](https://vuldb.com/?actor.unknown_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.unknown_rat](https://vuldb.com/?actor.unknown_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Unknown RAT:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Unknown RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.112.192.119](https://vuldb.com/?ip.3.112.192.119) | ec2-3-112-192-119.ap-northeast-1.compute.amazonaws.com | - | Medium
2 | [37.221.64.34](https://vuldb.com/?ip.37.221.64.34) | new43 | - | High
3 | [37.221.64.37](https://vuldb.com/?ip.37.221.64.37) | new13 | - | High
4 | [37.221.64.39](https://vuldb.com/?ip.37.221.64.39) | new05 | - | High
5 | [37.221.64.40](https://vuldb.com/?ip.37.221.64.40) | new31 | - | High
6 | [37.221.64.42](https://vuldb.com/?ip.37.221.64.42) | new47 | - | High
7 | [37.221.64.43](https://vuldb.com/?ip.37.221.64.43) | new48 | - | High
8 | [37.221.64.44](https://vuldb.com/?ip.37.221.64.44) | new29 | - | High
9 | [37.221.64.47](https://vuldb.com/?ip.37.221.64.47) | new46 | - | High
10 | [37.221.64.54](https://vuldb.com/?ip.37.221.64.54) | new09 | - | High
11 | [37.221.64.56](https://vuldb.com/?ip.37.221.64.56) | new08 | - | High
12 | [37.221.64.57](https://vuldb.com/?ip.37.221.64.57) | new27 | - | High
13 | [37.221.64.58](https://vuldb.com/?ip.37.221.64.58) | new26 | - | High
14 | [37.221.64.60](https://vuldb.com/?ip.37.221.64.60) | new11 | - | High
15 | [37.221.64.76](https://vuldb.com/?ip.37.221.64.76) | new24 | - | High
16 | [37.221.64.81](https://vuldb.com/?ip.37.221.64.81) | new39 | - | High
17 | [37.221.64.91](https://vuldb.com/?ip.37.221.64.91) | new42 | - | High
18 | [37.221.64.92](https://vuldb.com/?ip.37.221.64.92) | new02 | - | High
19 | [37.221.64.96](https://vuldb.com/?ip.37.221.64.96) | new23 | - | High
20 | [37.221.64.98](https://vuldb.com/?ip.37.221.64.98) | new44 | - | High
21 | [37.221.64.99](https://vuldb.com/?ip.37.221.64.99) | new33 | - | High
22 | [37.221.64.105](https://vuldb.com/?ip.37.221.64.105) | new07 | - | High
23 | [37.221.64.108](https://vuldb.com/?ip.37.221.64.108) | new49 | - | High
24 | [37.221.64.111](https://vuldb.com/?ip.37.221.64.111) | new14 | - | High
25 | [37.221.64.113](https://vuldb.com/?ip.37.221.64.113) | new22 | - | High
26 | ... | ... | ... | ...

There are 100 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Unknown RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059 | CWE-94 | Argument Injection | High
2 | T1505 | CWE-89 | SQL Injection | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Unknown RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `email.php` | Medium
2 | File | `tiki-register.php` | High
3 | Argument | `id` | Low

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/697acf12-2d6c-403e-b918-c9f25b544a09
* https://app.any.run/tasks/b7efe4d1-72b1-4eb8-8735-c246ea98638f
* https://app.any.run/tasks/dfc5f29f-b299-483e-84de-377ba8a718d7
* https://bazaar.abuse.ch/sample/0e5c2dc881698eddca82990a30bb2f734065b2eb9ea329b03fbf454e43a254e8/
* https://bazaar.abuse.ch/sample/2e7de86fcb5a87a88da4c49d3d388d84194c95a791b2b1587daa5955056451e5/
* https://bazaar.abuse.ch/sample/5f77465a62a1535e103ff32f3a922959661ba5e8b0b385384d507dc4be8f299a/
* https://bazaar.abuse.ch/sample/7b609924bfb9edfbc69cd7394ce44d944c75ed62ad72465b2710bd4dc59aabc1/
* https://bazaar.abuse.ch/sample/8b13ae2e374c71ac7e76cdee5faa5cbdca0238e086aa2aa5b98ee18475e81d8e/
* https://bazaar.abuse.ch/sample/47eac657dd8ba8d47851dc1e5270ce314e104ba32b1c01056902e72a9d78c126/
* https://bazaar.abuse.ch/sample/57f0888ec2f3eb3643c91761e5ca62fd9cad22ea3f029826c935e07ff3aa8344/
* https://bazaar.abuse.ch/sample/1861ce0df386218501fea79fd5481d0102e3bc918313d7288bee0941c07876e5/
* https://bazaar.abuse.ch/sample/642283bf3728a6bb968919f65840e48af0b585849e33399a46805875af2d6aca/
* https://bazaar.abuse.ch/sample/a080930b13f1b1b4340d53ecd748df7543adda9a474120f3c7fd82b9eadf1fc5/
* https://bazaar.abuse.ch/sample/bd2cc2f1f25b5f520a87068475247dd5611ab9f199ed3264983d720e016acf66/
* https://bazaar.abuse.ch/sample/bdfe8ca7a41ccc60e49b5a7164d06263dd0db8e2053128f37281480f5d0a6e30/
* https://bazaar.abuse.ch/sample/c3cff10bded89ce1c903d76dbccc2e012d5d200be9c56805bc2a830607f4b775/
* https://bazaar.abuse.ch/sample/d3d2011ad308f8d994cb76e55ba54550f7d6ab8ac6f9fe68ea2a6bac9ae1cf30/
* https://bazaar.abuse.ch/sample/e9eec0c02ac6d8b13332cc14ce7a035572f9d45080e817bd7e30e5e6f46bdc6d/
* https://bazaar.abuse.ch/sample/e60f5ea6362b16c2ed0a7872e1265baf419602f386ff05945acbb6b5d55be6d3/
* https://bazaar.abuse.ch/sample/f5dbafa3a5363368b0f9c88484f5641cb39665475441588a22eb38955ed87700/
* https://blogs.jpcert.or.jp/en/2025/04/dslogdrat.html
* https://github.com/stamparm/maltrail/commit/72b152921331a2311ef582cc418efda394212123
* https://search.censys.io/hosts/45.86.163.183
* https://search.censys.io/hosts/45.153.125.232
* https://search.censys.io/hosts/46.30.190.248
* https://search.censys.io/hosts/46.30.191.65
* https://search.censys.io/hosts/85.239.55.40
* https://search.censys.io/hosts/85.239.55.41
* https://search.censys.io/hosts/91.132.94.58
* https://search.censys.io/hosts/91.227.77.6
* https://search.censys.io/hosts/185.174.135.71
* https://search.censys.io/hosts/193.29.57.190
* https://search.censys.io/hosts/193.29.59.254
* https://threatfox.abuse.ch
* https://tria.ge/250626-tpggpahq8s
* https://tria.ge/250814-qsxfjahm2v
* https://urlscan.io/result/01960b87-bfe8-7533-a089-25203148d96a/
* https://www.shodan.io/host/45.77.110.173#4443
* https://www.shodan.io/host/49.232.224.106#8100
* https://www.shodan.io/host/85.239.55.207#80
* https://www.shodan.io/host/107.173.214.76#80
* https://www.shodan.io/host/124.156.152.46#80
* https://www.shodan.io/host/185.253.117.48#80
* https://www.shodan.io/host/193.29.59.248#80
* https://www.shodan.io/host/198.98.61.39#443
* https://x.com/JAMESWT_WT/status/1932721686828232936
* https://x.com/s1dhy/status/1900298352664678907
* https://x.com/s1dhy/status/1900681864345764169
* https://x.com/skocherhan/status/1928924517730058700
* https://x.com/skocherhan/status/1935017341735109053

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
