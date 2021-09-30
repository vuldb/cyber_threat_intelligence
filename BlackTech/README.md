# BlackTech - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [BlackTech](https://vuldb.com/?actor.blacktech). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.blacktech](https://vuldb.com/?actor.blacktech)

## Campaigns

The following campaigns are known and can be associated with BlackTech:

* Taiwan Government Agencies
* TSCookie
* WaterBear

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackTech:

* CN
* MS
* US

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of BlackTech.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 10.0.0.211 | - | High
2 | 43.240.12.81 | mail.terascape.net | High
3 | 45.76.102.145 | 45.76.102.145.vultr.com | Medium
4 | 45.124.25.31 | hkhdc.laws.ms | High
5 | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by BlackTech. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1600 | Cryptographic Issues | High

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackTech. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/wp-json/oembed/1.0/embed?url` | High
2 | File | `base/ErrorHandler.php` | High
3 | File | `goto.php` | Medium
4 | File | `isc/get_sid_js.aspx` | High
5 | File | `item_show.php` | High
6 | Argument | `author_name` | Medium
7 | Argument | `code_no` | Low
8 | Argument | `dbg_buf` | Low
9 | Argument | `url` | Low

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://blogs.jpcert.or.jp/en/2018/03/malware-tscooki-7aa0.html
* https://www.ithome.com.tw/news/139504
* https://www.trendmicro.com/en_us/research/17/f/following-trail-blacktech-cyber-espionage-campaigns.html
* https://www.trendmicro.com/en_us/research/19/l/waterbear-is-back-uses-api-hooking-to-evade-security-product-detection.html

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
