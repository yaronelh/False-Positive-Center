# False Positive Center
Repository to help security vendors deal with false positives, improving their detection engine, and centralize information for software developers making it easier to submit false positives to AV companies.

The repository lists the emails, and websites security vendors (antivirus companies) used to receive false positive reports. it's an effort to facilitate communication between software developers and security vendors.

[AV companies are not responsive? Look at the bottom for additional details.](#av-companies-are-not-responsive)


### Please use pull requests to:
- Add missing vendors
- Update information
- Change out-of-date information

#### What should be included in the email?
A few things are basically required by all security vendors, and would likely lead to better communication. So make sure your email includes the following when sent.
- The detection name
- Product (when applicable, some vendors have multiple different AV product at virus total, list which produced the detection)
- The VirusTotal link, or OPSWAT

#### VirusTotal (Important)

A flagged detection on virustotal does not mean, that the commercial version of that security vendor will detect/flag the file the same way. Security vendors usually configure their VirusTotal implementation to be more sensitive/differently than their actual product

Quote from [this VirusTotal Q&A](https://support.virustotal.com/hc/en-us/articles/115002094589-Why-do-not-you-include-statistics-comparing-antivirus-performance-)  
- VirusTotal's antivirus engines are command line versions, so depending on the product, they will not behave exactly the same as the desktop versions: for instance, desktop solutions may use techniques based on behavioral analysis and count with personal firewalls that may decrease entry points and mitigate propagation, etc.
- In VirusTotal desktop-oriented solutions coexist with perimeter-oriented solutions; **heuristics in this latter group may be more aggressive and paranoid**, since the impact of false positives is less visible in the perimeter. It is simply not fair to compare both groups.
- Some of the solutions included in VirusTotal are parametrized (in coherence with the developer company's desire) with a **different heuristic/aggressiveness level than the official end-user default configuration**.

[*] Emphases not present in the original text, And added for clarity.

#### Antivirus Contact Info For False Positives

| ENGINE | Contact | 
| :--- | :--- | 
| 360 | kefu@360.cn, https://open.soft.360.cn/report.php, http://sampleup.sd.360.cn/ |
| Acronis | virustotal-falsepositive@acronis.com |
| Ad-Aware (Lavasoft) | https://www.adaware.com/report-false-positives, malware.labs@adaware.com |
| Agnitum | trojans@agnitum.com |
| AhnLab-V3 | v3sos@ahnlab.com (recommended), e-support@ahnlab.com, samples@ahnlab.com | 
| Alibaba | virustotal@list.alibaba-inc.com |
| ALYac (ESTsecurity) | esrc@estsecurity.com |
| Antiy-AVL | avlsdk_support_vt@antiy.cn or submit@antiy.com |
| Avast | https://www.avast.com/false-positive-file-form.php, virus@avast.com |
| Avira (no cloud) | https://www.avira.com/en/analysis/submit, cleanset@avira.com, virus_malware@avira.com, virus@avira.com |
| AVG | https://www.avg.com/false-positive-file-form, https://www.avg.com/us-en/whitelist |
| Babable | obu@babable.com |
| Baidu | bav@baidu.com, gaoyingchun@baidu.com |
| BitDefender | https://www.bitdefender.com/consumer/support/answer/40673/, virus_submission@bitdefender.com, oemsamples@bitdefender.com| 
| Bkav Pro | fpreport@bkav.com, bkav@bkav.com |
| ByteHero | bytehero@163.com |
| CAT-QuickHeal | viruslab@quickheal.com, OEMENGINE@quickheal.com |
| Certego | https://www.certego.net/en/contatti/ |
| ClamAV | https://www.clamav.net/reports/fp |
| Clean-MX | abuse@clean-mx.de |
| CMC | vulambang@cmcinfosec.com, support.is@cmclab.net |
| Comodo | https://www.comodo.com/home/internet-security/submit.php, malwaresubmit@avlab.comodo.com |
| CRDF | labs@crdf.fr |
| CrowdStrike Falcon | VTscanner@crowdstrike.com |
| CyanSecurity | virustotal@cyansecurity.com |
| Cybereason | vt-feedback@cybereason.com |
| Cylance | cylancefilesubmit@cylance.com, [General instructions for submission](https://support.blackberry.com/kb/articleDetail?language=en_US&articleNumber=000067337) |
| Cynet | soc@cynet.com |
| CyRadar | virustotal@cyradar.com |
| Cyren | support@cyren.com, Instructions: https://www.cyren.com/support/reporting-av-misclassifications | 
| DNS8 | dns8@layer8.pt |
| DrWeb | https://vms.drweb.com/sendvirus/, vms@drweb.com |
| eGambit (TEHTRIS) | https://tehtris.com/en/false-positives-false-negatives/|
| Emsisoft | submit@emsisoft.com or fp@emsisoft.com (false positives), https://www.emsisoft.com/en/support/contact/ | 
| Endgame | info@endgame.com |
| eScan (Microworld) | samples@escanav.com, http://support.mwti.net/support/index.php?/Tickets/Submit/ |
| ESET-NOD32 | https://support.eset.com/kb141/?page=content&id=SOLN141 |
| F-Prot | viruslab@f-prot.com |
| F-Secure | https://www.f-secure.com/en/business/support-and-downloads/submit-a-sample, spyware-samples@f-secure.com, vsamples@f-secure.com |
| FireEye | virustotal@fireeye.com |
| Filseclab | fp@filseclab.com |
| Forcepoint (websense) | suggest@forcepoint.com |
| Fortinet | submitvirus@fortinet.com, https://www.fortiguard.com/faq/classificationdispute |
| GData | https://www.gdatasoftware.com/faq/consumer/submit-a-suspicious-file-app-or-url |
| Gridinsoft | antimalware@gridinsoft.com, https://anti-malware.gridinsoft.com/false-detect/ | 
| Hacksoft | virus@hacksoft.com.pe |
| Hauri | viruslab@hauri.co.kr |
| Huorong | seclab@huorong.cn |
| Ikarus | fp@ikarus.at, samples@ikarus.at, false-positive@ikarus.at | 
| Invincea | info@invincea.com |
| Jiangmin | support@jiangmin.com, shaojia@jiangmin.com |
| K7 | reportfp@labs.k7computing.com, k7viruslab@labs.k7computing.com, support@k7computing.com, https://support.k7computing.com/index.php?/ticket/submit-ticket |
| Kaspersky | https://opentip.kaspersky.com/, newvirus@kaspersky.com |
| Kingsoft (Cheetah) | operation@cmcm.com |
| Lionic (AegisLab) | support@aegislab.com, https://www.aegislab.com/reportfp |
| Malwarebytes | https://support.malwarebytes.com/hc/en-us/requests/new (Issue type > Product help > False-positive) |
| Malwares.com (Saint Security) | kog@stsc.com |
| MAX (SaintSecurity) | root@malwares.com |
| MaxSecure | tech@maxpcsecure.com |
| McAfee | Instructions: https://kc.mcafee.com/corporate/index?page=content&id=KB85567, virus_research@avertlabs.com | 
| McAfee-GW-Edition | datasubmission@mcafee.com |
| Microsoft Windows Defender | https://www.microsoft.com/en-us/wdsi/filesubmission |
| NANO-Antivirus | https://www.nanoav.ru/index.php?option=com_content&view=article&id=15&Itemid=83&lang=en, false@nanoav.ru |
| Netcraft | https://report.netcraft.com/report/mistake |
| Norton | https://submit.norton.com |
| nProtect (Inca) | virus_info@inca.co.kr |
| Palo Alto Networks | vt-pan-false-positive@paloaltonetworks.com |
| Panda | falsepositives@pandasecurity.com, virussamples@pandasecurity.com |
| Phising Database | https://github.com/mitchellkrogza/Phishing.Database#please-remove-my-domain-from-this-list- |
| Qihoo-360 | support@360safe.com, https://www.360totalsecurity.com/en/suspicion/false-positive/ | 
| Rising | http://mailcenter.rising.com.cn/filecheck_en/ |
| RocketCyber | support@rocketcyber.com |
| Sangfor Engine Zero | save@sangfor.com.cn, https://sec.sangfor.com/user_feedback?lang=EN-US (registration required) |
| Scrutiny | training@cyberstanc.com |
| SecureAge APEX | https://www.secureage.com/article-report-false-positive |
| SentinelOne (Static ML) | report@sentinelone.com |
| Sophos | https://support.sophos.com/support/s/filesubmission | 
| Spamhaus | https://www.spamhaus.org/dbl/removal/form/ |
| Symantec (Broadcom) | https://symsubmit.symantec.com/, false.positives@broadcom.com |
| Systweak | http://support.systweak.com/kayako/index.php?/Tickets/Submit |
| Tachyon | isarc@inca.co.kr (Password Protected zip file include detection name)|
| Tencent | TAVfp@tencent.com |
| TheHacker | virus@hacksoft.com.pe, falsopositivo@hacksoft.com.pe |
| Trapmine | fp@trapmine.com |
| TrendMicro | https://www.trendmicro.com/en_us/about/legal/detection-reevaluation.html, virus_doctor@trendmicro.com, https://helpcenter.trendmicro.com/en-us/srf/ |
| Trustlook | bd@trustlook.com |
| Trustwave | ADavidi@trustwave.com |
| VBA32 | feedback@anti-virus.by |
| VIPRE | https://www.vipre.com/support/submit-false-positive/ |
| VirusBlokAda | support-en@anti-virus.by |
| VirusDie | partners@virusdie.com |
| VirIT | http://www.tgsoft.it/italy/file_sospetti.asp |
| Webroot | http://snup.webrootcloudav.com/SkyStoreFileUploader/upload.aspx, https://www.webroot.com/us/en/business/support/vendor-dispute-contact-us |
| Webroot SMD | https://www.brightcloud.com/tools/file-change-request.php |
| XVirus | samples@xvirus.net, https://xvirus.net/submit |
| Yandex | yandex-antivir@support.yandex.ru |
| Yomi | yomi-false-positives@yoroi.company |
| Zillya | virus@zillya.com , https://zillya.com/support, help@zillya.com |
| ZoneAlarm by Check Point | zonealarm_VT_reports@checkpoint.com |
| Zoner | false@zonerantivirus.com |


### Antivirus Vendors Whitelisting programs
To decrease the chance of false positives you can consider submitting your program to a Antivirus companies whitelisting program, In the list below (just started 30th January contributions encouraged), Most programs require registration and a manual approval process.

| ENGINE | Link To Whitelisting Program / Allowlist Program | 
| :--- | :--- | 
| Avast | https://support.avast.com/en-ww/article/229/ |
| AVG | https://support.avg.com/SupportArticleView?l=en&urlname=AVG-Threat-Lab-file-whitelist |
| eset | https://support.eset.com/en/kb3345-how-do-i-whitelist-my-software-with-eset |
| Kaspersky | https://www.kaspersky.com/partners/allowlist-program |
| McAfee | https://service.mcafee.com/?locale=en-US&articleId=TS102751&fromSearch=true&page=shell&shell=article-view |
| Semantic (Norton) | [Whitelisting Program Discontinued](https://knowledge.broadcom.com/external/article/152428/adding-software-to-the-symantec-whitelis.html) |




### AV companies are not responsive?
There could be a scenario where an antivirus/security company is not responsive, but to be sure that the issue is not on your end (especially if you're sending emails from your own domain). Check that your DNS records are set up correctly for good deliverability. Add an SPF, DKIM, and DMARC to your DNS records. Some AV companies may ignore emails that are not set up correctly, and some will send a response email with an error, depending on how the individual company is setup.

To check if your DNS is configured correctly, as well as SPF, DKIM, and DMARC, use the Google [Check MX](https://toolbox.googleapps.com/apps/checkmx/) tool.

To do a final verification if the email was verified correctly in SPF, DKIM, and DMARC, send an email to a secondary email account and take a look at the full record to see if it passed. You're looking for this:

![EmailPass](https://github.com/yaronelh/False-Positive-Center/blob/main/EmailPass.png?raw=true)

If you did find an error in your configuration, consider resending the emails you already sent before the fix.

**TIP:** while SPF, and DKIM are relatively simple to setup, you can speed up the DMARC setup by searching for DMARC generator with your favorite search engine, to use a wizard to generate it instead of doing it manually.


### Contributors
Yaron Elharar, Pavel Moiseenko, Justine M.,sln162, Kai Kramer, you?..


#### Special thanks
Ana Tinoco from VirusTotal support, and the VirusTotal support team for making the initial contact information list. The hope of creating better communication between software developers and security vendors.


#### Final notes
While I tried to maintain the accuracy of the information here to the best of my ability, it may be that you encounter inaccuracies as things naturally change over time. If you do find any inaccuracies I encourage you to use a pull request, report an issue, or sending me a message.

#### Other important resources

Certification requirements for windows desktop apps - (article by Microsoft to make sure you're covering the basics)
https://docs.microsoft.com/en-us/windows/win32/win_cert/certification-requirements-for-windows-desktop-apps
