---
layout: post
title:  "Increase the security level of SaaS service"
date:   2020-05-29 18:05:55 +0300
image:  SA_banner.jpeg
tags:   Security
---
<html>
<head>
    <title>Synology Account Security Enhancement</title>
    <style>
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #333333; /* Dark gray color */
        }
        h2 { 
            font-weight: normal;
        }
        ul { 
            list-style-type: disc; 
            margin-left: 20px; 
        }
        li { 
            margin-bottom: 10px; 
        }
    </style>
</head>
<body>

    <h2>1. Purpose and Overview</h2>
    <ul>
        <li><strong>Overview:</strong> Synology Account, a critical SaaS service with over 5 million users, serves as the gateway to all Synology cloud services, including QuickConnect, Active Insight, and C2. The security of Synology Account is paramount, impacting both users and the company. It also facilitates user engagement in Synology Events and community participation.</li>
        <li><strong>Objective:</strong> To enhance the security of our cloud service, particularly as the integration of products with the Synology Account escalates.</li>
        <li><strong>Approach:</strong>
            <ul>
                <li>Introduce diverse methods for straightforward multi-factor authentication (MFA) setup.</li>
                <li>Foster user engagement in enabling two-factor authentication (2FA) through education on its significance.</li>
                <li>Strengthen account security, independent of 2FA activation.</li>
            </ul>
        </li>
    </ul>

    <h2>2. Current State Analysis</h2>
    <ul>
        <li>In 2020, a brute force attack caused data loss and incurred about $100,000 in damages, affecting around 50 NAS users. Although the impact was limited to less than 0.1% of users, it underscored the need for enhanced product security.</li>
        <li>Currently, the adoption rate of 2FA is only 1%, with OTP as the sole available option.</li>
        <li>Certain legacy portals are restricted to OTP for 2FA, pending upgrades by users.</li>
    </ul>

    <h2>3. Problem Statement</h2>
    <ul>
        <li><strong>Low Adoption Rate of Two-Factor Authentication (2FA):</strong> Currently, only a minimal 1% of users have enabled 2FA, predominantly due to the perceived complexity and inconvenience associated with traditional 2FA methods like One-Time Passwords (OTP).</li>
        <li><strong>User Inaccessibility and Convenience Issues:</strong> Many users face challenges in accessing or managing their 2FA settings, especially in scenarios such as phone loss or OTP inaccessibility. This leads to a reliance on technical support and a general reluctance to engage with existing security measures.</li>
        <li><strong>Limited Variety in Security Options:</strong> The current security framework primarily relies on OTPs, lacking diversity in authentication methods. This limitation fails to address the varying needs and preferences of a diverse user base.</li>
        <li><strong>Need for Enhanced User Awareness and Engagement:</strong> There is a significant gap in user understanding and involvement regarding their account's security settings. Users often do not regularly check or update their security preferences, partly due to the lack of a user-friendly interface.</li>
    </ul>

    <p><strong>Out of Scope</strong></p>
    <ul>
        <li>Mandatory 2FA implementation remains outside our current scope, focusing instead on voluntary adoption supported by user education and enhanced security features.</li>
    </ul>

</body>

<head>
    <title>Synology Account Security Enhancement - Research Methodology</title>
   
</head>
<body>

    <h2>4. Research Methodology</h2>
    
    <h3>Survey and Inquiry:</h3>
    <ul>
        <li>Collected 500 responses identifying the top three reasons for low MFA setup: perceived cumbersomeness, uncertainty about setup, and fear of being locked out post-setup.</li>
    </ul>

    <h3>User Interviews:</h3>
    <ul>
        <li>Discovered issues with double password entry inconvenience and fears of losing access due to accidental app deletion.</li>
    </ul>

    <h3>Competitive Analysis:</h3>
    <ul>
        <li>Examined Google, Microsoft, and Adobe’s security login methods. Noted each offers more than two 2FA methods, including OTP and phone push notifications.</li>
    </ul>

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


<html>
<head>
    <title>Synology Account Security Enhancement - Proposed Solutions</title>
    <style>
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #333333; /* Dark gray color */
        }
        h2 { 
            font-weight: normal;
        }
        table { 
            margin-left: 20px; 
            border-collapse: collapse;
        }
        th, td { 
            padding: 8px; 
            border: 1px solid #ddd;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
            margin: 0;
        }
        li {
            margin-bottom: 5px;
        }
    </style>
</head>
<body>

    <h2>6. Proposed Solution</h2>
    <table>
        <tr>
            <th>Proposed Solution</th>
            <th>Pros</th>
            <th>Cons</th>
        </tr>
        <tr>
            <td>New Login Method: "Approve Signin" Feature</td>
            <td>
                <ul>
                    <li>Enhances security against phishing by diminishing password reliance</li>
                    <li>Convenient for users: simple approval via phone</li>
                    <li>Accessible for those who find traditional 2FA methods cumbersome</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Requires stable internet connectivity</li>
                    <li>Necessitates downloading an additional Synology Secure Signin app</li>
                    <li>Learning curve: relatively new approach in the market</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Overview Page: Simplified Interface for Security Settings</td>
            <td>
                <ul>
                    <li>User-friendly interface improves understanding of security settings</li>
                    <li>Promotes user engagement in security practices</li>
                    <li>Highlights the importance of security to users</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Development demands time and resources</li>
                    <li>Needs regular updates for new features and threats</li>
                    <li>Users less likely to check settings regularly as it requires web service login</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Abnormal Sign-in Notification: Login Attempt Alerts</td>
            <td>
                <ul>
                    <li>Increases awareness of unauthorized access attempts</li>
                    <li>Enables prompt response to potential breaches if they didn't log in</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Risk of notification fatigue in users</li>
                    <li>Potential for false alarms leading to undue concern</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Abnormal Sign-in Compulsory 2FA: Mandatory 2FA for Abnormal IPs</td>
            <td>
                <ul>
                    <li>Enhances security level by enforcing 2FA on suspicious login attempts</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Can be cumbersome for users, especially if falsely identified as abnormal</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Security Key Integration</td>
            <td>
                <ul>
                    <li>Provides a highly secure, physical authentication method</li>
                    <li>Useful for users without smartphone access</li>
                    <li>Adds a new security option for users</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Incurs additional costs for users to acquire keys</li>
                    <li>Not essential for all, potentially confusing as an unfamiliar option</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Legacy Portal: Update with Advanced 2FA Options</td>
            <td>
                <ul>
                    <li>Upgrades outdated systems to current standards</li>
                    <li>Extends protection to more users</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Significant development and testing required</li>
                    <li>Challenges with compatibility in legacy systems</li>
                </ul
</body>
</html>



<html>
<head>
    <title>Synology Account Security Enhancement - MVP Requirements</title>
    <style>
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #333333; /* Dark gray color */
        }
        h2, h3 { 
            font-weight: normal;
        }
        table { 
            margin-left: 20px; 
            border-collapse: collapse;
        }
        th, td { 
            padding: 8px; 
            border: 1px solid #ddd;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <h2>7. Product MVP Requirements</h2>
    <table>
        <tr>
            <th>#</th>
            <th>Component</th>
            <th>Feature</th>
            <th>Priority</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Visual Appearance</td>
            <td>Design of Overview Page to Identify Account Security Level</td>
            <td>P1</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Backend</td>
            <td>Backend Development for "Approve Signin" Service</td>
            <td>P1</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Mobile App Development</td>
            <td>Mobile App for Push Notification (Approve Signin)</td>
            <td>P1</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Visual Appearance</td>
            <td>User Interface for "Approve Signin" Feature Setup</td>
            <td>P1</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Backend</td>
            <td>Update and Secure Legacy Portals with Advanced 2FA</td>
            <td>P1</td>
        </tr>
        <tr>
            <td>6</td>
            <td>Backend/Frontend</td>
            <td>Backup Method Implementation</td>
            <td>P1</td>
        </tr>
        <tr>
            <td>7</td>
            <td>Visual Appearance</td>
            <td>User Interface for Security Key Setup</td>
            <td>P2</td>
        </tr>
        <tr>
            <td>8</td>
            <td>Backend</td>
            <td>Integration of Security Key as a Login Option</td>
            <td>P2</td>
        </tr>
        <tr>
            <td>9</td>
            <td>Backend/Frontend</td>
            <td>Abnormal Activity Notification: Login IP History Tracking and Display</td>
            <td>P2</td>
        </tr>
        <tr>
            <td>10</td>
            <td>Backend</td>
            <td>Integration with App Push Notification Service</td>
            <td>P2</td>
        </tr>
        <tr>
            <td>11</td>
            <td>Backend</td>
            <td>Email Notification System</td>
            <td>P2</td>
        </tr>
        <tr>
            <td>12</td>
            <td>A/B Test</td>
            <td>Testing "Approve Signin" Feature and OTP Setup Complete Rate</td>
            <td>P3</td>
        </tr>
        <tr>
            <td>13</td>
            <td>A/B Test</td>
            <td>Testing User-Friendliness and Incentive of Overview Security Section</td>
            <td>P3</td>
        </tr>
        <tr>
            <td>14</td>
            <td>Internal Controls</td>
            <td>Monitoring and Feedback Tools</td>
            <td>P3</td>
        </tr>
        <tr>
            <td>15</td>
            <td>Backend/Frontend</td>
            <td>Privacy Data Deletion Features</td>
            <td>P3</td>
        </tr>
        <tr>
            <td>16</td>
            <td>Backend</td>
            <td>SMS Notification Integration</td>
            <td>P3</td>
        </tr>
    </table>

    <h3>Priority Definitions:</h3>
    <ul>
        <li><strong>P1 (Required for Launch):</strong> Essential features that are critical for the launch.</li>
        <li><strong>P2 (Expected for Launch):</strong> Important features that are planned for the launch but can be deferred if necessary.</li>
        <li><strong>P3 (Desired for Launch):</strong> Additional features that would enhance the product but are not crucial for the initial launch.</li>
    </ul>

</body>
</html>
