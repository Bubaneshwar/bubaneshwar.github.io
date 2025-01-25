---
layout: post
title: How to scrape apollo.io in under 5 minutes
url: scrape-apollo
---
# Cold Emails: Cheap and Effective When Done Right  

The main cost lies in sourcing quality B2B data, which can easily exceed thousands of dollars.  

If you examine **Apollo's pricing**:
- $49 for a thousand emails  
- $149 for four thousand emails  

This pricing isn't outrageous, but we can achieve much better results.  

---

## Scrape Hundreds of Thousands of B2B Emails from Apollo for $90  

**P.S.: There's a free trial worth ~130,000 emails. 😄**  

---

## Why Scrape Apollo for Data?  

![Apollo Free Plan Screenshot Highlighting Unlimited Email Credits](#)

**Apollo** is a leading B2B data vendor, offering a free plan that allows you to “view” unlimited emails.  

However, **emails can't be exported** unless you purchase a subscription.  

Enter: **Data Scraping**.  

---

## Requirements  

- An account on Apollo created with a **work email**  
  - If you don’t have a work email, create one on **Zoho** (free).  
  - Purchase a domain on platforms like **Namecheap** or **Porkbun**.  
  - The more work emails you have, the more data you can scrape.  
  - [Guide to creating a business email with Zoho](#)  
- An Apify account, which can be created with a personal email.  
  - We’ll use **Apify** to host the Apollo scraper.  

---

## Steps  

### Step 1: Create an Apollo.io Account  

1. Go to [apollo.io](https://apollo.io) and create an account using your business email.  
2. Select the **free plan** and confirm your email to complete the signup.  

![Apollo.io Signup Page Screenshot](#)

---

### Step 2: Search for Leads  

1. After signing in, navigate to the **person search** option on the sidebar.  
2. Click the **Net New** tab (to avoid errors with the free plan).  

![Apollo.io Person Search Dashboard](#)

3. Use Apollo’s targeting options to find your ideal prospects.  
   - Recommended Filters:  
     - **"Likely to Engage"** under "Email Status"  
     - **"Verified"** under "Email Status"  

   These filters ensure high-quality emails, minimizing invalid or risky ones that could harm your outreach campaign's deliverability.  

![Apollo.io Likely to Engage and Verified Fields Screenshot](#)

4. After finalizing the targeting options, **copy the page URL.**  
   - Each targeting modification updates the page URL.  

Now, you're ready to feed this URL into the scraper on Apify.  

---

### Step 3: Sign Up on Apify and Find the Scraper  

1. Go to [apify.com](https://apify.com) and sign up for a free account.  
2. In the **search bar**, type "Apollo."  

![Apify Dashboard Showing Apollo.io Scraper](#)

3. Select the **first scraper** that appears (important: avoid the "Pay per lead" scraper as it requires an Apify subscription).  
4. Use the scraper that costs $45/month (trial available).  

---

### Step 4: Fill in the Required Fields  

1. On the Apollo scraper page, enter the required fields:  
   - Export browser cookies or manually input your Apollo login details.  

   - For cookies:  
     1. Use a **cookie export extension** in your browser.  
     2. Log in to Apollo.  
     3. Export/copy the cookies and paste them into the cookies field on Apify.

2. Configure the scraper settings:  
   - **Get emails:** ON  
   - **Include guessed emails:** OFF  
   - **Wait for email verification:** ON  

![Apollo Scraper Required Fields on Apify](#)

3. For optional fields:  
   - **List name:** Enter a unique name to separate scraped data for each search.  
   - **Total number of records required:** Specify or leave blank to scrape all available leads.

4. Configure run options:  
   - Set **Memory** to 512 MB.  
   - Turn **No timeout** OFF.  

![Run Options in Apollo Scraper on Apify](#)

---

### Step 5: Start Scraping  

- Click **Save & Start** to begin the scraping process.  
- You'll be redirected to a live screen that tracks progress.  

Scraping 500-1000 emails typically takes only a few minutes.  

![Live Scraping Process on Apify](#)

---

### Step 6: Export Your Data  

Once scraping is complete:  
1. A **success message** will appear.  
2. Click **Export** to save your data.  

![Export Dataset on Apify Screenshot](#)

Export data in the desired format and select which data points to include or exclude.  

---

## Enjoy Your Free Data! 😉
