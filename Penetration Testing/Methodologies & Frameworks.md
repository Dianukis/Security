<h1 align="center">
<a href="https://purplesec.us/penetration-testing-methodologies/#Methodology">
    Advanced Penetration Testing Methodologies & Frameworks
</a>
</h1>

![image](https://user-images.githubusercontent.com/51442719/146185485-8f6d0050-ec3e-4dea-8694-e918234f9f90.png)

### Article Navigation

- Step 1: Planning and Preparation
- Step 2: Scanning / Assessment
- Step 3: Exploitation and Data Exfiltration
- Step 4: Reporting, Cleanup, and Destruction of Artifacts

---

## Step 1: Planning and Preparation

<details>
 <summary>
More Info
    </summary> 
<br>

During this step, both parties exchange initial information, plan, and prepare for the IT Security Assessment.

 

Prior to testing, a formal assessment agreement is signed by both parties.

 

This agreement provides the basis for all project work and mutual legal protection. It will also specify the specific engagement team, the exact dates, times of the test, escalation path, and other arrangements.

#### The primary outcome of the planning and preparation step is the:

- Identification of contact individuals from both sides.
- Opening meeting to confirm the scope, approach and methodology.
- Agreement to specific test cases and privilege escalation paths.
 
 </details>

---

## Step 2: Perform A Scan / Assessment
 
<details>
 <summary>
More Info
 </summary> 
<br>

A vulnerability assessment is a layered approach that includes an actual penetration test. During this step, a test plan is developed, tool kits are built, the assessment itself is conducted, and analysis of the assessment is performed.

### Develop A Test Plan
 

Based on the information gathered during planning and preparation a detailed test plan that outlines the steps necessary to produce the final vulnerability assessment report is created.
The test plan also includes the resources and the methodology used to assess and exploit the vulnerabilities on the target network.

 

### Build The Toolkit
 

Once the test plan has been developed a list of testing tools (commercial, publicly available, manual), methodologies, and publicly available exploits is drafted.

 

The purpose of this is to have a clearly defined path for the pen tester to identify and exploit vulnerabilities in the target systems in order to gain unauthorized access.
It’s considered best practice to include a list of tools and methodologies used for testing within the final report.

 

However, if the vendor does not provide this information then ask and they will produce the list.

 

### Conduct The Assessment
 

By running the selected tools and applying the chosen methodologies, a large amount of information is gathered about the target network systems and related vulnerabilities.
This information is crucial to penetrating the corporate defenses or being used in another part of the external assessment.

 

### Analysis
 

The assessment phase usually produces a large amount of raw data.

 

The analysis phase allows security engineers the opportunity to review the findings and develop a strategy on possible weaknesses and possible means of exploitation. The engineer will attempt to identify all active systems present on the network and determine software and hardware versions installed.

 

If a particular host employs authentication services (such as Mail or FTP server) it will be checked for the presence of default or standard login accounts. Lastly, this phase will determine the priority and risk profile of all vulnerabilities.

</details>

---

## Step 3: Exploitation and Data Exfiltration
 
<details>
 <summary>
More Info
 </summary> 
<br>

Once the vulnerabilities are identified in the previous phase an engineer will attempt to verify the validity of these vulnerabilities by exploiting them.

 

This task will only be performed at the request of the customer and only after having obtained formal authorization. The benefit of performing this step is positive verification that the particular vulnerability exists.

 

The engineer will review the strength of any authentication systems present on network hosts and on remote terminal sessions by attempting to use easily guessable passwords based on common English dictionary.

 

### Establishment And Extraction
 

Carrying the previous task further, the engineer will attempt to gain access to the information contained on the protected network segments. Once within the system, the customer will be provided with evidence of the penetration.


### Attack Vectors
 

Penetration tests use a variety of attack vectors in an attempt to exploit weaknesses and threats within systems or web applications.

 

#### These attack vectors may consist of any of the following methods:

- Invalidated input
- Broken authentication
- Insecure transmission
- Denial of service (DoS)
- Broken access controls
- Weak data protection
- Broken session management
- Cross-site scripting (XSS)
- Insecure storage
- Injections Buﬀer over ﬂows
- Cross-site request forgery (CSRF)
- SSL certificate security
- Improper error handling
- Cookie poisoning
- Privilege escalation
- Insecure configuration
- XML external entry expansion
- Information disclosure
- System ﬁnger printing
- Services probing
- Analysis and identification of attack vectors
- Exploit testing
- Authentication attacks
- Vulnerability exploitation
- Exploitation of configuration ﬂaws
- Credential spraying
- SQL injection
- Unauthorized access to sensitive data

</details>

---

## Step 4: Reporting, Cleanup, and Destruction of Artifacts

<details>
 <summary>
More Info
 </summary> 
<br>
        
> Clean Up And Destroy Artifacts
 
All information that is created and/or stored on the tested systems will be removed from these systems. If this is for some reason not possible from a remote system, all these files (with their location) will be detailed in the technical report so that your technical staff will be able to remove these after the report has been received.

### Project Deliverables
 
When engaging with a vendor it’s important to fully understand the types of reports that will be delivered. The value in performing a penetration test is greatly tied to the outcome of these reports in order for senior management teams to make informed decisions on how best to secure their systems.

#### Project deliverables for penetration testing may include the following reports:

- Reconnaissance scoping report
- Detailed technical report
- Itemized exportable report
- Executive summary report
- Remediation reports


### Reconnaissance Scoping Report

A document listing the systems in scope discovered during the reconnaissance or discovery phases.

This should include output from information gathering and discovery activities that are intended to map the attack surface of the target environment. This will be reviewed to determine if any scoping adjustments need to be made.


### Detailed Technical Report

#### The technical pen test report typically includes:

>- The methodology employed including the threat model.
>- Positive security aspects identified.
>- Detailed technical vulnerability findings.
>- A risk rating for each vulnerability.
>- Supporting detailed exhibits for vulnerabilities when appropriate.

Post remediation updated reports may be also be requested in the event there are open issues.

### Itemized Exportable Report
 
> A report in an exportable format (Excel, XML) is typically delivered to the customers. This itemized list includes all findings with high-level category, subcategories, criticality, and IP/hostname, which is required for input into a risk tracking system.
> 
> A bank template may also be provided.


### Executive Summary Report
 
> A document developed to summarize the scope, approach, findings, and recommendations, in a manner suitable for senior management.  
>
> It is typical of a vendor to provide an executive presentation to discuss the report in further detail and to ensure all obligations within the scope of work have been satisfied.

### Remediation Reports
 
> Upon completion of the initial test, the customer will work to remediate known vulnerabilities and exploits as outlined in the final report.
>
>A retest is then performed on high and medium findings after the remediation period. The purpose of this retest is to validate and confirm that issues were remediated or mitigated.
    
 </details>
