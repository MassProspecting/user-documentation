# GMail

## 1. Enable 2-Step Verification on Your Google Account

1. **Open your Google Account settings**  
   Go to <https://myaccount.google.com> and sign in with your Gmail credentials.

2. **Navigate to Security**  
   In the left-hand menu, click **Security**.

3. **Turn on 2-Step Verification**  
   Under **“How you sign in to Google”**, select **2-Step Verification**, then click **Get started** and re-enter your password.

4. **Choose and configure your second step**  
   - **Google prompts** (push notification to your phone)  
   - **Authenticator app** (TOTP codes via Google Authenticator or similar)  
   - **SMS text message or voice call**  
   
   Follow the on-screen prompts to complete setup.

5. **Verify and finish**  
   Enter the code or approve the prompt when requested. Once verified, click **Turn on** to enable 2FA.

---

## 2. Create an App Password

## 2. Create an App Password

> **Note:** App passwords are available only if you have turned on 2-Step Verification and are not using a completely passwordless (passkey-only) sign-in.  

1. **Go into your 2-Step Verification settings**  
   - On the Security page, click the **2-Step Verification** card (it may say “On since …”).  
   - Re-enter your password if prompted.

2. **Find the App passwords link**  
   - Once inside the 2-Step Verification panel, scroll down to the **“App passwords”** section.  
   - Click **App passwords**.  

3. **Generate a new App Password**  
   - **Select app**: choose **Mail**  
   - **Select device**: choose your application or **Other (Custom name)** (e.g. “Cold-email Tool”)  
   - Click **Generate**, then copy the 16-character password.

4. **Use this password in your tool**  
   In your third-party email tool’s SMTP settings, enter:
   ```text
   Username:   your-full-gmail@address.com
   Password:   <the 16-character App Password>

---

## 3. Configure SMTP Relay in Google Workspace

> **Prerequisite:** You must have a Google Workspace (formerly G Suite) account with administrator privileges and a verified domain.

1. **Sign in to the Admin console**  
   Go to <https://admin.google.com> and log in with a super-administrator account.

2. **Locate the SMTP relay service**  
   Navigate to **Apps → Google Workspace → Gmail → Routing**. Scroll to **SMTP relay service** and click **Configure** (or **Add another rule**).

3. **Define your relay setting**  
   - **Name**: e.g. “Cold-Email Relay”  
   - **Allowed senders**: choose **Only addresses in my domains** (or **Only registered app users**)  
   - **Authentication**: check **Only accept mail from the specified IP addresses**, then **Add** each IP address used by your third-party tool  
   - **Require TLS encryption**: check this to enforce secure connections  
   - Click **Save**

4. **Take note of relay details**  
