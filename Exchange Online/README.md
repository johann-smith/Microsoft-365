<H1>The Office 365 Email Security Checklist scripts:</H1>

<H2>You can either run the entire recommended baseline (Baseline-ExchangeOnline), or run the scripts individually:</H2>

<p>• Baseline-365ATP.ps1: Configures Office 365 Advanced Threat Protection (plan 1)
<p>• Baseline-ExchangeOnline.ps1: Configures Exchange Online tenant with all of the baseline settings and policies
<p>• Baseline-M365BTenant.ps1: Includes Baseline-365ATP.ps1 and Baseline-ExchangeOnline.ps1 settings in a single script
<p>• Advanced-TenantConfig.ps1: For further customization of Exchange Online
<p>• Setup-DKIM.ps1: This script helps with configuring DKIM; use: .\Setup-DKIM.ps1 -Domain "yourdomainhere.com"
<p>• Disable-Forwarding.ps1: This script will disable auto-forwarding and also output csv of existing forwarders to C:\temp

<p>Be sure to read the comments and review each script. You are responsible for your own implementation, use at your own risk.
<p>These scripts follow the guide published at: https://www.itpromentor.com/email-security-checklist/
