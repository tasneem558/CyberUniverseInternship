# Day 06 - Phishing Email Analysis

## Case Study 1: Fraudulent Order Update (AT&T Mockup)  
**Type:** Malware Delivery & Credential Harvesting  

### Identified Red Flags
1. **Suspicious Link:** When hovering over the button, the URL leads to `margopassadorestylist.com`, which has no relation to AT&T.
2. **Double File Extension:** The file name `confirmation-974702584.pdf.jar` pretends to be a PDF, but it is actually a Java executable file.
3. **Fake-Looking Domain:** The sender uses `wireless.att-mail.com`, which looks similar to an official domain but is not the real corporate address.
4. **No Personalization:** The email does not mention the recipient’s name, which is common in mass phishing emails.
5. **Urgency and Pressure:** Mentioning a monthly charge for an expensive product (iPhone 11) is meant to create panic.
6. **Imitation of Branding:** The layout and logos try to make the message look legitimate.
7. **Unexpected Purchase:** The email talks about an order the user never made, pushing them to click and “check details.”

### Psychological Manipulation
- **Fear:** The victim worries about being charged for something they did not buy.
- **Urgency:** The situation feels immediate and requires quick action.
- **Curiosity:** The user may click just to see what the order is about.

### Why This Email is Suspicious
This email pretends to be from a trusted company but redirects the user to a completely unrelated website. The double extension is a strong indicator of hidden malware. In my opinion, this is one of the clearest technical red flags in the email.

### What Could Happen
If the file is downloaded and executed, it could install malware such as ransomware or a Remote Access Trojan (RAT), allowing attackers to control the system.


## Case Study 2: Financial Scam (Reem Al-Hashimi)  
**Type:** Advanced Fee Fraud (Social Engineering)

### Identified Red Flags
1. **Unverified Identity:** The sender claims to be a government official but uses a public Gmail account.
2. **Language Mistakes:** Multiple grammar errors reduce credibility.
3. **Generic Greeting:** The message starts with “Hello” instead of addressing the recipient by name.
4. **Different Reply Address:** The email asks the recipient to respond to another suspicious address.
5. **Unrealistic Offer:** Promising 30% of €47.7 million is clearly too good to be true.
6. **Long Emotional Story:** The detailed background story is likely meant to build trust.
7. **Suspicious Financial Request:** The message involves transferring large amounts of money through beneficiary accounts.

### Psychological Manipulation
- **Greed:** The promise of easy money can cloud judgment.
- **Authority Bias:** Claiming to be a high-ranking official builds fake credibility.
- **Trust Building:** Referencing major events adds false legitimacy.

### Why This Email is Suspicious
The sender mixes authority, emotional storytelling, and unrealistic financial rewards. These are common traits of advance fee fraud scams designed to manipulate victims into sending money or sharing banking details.

### What Could Happen
If the victim replies, they may be asked to send advance fees or share banking information, leading to direct financial loss or identity theft.


## Possible Impact
- Credential theft
- Malware infection
- Financial loss
- Exposure of personal information

## Prevention Measures
1. Always check the real destination of links before clicking.
2. Verify the sender’s full email address, not just the display name.
3. Avoid downloading suspicious file types such as `.jar` or `.exe`.
4. Enable Multi-Factor Authentication (MFA) for added account security.
