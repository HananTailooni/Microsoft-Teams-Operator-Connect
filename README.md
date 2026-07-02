# Microsoft-Teams-Operator-Connect-Deployment-Telnyx-
This project demonstrates a complete deployment of Microsoft Teams Operator Connect using Telnyx as the certified operator provider.
The project covers end-to-end onboarding, carrier integration, emergency address configuration, phone number onboarding, user assignment, and PSTN validation.

# Objectives

- ✅ Deploy Microsoft Teams Operator Connect
- ✅ Integrate Telnyx certified carrier services
- ✅ Import existing PSTN numbers into Teams
- ✅ Configure emergency locations
- ✅ Assign Operator Connect numbers to Teams users
- ✅ Validate inbound and outbound PSTN calling




# Architecture:
PSTN --> Telynx Operator connect --> Teams cloud --> Teams users



# Implementation Steps:
1. Direct Routing Cleanup:
- ✅ Removed Direct Routing number associations
- ✅ Removed SBC dependencies
- ✅ Released previously assigned numbers
2. Operator Connect Onboarding:
- ✅ Established Operator Connect relationship
- ✅ Connected tenant with Telnyx
- ✅ Published numbers to Teams
3. Emergency Location Configuration:
- ✅ Created and validated emergency addresses
- ✅ Associated emergency location with Operator Connect inventory
4. Number Assignment:
- ✅ Imported numbers into Teams inventory
- ✅ Assigned Operator Connect number to user
5. Validation:
- ✅ Inbound PSTN Testing
- ✅ utbound PSTN Testing
- ✅ Two-way audio verification
- ✅ Teams dialpad validation



# Challenges Encountered:
- ✅ Operator Connect synchronization delays
- ✅ Direct Routing inventory conflicts
- ✅ Emergency location synchronization issues
- ✅ Usage location mismatch errors
- ✅ Geographic assignment validation

#Final Outcome:
Successfully deployed Microsoft Teams Operator Connect using Telnyx with full PSTN functionality validated.lity validated.

# Documentation 
[Operator Connect.pdf](Operator%Connect.pdf)
