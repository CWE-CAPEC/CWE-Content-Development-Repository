# CWE Scope Exclusions

Last generated: 2024-05-15 21:37:38

WARNING: this file was automatically generated. Do not edit.

## Scope Exclusions - Summary

| ID | Name |
|----|------|
|[SCOPE.NOTREAL](#SCOPE.NOTREAL)|Not a real-world issue|
|[SCOPE.HUMANPROC](#SCOPE.HUMANPROC)|Human/organizational process|
|[SCOPE.MOTIVE](#SCOPE.MOTIVE)|Motivation instead of the mistake|
|[SCOPE.SITUATIONS](#SCOPE.SITUATIONS)|Focus on situations in which weaknesses may appear|
|[SCOPE.GROUPING](#SCOPE.GROUPING)|Grouping of issues without a common behavior|
|[SCOPE.NOMITS](#SCOPE.NOMITS)|No actionable mitigations|
|[SCOPE.CUSTREL](#SCOPE.CUSTREL)|Not customer-relevant|
|[SCOPE.CONFLICT](#SCOPE.CONFLICT)|Conflict/contradiction with other weaknesses|
|[SCOPE.NOSEC](#SCOPE.NOSEC)|Not security-related|
|[SCOPE.ADMINERR](#SCOPE.ADMINERR)|Admin/user error|


## Details


<a name="SCOPE.NOTREAL"></a>
## **SCOPE.NOTREAL - "Not a real-world issue"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The issue has not happened and cannot occur in real-world software or other electronic logic, and/or has no actual security implications.|
|**Rationale**||
|**Examples**|Due to a misinterpretation of source material, CWE-365 originally described an insecure behavior that did not exist in any real-world compilers, so it was deprecated.|
|**Debates**|No active debate.|
|**Resolution**|As of January 2023, the submission will be rejected or delayed pending close review, possibly including community engagement.|



<a name="SCOPE.HUMANPROC"></a>
## **SCOPE.HUMANPROC - "Human/organizational process"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The submission focuses on a problem in a human or organizational process or policy (e.g., insufficient developer training) that is not measurable and does not produce concrete artifacts that identify weaknesses. Note: this scope exclusion does NOT apply to cases in which humans directly influence insecure behavior of a product, such as insecure configuration (which can also be automated or performed by code, not humans).|
|**Rationale**|Weaknesses can emerge as a result of these activities. Other efforts cover this area, e.g., BSIMM, OWASP SAMM, and NIST Secure Software Development Framework.<br><br>Note that this exclusion is similar to SCOPE.ADMINERR in that it reflects human actions.|
|**Examples**|Lack of developer training, insufficient testing, not following secure coding standards, corporate policy gaps, or human resource / people-management problems such as not hiring enough people.<br><br>CWE-1297 is about the potential for leakage of NDA information between non-customer organizations during the manufacturing process.|
|**Debates**|No active debate, but manufacturing processes (of concern to HW/supply chain) may fall under this exclusion, as would ICS/OT.|
|**Resolution**|As of January 2023, such submissions will be rejected (if framed as "weaknesses") but could help modify existing CWEs for elements such as modes of introduction.|



<a name="SCOPE.MOTIVE"></a>
## **SCOPE.MOTIVE - "Motivation instead of the mistake"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|Any characterization of motivation (e.g., "malicious") that does not focus on the actual weakness, whether intentionally or accidentally introduced.|
|**Rationale**|A weakness is based on the behavior of the product, and malicious actors can introduce the same weaknesses as non-malicious developers.|
|**Examples**||
|**Debates**|No active disagreement as of January 2023.|
|**Resolution**|As of January 2023, submissions are likely to be rejected unless they can be converted to actual weaknesses. Any provided references or examples could be used to modify demonstrative or observed examples of existing CWEs.|



<a name="SCOPE.SITUATIONS"></a>
## **SCOPE.SITUATIONS - "Focus on situations in which weaknesses may appear"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The submission focuses on conditions or situations in which weaknesses are more likely to appear but are outside of the direct control of the product.|
|**Rationale**|CWE is focused on the flaws/defects that can occur within a product. While various situations can contribute to the introduction of weaknesses, these are better captured as modes of introduction, which are recorded in a separate field in CWE entries.<br><br>CWE-1297 is about the potential for leakage of NDA information between non-customer organizations during the manufacturing process.|
|**Examples**|"The growing connectivity between IT and OT systems can introduce new vulnerabilities." (SEI ETF document on categories of ICS/OT vulnerabilities).|
|**Debates**|No active disagreement as of January 2023.|
|**Resolution**|Submissions are likely to be rejected unless they can be recast as categories or can influence modes of introduction of existing CWEs, i.e., modify entries.|



<a name="SCOPE.GROUPING"></a>
## **SCOPE.GROUPING - "Grouping of issues without a common behavior"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The submission is a grouping of issues or concerns related to the same feature such as technology, language, development lifecycle, etc., but there is not a common behavior between them all.|
|**Rationale**|Weaknesses are based on specific behavior and other shared criteria that can be hierarchically classified under a common ancestor in the research view 1000. If no such ancestor is possible, then the submission is not likely a weakness.|
|**Examples**|"If the developer doesn't process files correctly, attackers can steal or delete data."<br><br>With respect to hardware, weaknesses that have physical characteristics do not share the same hierarchy in research view 1000. However, the hardware community asked for them to be grouped into a category (CWE-1388).|
|**Debates**|No active disagreement as of January 2023.|
|**Resolution**|The submission might be acceptable as a category, or some of its content could modify existing entries. In some cases, the submission might influence subtree organization.|



<a name="SCOPE.NOMITS"></a>
## **SCOPE.NOMITS - "No actionable mitigations"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|There are no actionable mitigations available to the developer/designer/manufacturer to prevent or reduce the weakness.|
|**Rationale**|If a product has a weakness type with no known fixes or mitigations, then a CWE entry would not be helpful to the developer / designer / manufacturer, i.e., it is not actionable.|
|**Examples**|Some techniques for analyzing hardware do not have any practical real-world mitigations for highly-resourced adversaries, yet they remain a concern to defenders.|
|**Debates**|As of January 2023, there is some community disagreement about this scope exclusion: (1) Developers could avoid the affected functionality altogether. (2) Weaknesses without mitigations could serve as topics for academic study.|
|**Resolution**|Submissions will be reviewed on a case-by-case basis, delayed, and possibly cited as examples until this exclusion is finalized after extensive community feedback.|



<a name="SCOPE.CUSTREL"></a>
## **SCOPE.CUSTREL - "Not customer-relevant"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The issue is not relevant to the threat model or security concerns of the product's owner/operator (i.e., the customer).|
|**Rationale**|Traditionally, the focus on publicly-disclosed vulnerabilities has been on products that affect customers. Widening the scope to include non-customer interests would risk creating weaknesses with no relevance to customers who want to acquire secure products.|
|**Examples**|CWE-1278 is about avoiding reverse engineering using certain techniques. While theft of Intellectual Property might be a major concern for vendors, knowledge of how a product works does not affect the customer directly. A separate submission proposed coverage for anti-reverse-engineering: "Protections and measures intended to prevent or hinder reverse engineering of Intellectual Property (IP) are not present in the product design."<br><br>CWE-1297 is about the potential for leakage of NDA information between non-customer organizations during the manufacturing process.|
|**Debates**|As of January 2023, there is some community disagreement about this scope exclusion. Customers are not the only participants within the ecosystem, and concerns such as Intellectual Property violations have clear financial implications for vendors if compromised. If not handled carefully, allowing CWEs in this area could cause conflicts; e.g., if a CWE is created that a product doesn't obscure its code enough, that CWE would apply to all open source products.<br><br>Note that there may be a logical inconsistency between SCOPE.CUSTREL and SCOPE.CONFLICT, since there may be differences in threat models across different industries, and each participant might have different priorities. For example, in healthcare, availability is a priority that may conflict with password requirements, since locking out a medical device user may cause security issues. Similarly, the patients themselves might be considered a threat actor against the security of their device if they can modify the device's behavior in ways that are not allowed by the doctor; the Do-It-Yourself (DIY) community of insulin-pump hackers demonstrates this conflict with device manufacturers.|
|**Resolution**|Submissions will be reviewed on a case-by-case basis, delayed, and possibly cited as examples until this exclusion is finalized after extensive community feedback.|



<a name="SCOPE.CONFLICT"></a>
## **SCOPE.CONFLICT - "Conflict/contradiction with other weaknesses"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The issue directly conflicts with or contradicts other CWE entries, e.g., "X is bad" in one CWE, and "Y is bad so do X instead" in another CWE.|
|**Rationale**|Directly-conflicting CWE entries can cause user confusion and/or suggest some lack of agreement as to what constitutes "secure" products.|
|**Examples**|"The product has code that can be easily reverse-engineered, allowing adversaries to steal Intellectual Property." This statement implies that all open source code has a weakness because it is not obfuscated.|
|**Debates**|As of January 2023, one area of active debate involves the desire of some community members for CWE to include weaknesses for code/logic that can be easily reverse-engineered (note that this is also affected by SCOPE.CUSTREL). If CWE covers a concern that effectively promotes code obfuscation (i.e., says that it's too easy to extract the real code/logic), this could be seen to directly conflict with CWE-656: Reliance on Security Through Obscurity, which effectively follows Kerckhoff's principle, summarized as: "a cryptosystem should be secure, even if everything about the system, except the key, is public knowledge." As another example, in 2021, members of the CWE-Research list discussed older CWE entries related to password aging that directly implied that password aging was an important capability, but the modern belief is that password aging should be unnecessary. Yet, creation of a new entry such as "Reliance on Password Aging" would conflict with the original CWE entries and any products that still rely on passwords.<br><br>Another potential conflict arises when design decisions require tradeoffs between security and other desired features such as safety and reliability.<br><br>Note that there may be a logical inconsistency between SCOPE.CUSTREL and SCOPE.CONFLICT, since there may be differences in threat models across different industries, and each participant might have different priorities. For example, in healthcare, availability is a priority that may conflict with password requirements, since locking out a medical device user may cause security issues. Similarly, the patients themselves might be considered a threat actor against the security of their device if they can modify the device's behavior in ways that are not allowed by the doctor; the Do-It-Yourself (DIY) community of insulin-pump hackers demonstrates this conflict with device manufacturers.|
|**Resolution**|The submission might be rejected unless it reveals some other problems with existing CWE content, which might prevent it from progressing to later stages until the existing CWE issues can be addressed satisfactorily.|



<a name="SCOPE.NOSEC"></a>
## **SCOPE.NOSEC - "Not security-related"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The issue is solely concerned with safety, reliability, or another property not related to security. Clarification on privacy: if an issue is related to desires for access control or preservation of confidentiality, it is within scope of "security".|
|**Rationale**|Many aspects of industrial safety, such as correct electric shielding and insulation, do not affect security. There are many safety-focused standards throughout different industries, and expanding CWE's scope to include safety-only issues would limits utility to most current CWE users.|
|**Examples**||
|**Debates**|As of January 2023, it is suspected that there will be some community disagreement about this scope exclusion.|
|**Resolution**|Submissions will be reviewed on a case-by-case basis, delayed, and possibly cited as examples until this exclusion is finalized after extensive community feedback.|



<a name="SCOPE.ADMINERR"></a>
## **SCOPE.ADMINERR - "Admin/user error"**

| Field | Details |
|-------|---------|
|**Status**|Development|
|**Last Modified**||
|**Description**|The issue focuses on security errors that are made by an admin or user of the product/service, not the developer or maintainer of the product/service.|
|**Rationale**|Traditionally, CWE has covered defects or flaws within the product itself. This is separate from how administrators or users may misuse or abuse the products in ways that were not intended, typically through insecure configuration, so there is little that product developers can do. It seems likely that such issues will not be relevant to most CWE users.<br><br>Note that this exclusion is similar to SCOPE.HUMANPROC in that it reflects human actions.|
|**Examples**||
|**Debates**|As of January 2023, this is a new exclusion. It is suspected that there will be some community disagreement about this scope exclusion, since many services deploy and manage their code for customers in ways that obscure the distinction between system administrators and software developers ("DevOps"). CWE is also intended to cover misconfigurations made by admins, such as running a process at an excessively high privilege level.|
|**Resolution**|Submissions will be reviewed on a case-by-case basis, delayed, and possibly cited as examples until this exclusion is finalized after extensive community feedback.|

