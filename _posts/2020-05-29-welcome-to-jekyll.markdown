---
layout: post
title:  "Increase the security level of SaaS service"
date:   2020-05-29 18:05:55 +0300
image:  SA_banner.jpeg
tags:   Security
---
<!DOCTYPE html>
<html>
<head>
    <title>Synology Account Security Enhancement</title>
    <style>
        body { font-family: Arial, sans-serif; }
        h2 { color: #2A4D69; }
        h3 { color: #4B88A2; }
    </style>
</head>
<body>

    <h2>1. Purpose and Overview</h2>
    <p>The Synology Account is a SaaS service with more than 5 million users. It is the entrance to all the Synology cloud cloud service, including QuickConnect, Active Insight, and C2 services. The security level of the Synology account is critical to all the users and company. In addition, users need to utilize the Synology Account services in order to sign up for Synology Events or participate in the community.</p>
    
    <h3>Objective:</h3>
    <p>As the number of products that are linked to the Synology Account within the company increases, it is more critical to enhance the overall security of our cloud service.</p>
    
    <h3>Approach:</h3>
    <ul>
        <li>Provide multiple ways for users to easily set up multi-factor authentication (MFA).</li>
        <li>Increase user willingness to enable two-factor authentication (2FA) by educating them on its importance.</li>
        <li>Increase the account security even without 2FA setup.</li>
    </ul>

    <h2>2. Current Statement</h2>
    <ul>
        <li>In 2020, a brute force attack led to data loss and approximately $100,000 in damages for around 50 NAS users. Although measures were taken to mitigate the attack, affecting less than 0.1% of users, there's a recognized need to bolster product security.</li>
        <li>The current 2FA setup rate stands at a mere 1%. OTP is the only method offered.</li>
        <li>Some legacy portals support only OTP as the second factor, pending user upgrades.</li>
    </ul>

    <h2>3. Problem Statement</h2>
    <ul>
        <li>The 2FA setup rate is less than 1% among 5 million accounts. Efforts to encourage system upgrades via email have been largely ignored.</li>
        <li>Users who lose access to OTP (e.g., phone loss) must contact technical support for recovery.</li>
        <li>Users lack understanding of the setup and usage of 2FA.</li>
    </ul>

    <h2>Out of Scope</h2>
    <p>Mandating users to set up 2FA.</p>

    <h2>5. Research Methodology</h2>
    <h3>Survey and Inquiry:</h3>
    <p>Collected 500 responses identifying the top three reasons for low MFA setup: perceived cumbersomeness, uncertainty about setup, and fear of being locked out post-setup.</p>

    <h3>User Interviews:</h3>
    <p>Discovered issues with double password entry inconvenience and fears of losing access due to accidental app deletion.</p>

    <h3>Competitive Analysis:</h3>
    <p>Examined Google, Microsoft, and Adobe’s security login methods. Noted each offers more than two 2FA methods, including OTP and phone push notifications.</p>
<!DOCTYPE html>
<html>
<head>
    <title>Comparative Analysis of Security Login Methods</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <h2>Comparative Analysis of Security Login Methods</h2>

    <table>
        <tr>
            <th>Feature</th>
            <th>Google</th>
            <th>Microsoft</th>
            <th>Adobe</th>
        </tr>
        <tr>
            <td>Two-Factor Authentication (2FA)</td>
            <td>Yes</td>
            <td>Yes</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td>Authentication Methods</td>
            <td>OTP, Push Notification, U2F Key</td>
            <td>OTP, Push Notification, Physical Security Key</td>
            <td>OTP, SMS, Email</td>
        </tr>
        <tr>
            <td>Backup Methods</td>
            <td>Backup Codes, Secondary Email</td>
            <td>Secondary Email, Security Questions</td>
            <td>Recovery Email</td>
        </tr>
        <tr>
            <td>User Interface</td>
            <td>User-friendly, Intuitive</td>
            <td>Intuitive, Comprehensive</td>
            <td>Simple, Straightforward</td>
        </tr>
        <tr>
            <td>Recovery Options</td>
            <td>Email, Phone</td>
            <td>Email, Phone, Security Questions</td>
            <td>Email</td>
        </tr>
        <tr>
            <td>Additional Security Features</td>
            <td>Advanced Protection Program</td>
            <td>Microsoft Authenticator App</td>
            <td>Adobe Account Access</td>
        </tr>
    </table>

</body>
</html>

    <h2>6. Proposed Solutions</h2>
    <ul>
        <li><strong>New Login Method</strong>: Introduce an "approve signin" feature.</li>
        <li><strong>Overview Page</strong>: Design an interface to simplify understanding and managing security settings.</li>
        <li><strong>Sign-in Notification</strong>: Implement notifications for login attempts.</li>
        <li><strong>Other Login Options</strong>: Introduce a security key as an alternative login option.</li>
        <li><strong>Legacy Portal</strong>: Update and secure legacy portals with advanced 2FA options.</li>
    </ul>

</body>
</html>

