# Groundbait - Cyber Threat Intelligence

The indicators are related to [VulDB CTI analysis](https://vuldb.com/?doc.cti) of the actor known as [Groundbait](https://vuldb.com/?actor.groundbait). The activity monitoring correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, activities, intentions, emerging research, and attacks. Our unique predictive model is able to forecast activities and their characteristics.

Live data and more analysis capabilities are available at [https://vuldb.com/?actor.groundbait](https://vuldb.com/?actor.groundbait)

## Countries

These countries are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Groundbait:

* US

## IOC - Indicator of Compromise

These indicators of compromise indicate associated network ressources which are known to be part of research and attack activities of Groundbait.

ID | IP address | Hostname | Confidence
-- | ---------- | -------- | ----------
1 | 23.22.38.222 | ec2-23-22-38-222.compute-1.amazonaws.com | Medium
2 | 23.22.221.237 | ec2-23-22-221-237.compute-1.amazonaws.com | Medium
3 | 52.23.164.7 | ec2-52-23-164-7.compute-1.amazonaws.com | Medium
4 | 54.152.171.48 | ec2-54-152-171-48.compute-1.amazonaws.com | Medium
5 | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

Tactics, techniques, and procedures summarize the suspected ATT&CK techniques used by Groundbait. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Description | Confidence
-- | --------- | ----------- | ----------
1 | T1059.007 | Cross Site Scripting | High
2 | T1068 | Execution with Unnecessary Privileges | High
3 | T1211 | 7PK Security Features | High
4 | ... | ... | ...

There are 1 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These indicators of attack list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Groundbait. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `admin/salesadmin.php` | High
2 | File | `drivers/gpu/drm/udl/udl_fb.c` | High
3 | File | `libwav.c` | Medium
4 | File | `regexp.c` | Medium
5 | File | `src/http.c` | Medium
6 | Library | `mshtmled.dll` | Medium
7 | Argument | `refresh/branchtotable` | High
8 | Argument | `resultpage` | Medium
9 | Argument | `searchterm` | Medium

## References

The following list contains external sources which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/groundbait
* https://www.threatminer.org/report.php?q=Operation-Groundbait-ESET.pdf&y=2016

## Literature

The following articles explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?doc.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2021](https://vuldb.com/?doc.changelog) by [vuldb.com](https://vuldb.com/?doc.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?doc.faq), read the [documentation](https://vuldb.com/?doc) or [contact us](https://vuldb.com/?contact)!
