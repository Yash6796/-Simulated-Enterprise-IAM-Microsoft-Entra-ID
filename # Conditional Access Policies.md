# Conditional Access Policies

## 1. High-Risk Sign-in Block

- **Name**: Block High Risk Sign-Ins
- **Target Users**: All users
- **Conditions**:
  - Sign-in Risk: High
- **Access Control**:
  - Action: Block access

## 2. MFA Enforcement for Admins

- **Name**: Enforce MFA for Admins
- **Target**: Global Admins, Security Admins
- **Condition**:
  - User risk: Medium or above
- **Control**:
  - Grant Access → Require MFA

## 3. Country Restriction for Finance

- **Name**: Restrict Finance Dept to India
- **Target Group**: Finance-Group
- **Condition**:
  - Location: Outside India
- **Control**:
  - Block access
