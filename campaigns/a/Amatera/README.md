# Amatera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Amatera_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Amatera:

* [CN](https://vuldb.com/country/cn)
* [RU](https://vuldb.com/country/ru)
* [US](https://vuldb.com/country/us)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Amatera or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Amatera](https://vuldb.com/actor/amatera) | High
2 | [APT28](https://vuldb.com/actor/apt28) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Amatera.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [46.149.73.57](https://vuldb.com/ip/46.149.73.57) | v738388.hosted-by-vdsina.com | [APT28](https://vuldb.com/actor/apt28) | High
2 | [46.149.73.60](https://vuldb.com/ip/46.149.73.60) | v707302.hosted-by-vdsina.com | [APT28](https://vuldb.com/actor/apt28) | High
3 | [46.149.73.219](https://vuldb.com/ip/46.149.73.219) | v741349.hosted-by-vdsina.com | [APT28](https://vuldb.com/actor/apt28) | High
4 | [46.149.77.24](https://vuldb.com/ip/46.149.77.24) | v721073.hosted-by-vdsina.com | [APT28](https://vuldb.com/actor/apt28) | High
5 | [77.91.96.205](https://vuldb.com/ip/77.91.96.205) | - | [APT28](https://vuldb.com/actor/apt28) | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Amatera. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Amatera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin-cp/file-manager/upload` | High
2 | File | `/admin/?page=system_info/contact_info` | High
3 | File | `/admin/delete_pending.php` | High
4 | File | `/admin/students.php` | High
5 | File | `/admin/theme-edit.php` | High
6 | File | `/api/admin/store/product/list` | High
7 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
8 | File | `/api2/html/` | Medium
9 | File | `/app/sys1.php` | High
10 | File | `/goform/formSetWanPPTPpath` | High
11 | ... | ... | ...

There are 79 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://bazaar.abuse.ch/sample/3a705a4987cba73f9a93c24654999febe598194ced3984b1e303ef357db5e8b1/
* https://bazaar.abuse.ch/sample/3b2b3cb791b20905a0e59bb7d1bad17d32576932b184cb61c4daa0e9b6b61d38/
* https://bazaar.abuse.ch/sample/4fd1b4d687a1ae686bfef4cb3dc09c96c4d4e12f22e7f46d2eadd24903a44888/
* https://bazaar.abuse.ch/sample/6a5cd11b8291723d19c0a402a6cc27559278bc458f827bf5f7fa4a48ee5e9275/
* https://bazaar.abuse.ch/sample/9f3c3388c6ce825295a8c36a7668a215b4f0defdd2335e9fc29810d4a5a0b1cd/
* https://bazaar.abuse.ch/sample/63cedb109aa1eb02c5c947f0988fe6f582f35ab7060ac8ba1d55fbd4aef36be1/
* https://bazaar.abuse.ch/sample/65ee7d1c4b625e7540c2e0cd7ab5e0c582197ba3e9dac14144c0d57685e0cb04/
* https://bazaar.abuse.ch/sample/69a221fe8833624d52031f5c6243745ea901b5622231de26bd52023ff667a71c/
* https://bazaar.abuse.ch/sample/903e3b20852eb6b2981336d045befc77286299d461af10658b68b20912d00c00/
* https://bazaar.abuse.ch/sample/7081ed638a67a0f5cf95948e4b63444da033787c10a5896688fd8ae93777856f/
* https://bazaar.abuse.ch/sample/415737aa1366bd168719cd65e6707a3875cc9421cf7e62d1184016b3fbbe7aff/
* https://bazaar.abuse.ch/sample/5775367d227515a556a10cb29fe0272509911b26699f3c59681cae9bc3886d03/
* https://bazaar.abuse.ch/sample/a39eca46f834e874975e46eeda652906ab3576735fe930cec7e284560c6145ca/
* https://bazaar.abuse.ch/sample/ecf674e913f5fd7429886d419978470bb2f0d7832225dc51d98aa79c5f62c3d5/
* https://bazaar.abuse.ch/sample/fc0679e7f8653a35bb725adfd54fa7a58db8b1d10ef0231c65907db622075b58/
* https://cookie.engineer/weblog/articles/malware-insights-macos-phexia-campaign.html
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3743490/
* https://urlhaus.abuse.ch/url/3743599/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
