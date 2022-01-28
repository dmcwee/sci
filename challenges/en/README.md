# Challenges
Challenges are designed to be similar to a customer's scenario.  The material should be reviewed by a team, the requirements extracted, and then implemented in the environment. In many cases the scenario can be solved in multiple ways and so discussion of "this approach" vs. "that approach" is helpful.

## Thoughts for MWA Challenges
1. **Challenge 3** - includes some compliance policy application via Azure Security Center.  This may not be useful to the MWAs, but a similar scenario that uses Compliance Center in M365 could be substituted here. Also, this is where Sentinel is set up and while that would be great, the subscriptions may be an issue.
1. **Challenge 6** - Remove as this challenge is only focused on Azure solutions
1. **Challenge 7** - Remove Sentinel integration/component
1. **Challenge 9** - Remove the Sentinel integration

## TODO ##
- [X] **Challenge 3** Remove Azure Security Center tasks and measures.
- [ ] **Challenge 3** Add more M365 Compliance considerations to this scenario.  Things like Endpoint DLP settings, email tool tips, etc. may be more useful.
- [X] **Challenge 7** Remove Sentinel references
- [ ] **Challenge 7** Add more Defender for Endpoint scenarios/cases to this 
- [ ] **Challenge 9** Remove the Sentinel integration

## Index of Technology and Challenges ##
1. **Challenge 1** 
    1. Licensing
    1. Azure AD
    1. Insider Risk Management
1. **Challenge 2**
    1. M365 Secure Score
    1. Azure AD
        1. MFA
        1. Conditional Access
        1. Password Policies
    1. Defender for Endpoint
        1. Initial provisioning of tenant
        1. Activation of Lab
    1. Licensing
    1. Defender for Office
1. **Challenge 3**
    1. Compliance Manager
        1. Assign Templates
        1. Resolve Tasks
    1. Azure AD
        1. Password Policies
        1. Conditional Access Policies
        1. Account Policies
    1. Lockbox
1. **Challenge 4**
    1. MIP
    1. DLP (Email, Teams, SPO)
    1. Endpoint DLP
    1. Insider Risk
1. **Challenge 5**
    1. Azure AD
        1. Conditional Access
        1. Priviledged Access
        1. Groups
1. **Challenge 6** - This needs to be replaced by something else. 
1. **Challenge 7**
    1. Defender for Endpoint
        1. Attack Simulations
        1. Advanced Hunting
    1. MDCA Integration with MDE
1. **Challenge 8**
    1. Microsoft Endpoint Manager
        1. Onboard a single machine to MEM
        1. Integrate with MDE
        1. Conditional Access/Compliance Policy
    1. MDE
        1. Execute Attack Script
    1. MDO
        1. Attack Simulator
1. **Challenge 9**
    1. MDCA
        1. Sanction/Unsanction Apps
        1. Import logs from firewalls
        1. Integrate with MDE
        1. *MISSING:* Looking for documents in the tenant that are over shared or missing labels
        1. *MISSING:* Limiting sessions based on machine type