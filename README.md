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

Quote from [this VirusTotal Q&A](https://docs.virustotal.com/docs/antivirus-stats)
- VirusTotal's antivirus engines are command line versions, so depending on the product, they will not behave exactly the same as the desktop versions: for instance, desktop solutions may use techniques based on behavioral analysis and count with personal firewalls that may decrease entry points and mitigate propagation, etc.
- In VirusTotal desktop-oriented solutions coexist with perimeter-oriented solutions; **heuristics in this latter group may be more aggressive and paranoid**, since the impact of false positives is less visible in the perimeter. It is simply not fair to compare both groups.
- Some of the solutions included in VirusTotal are parametrized (in coherence with the developer company's desire) with a **different heuristic/aggressiveness level than the official end-user default configuration**.

[*] Emphases not present in the original text and added for clarity.

#### Antivirus Contact Info For False Positives

In addition to the information in the table below, VirusTotal also has their own listing of contact information for antivirus companies. You can find it [here](https://docs.virustotal.com/docs/false-positive-contacts).

| ENGINE | Contact | 
| :--- | :--- | 
| 360 | kefu@360.cn, https://open.soft.360.cn/report.php, http://sampleup.sd.360.cn/ |
| Acronis | virustotal-falsepositive@acronis.com |
| Ad-Aware (Lavasoft) | https://www.adaware.com/report-false-positives, malware.labs@adaware.com |
| Agnitum | trojans@agnitum.com |
| AhnLab-V3 | v3sos@ahnlab.com (recommended), e-support@ahnlab.com, samples@ahnlab.com | 
| AlphaMountain ai | https://www.alphamountain.ai/contact/ or support@alphamountain.freshdesk.com |
| Alibaba | virustotal@list.alibaba-inc.com |
| ALYac (ESTsecurity) | esrc@estsecurity.com |
| Antiy-AVL | support@antiy.cn, avlsdk_support@antiy.cn |
| Arcabit | vt.fp@arcabit.pl or virus@arcabit.com |
| Avast | https://www.avast.com/report-false-positive, virus@avast.com |
| Avira (no cloud) | https://www.avira.com/en/analysis/submit, novirus@avira.com |
| AVG | https://www.avg.com/false-positive-file-form, https://www.avg.com/us-en/whitelist |
| Babable | obu@babable.com |
| Baidu | bav@baidu.com, gaoyingchun@baidu.com |
| BitDefender | https://www.bitdefender.com/consumer/support/answer/40673/, virus_submission@bitdefender.com, oemsamples@bitdefender.com| 
| Bkav Pro | fpreport@bkav.com, bkav@bkav.com |
| ByteHero | bytehero@163.com |
| Certego | https://www.certego.net/en/contatti/, fp@certego.net |
| ClamAV | https://www.clamav.net/reports/fp |
| Clean-MX | abuse@clean-mx.de |
| CMC | vulambang@cmcinfosec.com, support.is@cmclab.net |
| CRDF Labs | https://threatcenter.crdf.fr/false_positive.html |
| CrowdStrike Falcon | VTscanner@crowdstrike.com |
| CyanSecurity | virustotal@cyansecurity.com |
| Cybereason | vt-feedback@cybereason.com |
| Cylance | cylancefilesubmit@cylance.com, [General instructions for submission](https://support.blackberry.com/pkb/s/article/67337) |
| Cynet | soc@cynet.com |
| CyRadar | virustotal@cyradar.com |
| Cyren | support@cyren.com, Instructions: https://www.cyren.com/support/reporting-av-misclassifications | 
| DeepInstinct  | info@deepinstinct.com |
| DNS8 | dns8@layer8.pt |
| DrWeb | https://vms.drweb.com/sendvirus/, vms@drweb.com |
| eGambit (TEHTRIS) | https://tehtris.com/en/false-positives-false-negatives/|
| Elastic | https://docs.google.com/forms/d/e/1FAIpQLSd2WQ-o7Y31Hf1PKvdxxd1iMNSxkoBth1cVDJZRuXuAmaD3rg/viewform, https://discuss.elastic.co/t/submitting-false-positives/232322 |
| Emsisoft | submit@emsisoft.com or fp@emsisoft.com (false positives), https://www.emsisoft.com/en/help/contact/ | 
| Endgame | info@endgame.com |
| eScan (Microworld) | samples@escanav.com, http://support.mwti.net/support/index.php?/Tickets/Submit/ |
| ESET-NOD32 | samples@eset.com, ([more information here](https://support.eset.com/kb141/?page=content&id=SOLN141))   |
| F-Prot | viruslab@f-prot.com |
| F-Secure | https://www.f-secure.com/en/business/support-and-downloads/submit-a-sample |
| Filseclab | fp@filseclab.com |
| Forcepoint (websense) | suggest@forcepoint.com or https://support.forcepoint.com/s/article/000012884, [File Submission Tool](https://support.forcepoint.com/s/article/000019083), [URL Submission Tool](https://support.forcepoint.com/s/article/URL-List-submission-Tool) |
| Fortinet | submitvirus@fortinet.com, https://www.fortiguard.com/faq/classificationdispute |
| GData | https://www.gdata.de/help/en/general/AllgemeineFragen/DateiURLAppEinsenden |
| Google | google-at-virustotal@google.com, or go through this process, First upload the file to Google Drive (Preferably don't use your main account). Once uploaded, if the file was identified it will be flagged, right-click on the file and select **Open With** -> **Preview**. Google Drive will display '*This file looks suspicious. It is visible only to the owner.*' alert, click **request a review**. On the **Request a review** page, click the **Request file review** button at the bottom of the page. [Demo Video](https://github.com/yaronelh/False-Positive-Center/pull/76#issuecomment-1963005790) |
| Gridinsoft | antimalware@gridinsoft.com, https://gridinsoft.com/incorrect-detection |
| Hacksoft | virus@hacksoft.com.pe |
| Hauri | viruslab@hauri.co.kr |
| Huorong | seclab@huorong.cn |
| Ikarus | samples@ikarus.at, false-positive@ikarus.at | 
| Invincea | info@invincea.com |
| Jiangmin | support@jiangmin.com, shaojia@jiangmin.com |
| K7 (K7GW) | reportfp@labs.k7computing.com, k7viruslab@labs.k7computing.com, support@k7computing.com, https://support.k7computing.com/index.php?/ticket/submit-ticket |
| Kaspersky | https://opentip.kaspersky.com/, newvirus@kaspersky.com, or https://support.kaspersky.com/b2c/il#contacts (OS > Application > Malware > False positive > Continue to contact support button > Upload file) |
| Kingsoft (Cheetah) |  ti@mingting.cn |
| Lionic (AegisLab) | support@aegislab.com, https://www.lionic.com/reportfp |
| Malwarebytes | https://support.malwarebytes.com/hc/en-us/articles/360038524154-Report-a-false-positive-to-Malwarebytes-Support or for clients https://support.malwarebytes.com/hc/en-us/requests/new (Issue type > Product help > False-positive). |
| Malwares.com (Saint Security) | kog@stsc.com |
| MAX (SaintSecurity) | root@malwares.com |
| MaxSecure | tech@maxpcsecure.com |
| McAfee | [https://www.mcafee.com/support/s/article/000001921](https://www.mcafee.com/support/s/article/000001921), virus_research@avertlabs.com instructions for email submissions [here](https://www.mcafee.com/support/s/article/000001662?language=en_US#:~:text=How%20to%20send%20sample%20files%20to%20McAfee)| 
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
| QuickHeal | viruslab@quickheal.com, OEMENGINE@quickheal.com, support@quickheal.com, https://techsupport.quickheal.com/report-an-issue/false-positive |
| Rising | http://mailcenter.rising.com.cn/filecheck_en/ |
| RocketCyber | support@rocketcyber.com |
| Sangfor Engine Zero | To report false positives follow their [instruction guide](https://github.com/yaronelh/False-Positive-Center/blob/main/Sangfor%20Engine%20Zero%20false%20positive%20instruction%20guide.pdf) |
| Scrutiny | training@cyberstanc.com |
| Seclookup | info@seclookup.com |
| SecureAge APEX | https://www.secureage.com/support/report-false-positive |
| SentinelOne (Static ML) | report@sentinelone.com |
| Skyhigh (SWG) | Use the [Avira Process](https://success.skyhighsecurity.com/Skyhigh_Secure_Web_Gateway_%28On_Prem%29/Anti-malware_Filtering/How_to_submit_false_positive%2F%2Fnegative_samples_for_review), or email virus_research_gateway@avertlabs.com |
| Sophos | https://support.sophos.com/support/s/filesubmission, for email submission/other options [see this article](https://support.home.sophos.com/hc/en-us/articles/360041664851-How-to-review-and-submit-samples-of-suspicious-files-or-false-positives-to-Sophos?section=Additional%20file%20submission%20options)  | 
| Spamhaus | https://www.spamhaus.org/dbl/removal/form/ |
| Symantec (Broadcom) | https://symsubmit.symantec.com/, false.positives@broadcom.com |
| Systweak | http://support.systweak.com/kayako/index.php?/Tickets/Submit |
| Tachyon | isarc@inca.co.kr (Password Protected zip file include detection name)|
| Tencent | TAVfp@tencent.com |
| TheHacker | virus@hacksoft.com.pe, falsopositivo@hacksoft.com.pe |
| Trapmine | fp@trapmine.com (Concluding operations December 31) |
| Trellix (FireEye) | https://kcm.trellix.com/corporate/index?page=content&id=KB85567 |
| TrendMicro | https://www.trendmicro.com/en_us/about/legal/detection-reevaluation.html, virus_doctor@trendmicro.com, https://helpcenter.trendmicro.com/en-us/srf/ |
| Trustlook | bd@trustlook.com |
| Trustwave | ADavidi@trustwave.com |
| Varist | SampleFP@avsubmit.com , support@varist.com |
| VBA32 | feedback@anti-virus.by |
| VIPRE | https://helpdesk.vipre.com/hc/en-us/requests/new |
| VirusBlokAda | support-en@anti-virus.by |
| VirusDie | partners@virusdie.com |
| VirIT | http://www.tgsoft.it/italy/file_sospetti.asp |
| Webroot | http://snup.webrootcloudav.com/SkyStoreFileUploader/upload.aspx, https://www.webroot.com/us/en/business/support/vendor-dispute-contact-us, https://www.brightcloud.com/tools/url-ip-lookup.php (enter URL in `Look up URL or IP:` and click `Look Up`, then click `Request a reputation change` on the right, fill `Request a Change:` form and click `Submit`) |
| Webroot SMD | https://www.brightcloud.com/tools/file-change-request.php |
| Xcitium (Comodo) | https://www.comodo.com/home/internet-security/submit.php, malwaresubmit@avlab.comodo.com, security@xcitium.com, support@xcitium.com, https://forum.xcitium.com/ |
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


#### Special thanks
Ana Tinoco from VirusTotal support, and the VirusTotal support team for making the initial contact information list. The hope of creating better communication between software developers and security vendors.
You can also find the VirusTotal vendor [contact list here](https://docs.virustotal.com/docs/false-positive-contacts)


#### Final notes
While I tried to maintain the accuracy of the information here to the best of my ability, it may be that you encounter inaccuracies as things naturally change over time. If you do find any inaccuracies I encourage you to use a pull request, report an issue, or sending me a message.

#### Other important resources

Certification requirements for windows desktop apps - (article by Microsoft to make sure you're covering the basics)
https://docs.microsoft.com/en-us/windows/win32/win_cert/certification-requirements-for-windows-desktop-apps
