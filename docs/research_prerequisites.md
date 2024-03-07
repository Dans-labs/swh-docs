Prerequisites
=============

Before you can start using the deposit form, you must successfully complete the three steps described below.
Otherwise the deposit form will not submit your data!

**It is important to go through these steps before your deposit!**   
For now, there are several actions to complete, however, most of them you only have to perform once before you start depositing for the first time.   
Next time you only have to log in to the deposit input form to be able to deposit again.

### Step 1: Dataverse account
The deposit form will deposit the sourcecode related (meta)data to the connected Dataverse instance on your behalf.  
To be able to so, you need to supply your [Dataverse API-token](https://guides.dataverse.org/en/latest/api/auth.html){target="_blank"} to the deposit form. Therefore you must have a Dataverse account on the connected (DANS) [Dataverse demo]{target="_blank"} instance. If you already have a Dataverse account on the connecting instance, you can skip this step.   
**To register and get your account do the following:**

1. Goto the [Dataverse demo]{target="_blank"} instance.
2. Goto 'Sign Up' in the right top menu bar.
3. Enter your account information

[//]: # (4. Goto the "Account Information" tab. This tab can also be reached from the 'user account' top right menu bar, 3rd entry: "Account Information".)

[//]: # (5. Click the "Send Verification Email" button.)

[//]: # (6. Check your email and confirm the given 'verify link'.)

Done. This was a one-time operation.  
P.s: At the Demo Dataverse you are not required to verify your email. This may be changed at any time.

!!! note

    Currently the Deposit form is connected to a 'vanilla' Dataverse instance, on which you need to create a classic "Dataverse account" with your own choosen username and password.
    In the near future, the deposit form will likely be connected to instances where you can also log in with your 'Institutional Account’ (Authentication and Authorisation Infrastructure).

### Step 2: Depost-form account
At the time of writing, the Deposit form offers two login methods:

1. Federated login via your Google account.
2. Local account with your email as username.

If you do not have a Google account, or do not want to use it, you can create a local account:

1. Goto the [DANS Deposit]{target="_blank"} input form
2. Click on the 'LOG IN' button; you will be redirected to the 'Sign in to your account' login form
3. Choose either to 'Sign in' or 'Register' as a (new) user, or choose to 'Sign in with Google'

You are now logged in to the DANS Deposit entry form. You only have to take one more step to deposit data!

### Step 3: Register your Dataverse API-key

From the opening screen of the [DANS Deposit]{target="_blank"} input form, click on the 'DEPOSIT DATA' button.
You arrive at the actual input form.   
At the top of that screen you will see a yellow box, containing a warning text:

!!! warning "Missing or invalid API keys"
    
    You need to enter your personal API keys to be able to submit this form. Check your settings.

Now complete the following steps:

1. Click on 'Check your settings'.
2. In the next screen, click on 'Get you key here'.
3. You will be redirected to the connected Dataverse instance in a new window. Log in with your Dataverse account, that you created in Step 1.
4. Goto your account settings. This can be reached from the 'user account' top right menu bar, displaying your account name.
5. Select the 4th entry: 'API Token'.
6. Click on 'Create Token'. A code consisting of numbers, letters and hyphens will appear (e.g. 'e27338d4-9586-4216-848f-daff9cfcf4c9'). This is your 'API key'.   
7. Click on the 'Copy to Clipboard' button. You have now copied your API key.
8. Return to the window with the Deposit form input panel.
9. In the input field that says 'Your personal Dataverse API key', paste the API key you just copied. If all goes well, a green check mark will appear behind the API key.
10. Click on the 'DEPOSIT YOUR DATA' button.

If you get a warning that your API key is invalid, check in the Dataverse instance that your account has been successfully verified, see step 1.

Once you have completed all of the above steps, you are good to go for depositing your files and source code, which is described in the [next step](research_manual.md).

[Dataverse demo]: {{hyperlink.ext.dataverse}}
[DANS Deposit]: {{ hyperlink.ext.deposit }}
[Software Heritage]: {{hyperlink.ext.swh}}