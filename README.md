# Project Milestone 1 - Week 5 Assignment

## Deploy Link

https://www.haikalbintang.site/

https://haikal-bintang.netlify.app/

## How to clone repo until running your computer

### Make a New Empty Folder

To create a new empty folder you can use a command, or with file explorer.

Command for Windows:

```
mkdir folder_name
```

### Open folder with VS Code

You can right-click on the "new empty folder" and choose Open with Code

### Change Directory to the "new empty folder"

Command for Windows:

```
cd "new empty folder"
```

### Download Repositories

Download the repository onto your computer using the `git clone` command. The repository url can be seen in the desired repository.

```
git clone "<url repository>"
```

### Update Repositories

Update the repository that has been downloaded to the computer using the `git pull` command.

```
git pull origin <branch name>
```

### Uploading Changes

Before pushing, don't forget to pull first.

Add new file or change file

```
git add <file name>
```

Or you add new file or modify multiple files at once

```
git add .
```

Confirm file additions or changes

```
git commit -m "<commit messages>"
```

Submit changes to the repository

```
git push origin <branch name>
```

<br>
<br>

# Deploy Documention

### Buy Domain

**Step 1 :** First you have to buy a domain at [Niagahoster](https://www.niagahoster.co.id/)

![Alt text](assets/Screenshot%20(285).png)

**Step 2 :** On the domain name, it's up to you to put the domain name according to your own needs.

![niaga_domain](assets/Screenshot%20(286).png)

**Step 3 :** After choosing a domain name is done, make a payment.

![niaga_dashboard](assets/Screenshot%20(287).png)

Now your domain arleady done.

### Deploy Your Website in Netfliy

**Step 1 :** Open **[Netlify](https://app.netlify.com/)** and Login.

![netlify_homepage](assets/Screenshot%20(291).png)

**Step 2 :** Go to tab **"Team Overiew"**

**Step 3 :** Click **"Add new Site"**

![netlify_dashboard](assets/Screenshot%20(291).png)

**Step 4 :** Click **"Import an existing project"**

![netlify_save](assets/Screenshot%20(316).png)

**Step 5 :** Select your repository from Github

![netlify_repo](assets/Screenshot%20(293).png)

**Step 6 :** Pick an Owner

**Step 7 :** Pick branch main

**Step 8 :** Click **Deploy Site**

![netlify_deploy](assets/Screenshot%20(294).png)

**Step 9 :** After you deploy, you will get the site name

**Step 10:** Click **Domain Settings**

![netlify_domain_setting](assets/Screenshot%20(295).png)

**Step 11:** Choose the site name and Edit the site name

**Step 12:** Fill the site name and Click **Save**

![netlify_changesite](assets/Screenshot%20(297).png)

### Custom DNS

After you have done **Buy Domain & Set Up Netlify**, now we set up the Custom DNS.

**Step 1:** Login or create a new ID at [Cloudfare](https://www.cloudflare.com/).

**Step 2:** Enter the Domain that you bought in **Niagahoster**

![cloud_domain](assets/Screenshot%20(301).png)

**Step 3 :** Go To DNS Tab - Click "Add Record"

![dnsrecord_setup](assets/Screenshot%20(305).png)

**Step 4 :** Choose the type to **"CNAME"**

**Step 5 :** Name **www**

**Step 6 :** Copy and Paste your **Netlify** Subdomain to Target & Click **Save**

![dnsrecord_newrecord](assets/Screenshot%20(305).png)

**Step 7:** Go To **"Domain Settings"** on **Netlify**.

![net_domainset](assets/Screenshot%20(306).png)

**Step 8:** Click **Add a domain**.

![net_adddomain](assets/Screenshot%20(307).png)

**Step 9::** Enter your Custom Domain Name that you bought at **Niagahoster** and Click **Verify**.

![net_setupdomain](assets/Screenshot%20(308).png)

**Step 10 :** Done, your domain is now the main domain.

![primary_domain](assets/Screenshot%20(308).png)

### Change Your Nameservers

Don't forget change your Nameserver value

**Step 1 :** Go To **Niagahoster** and Click **Kelola Layanan**.

![niaga_dashboard](assets/Screenshot%20(309).png)

**Step 2 :** Go to tab Overview Domain and Click **Change Nameserver**.

![niaga_change](assets/Screenshot%20(311).png)

**Step 3 :** Go to **Cloudfare** DNS Tab and see Cloudfare Nameserver and copy server values.

![cloud_value](assets/Screenshot%20(312).png)

**Step 4 :** The value copied on **Cloudflare**, paste the value in Update Nameserver on **Niagahoster** and Click **Save**.

![niaga_update](assets/Screenshot%20(312).png)

Done Now Your Value Nameserver arleady change.

![niaga_value](assets/Screenshot%20(315).png)

### Website Launch

After we have done all the steps above, we wait for the nameserver status to be **active** on **Cloudflare**.

![cloud_active](assets/Screenshot%20(315).png)

or you can get notification in email, if server arleady **active**.

Now you can run your website.

I hope the steps above can help you.

Thank You.
