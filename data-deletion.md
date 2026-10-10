# User Data Deletion

**Effective date: 10 October 2026**

The Hunt K Hash Cinematics app stores only the sign-in tokens issued by Meta and Google. It
does not keep copies of your posts, comments, insights or analytics. You can remove everything
it holds in any of the following ways.

## Option 1: Remove the app from your account

This cancels the app's access immediately and makes any stored token useless.

**Facebook and Instagram**

1. Open Facebook and go to **Settings & privacy → Settings**.
2. Open **Apps and Websites**.
3. Find **Hunt K Hash Cinematics** and select **Remove**.

**Google and YouTube**

1. Go to <https://myaccount.google.com/permissions>.
2. Select **Hunt K Hash Cinematics**.
3. Select **Remove access** (or **Delete all connections**).

## Option 2: Delete the stored tokens

If you run the app yourself, delete these files on the machine that runs it:

- `~/.mcp-plugins/instagram-token.json`
- `~/.mcp-plugins/youtube-token.json`
- the SQLite file set in `MCP_STORE_PATH`, if you use remote mode

## Option 3: Ask us to delete your data

If you used a copy of the app hosted by Hunt K Hash Cinematics, open an issue at
<https://github.com/Hash-Cine/Hunt-k-Hash-cinematics-privacy-policy-tc-license/issues>
with the title "Data deletion request". Do not post tokens or passwords in the issue; we will
only need the Instagram username or YouTube channel concerned.

We will delete the stored tokens for that account within 30 days and confirm in the issue.

## What happens after deletion

The app can no longer read or change your account. Content you published through the app
stays on Instagram or YouTube until you delete it there. Files you uploaded to a storage
service (Cloudinary or Amazon S3) stay in that service until you delete them there.
