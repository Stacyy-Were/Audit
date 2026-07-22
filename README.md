# Audit

## PERSONAL SECURITY AUDIT REPORT

Auditor:       [Stacy Were]
Audit Date:    [22/07/2026]
Engagement:    Personal Digital Security Assessment
Methodology:   Scope > Intelligence > Exposure > Severity > Remediation


------------------------------------------------------------
 ## 1. SCOPE
------------------------------------------------------------

Systems and accounts assessed:
  - Primary email:   [e.g. stacywerewere@gmail.com]
  - Key accounts:    [e.g. Google, Spotify, Instagram, GitHub, LinkedIn, Bank]
  - Primary device:  [e.g. Samsung, Microsoft, HP]
  - Network:         [e.g. home Wi-Fi (LWB)]


------------------------------------------------------------
 ## 2. EXECUTIVE SUMMARY
------------------------------------------------------------


 ### Assessment identified 3 critical breaches:
 1. In March 2026, hackers claimed they had obtained data from the gig economy platform Paidwork which they then listed for sale. Almost 11GB of data allegedly obtained from the platform was subsequently posted publicly in July and contained over 23M unique email addresses. The breach also included a broad range of other data relating to the operation of the platform including user profile data, banking information, payout history for workers and passwords stored as bcrypt hashes.

    Compromised data:
    * Bank account numbers
    * Dates of birth
    * Device information
    * Education levels
    * Email addresses
    * Financial transactions
    * Genders
    * IP addresses
    * Names
    * Passwords
    * Personal interests
    * Phone numbers
    * Physical addresses
    * Profile photos\

2. In January 2024, data was scraped from Trello and posted for sale on a popular hacking forum. Containing over 15M email addresses, names and usernames, the data was obtained by enumerating a publicly accessible resource using email addresses from previous breach corpuses. Trello advised that no unauthorised access had occurred.

    Compromised data:
    * Email addresses
    * Names
    * Usernames

3. In June 2020, the user-generated stories website Wattpad suffered a huge data breach that exposed almost 270 million records. The data was initially sold then published on a public hacking forum where it was broadly shared. The incident exposed extensive personal information including names and usernames, email and IP addresses, genders, birth dates and passwords stored as bcrypt hashes.

    Compromised data:
    * Bios
    * Dates of birth
    * Email addresses
    * Genders
    * Geographic locations
    * IP addresses
    * Names
    * Passwords
    * Social media profiles
    * User website URLs
    * Usernames



------------------------------------------------------------
 ## 3. FINDINGS
------------------------------------------------------------

CRITICAL
  [ ] Primary email (Gmail) has no 2FA enabled
  [ ] Password is reused across accounts

HIGH
  [ ] Trello and Wattpad breach exposed PII;
        password pattern still in use elsewhere
  [ ] Unrecognised Chrome session active on Google
        account from an IP last used 11 months ago

MEDIUM
  [ ] 14 third-party apps have access to Google account;
        many not used in over 12 months
  [ ] Primary email publicly tied to inactive Skype
        account via OSINT tools

LOW
  [ ] Forgotten LinkedIn account from 2015 still active
        under previous email


------------------------------------------------------------
 ## 4. ACTIONS TAKEN DURING AUDIT
------------------------------------------------------------

  [x] [e.g. Enabled authenticator-app 2FA on primary email]
  [x] [e.g. Logged out of 2 unrecognised sessions on Google]
  [x] [e.g. Revoked access for 9 unused third-party apps]


------------------------------------------------------------
 ## 5. REMEDIATION PLAN
------------------------------------------------------------

This week:
  [ ] [e.g. Enable 2FA on remaining 4 key accounts]
  [ ] [e.g. Change reused password on banking login]

This month:
  [ ] [e.g. Set up Bitwarden and migrate all saved passwords]
  [ ] [e.g. Delete forgotten LinkedIn account from 2021]



 END OF REPORT