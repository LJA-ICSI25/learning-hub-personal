# Server22 GPO

# Account Policy 1

## Password Policy 1.1
### Password History 1.1.1
- 24 or more password(s)
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Enforce password history
### Maximum password age 1.1.2
- 265 of fewer days, but not 0
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Maximum password age
### Maximum password age (STIG) 1.1.3
- 60 of fewer days, but not 0
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Maximum password age
### Minimum password age 1.1.4
- 1 or more day(s)
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Minimum password age
### Minimum password length 1.1.5
- 14 or more characters
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Minimum password length
### Password must meet complexity requirements 1.1.6
- Enabled
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Password must meet complexity requirements
### Relax minimum password length limits 1.1.7
- Enabled
- HKLM\System\CurrentControlSet\Control\SAM:RelaxMinimumPasswordLengthLimits
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Relax minimum password length limits
### Store passwords using reversible encryption 1.1.8
- Disabled
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Password Policy\Store passwords using reversible encryption

## Account Lockout Policy 1.2
### Account lockout duration 1.2.1
- 15 or more minutes
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Account Lockout Policy\Account lockout duration
### Account lockout threshold 1.2.2
- 5 or fewer invalid logon attempts, but not 0
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Account Lockout Policy\Account lockout threshold
### Account lockout threshold (STIG) 1.2.3
- 3 or fewer invalid logon attempts, but not 0
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Account Lockout Policy\Account lockout threshold
### Allow Administrator account lockout 1.2.4
- Enabled
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Account Lockout Policies\Allow Administrator account lockout
### Reset account lockout counter after 1.2.5
- 15 or more minutes
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policies\Account Lockout Policy\Reset account lockout counter after

## Kerberos Policy 1.3 
### Enforce user logon restrictions 1.3.1
- STIG DC only 
- Manual
- Enabled
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policy\Kerberos Policy\Enforce user logon restrictions
### Maximum lifetime for service ticket 1.3.2
- STIG DC only
- Manual
- 600 or fewer minutes, but not 0
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policy\Kerberos Policy\Maximum lifetime for service ticket
### Maximum lifetime for user ticket 1.3.3
- STIG DC only
- Manual
- 10 or fewer hours, but not 0
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policy\Kerberos Policy\Maximum lifetime for user ticket
### Maximum lifetime for user ticket renewal 1.3.4
- STIG DC only
- Manual
- 7 or fewer days
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policy\Kerberos Policy\Maximum lifetime for user ticket renewal
### Maximum tolerance for computer clock synchronization 1.3.5
- STIG DC only
- Manual
- 5 or fewer minutes
- Computer Configuration\Policies\Windows Settings\Security Settings\Account Policy\Kerberos Policy\Maximum tolerance for computer clock synchronization

# Local Policies 2

## Audit Policy 2.1
### Access Credential Manager as a trusted caller
- No one
- Computer Configuration\Policies\Windows Settings\Security Settings\Local Policies\User Rights Assignment\Access Credential Manager as a trusted caller
### Access this computer from the network 
- Administrators, Authenticated Users, ENTERPRISE DOMAIN CONTROLLERS
- DC only
- Computer Configuration\Policies\Windows Settings\Security Settings\Local Policies\User Rights Assignment\Access this computer from the network
### Access this computer from the network
- Administators, Authenticated Users
- MS only
- Computer Configuration\Policies\Windows Settings\Security Settings\Local Policies\User Rights Assignment\Access this computer from the network

## User Rights Assignment 2.2
