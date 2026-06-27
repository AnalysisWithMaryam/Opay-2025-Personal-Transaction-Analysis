# Opay 2025 Personal Transaction Analysis
# My 2025 Student Money Story 📱💸
 
A student's honest look at her finances - where my allowance goes, who sends me money, and what I'm learning about managing money while in school.
 
---
 
## Table of Contents
- [Project Overview](#project-overview)
- [Tools & Techniques](#tools--techniques)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning Process](#data-cleaning-process)
- [Excel Dashboard](#excel-dashboard)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
---

## Project Overview
 
So I'm a student trying to figure out my money. 🎓 In 2025, I decided to actually look at where my allowance and income go instead of just spending blindly. I pulled all my OPay transactions from January to December and analyzed them.
 
Why? Because I kept wondering:
- Am I broke because I spend too much?
- Where does my parents' money actually go?
- Who am I sending money to and why?
- Can I afford university expenses with this income?
- Am I saving anything? (Spoiler: barely)
### My Account Overview
- **Name:** MARYAM ABEBI ADEWUSI
- **Year Analyzed:** January - December 2025 (my whole 2025!)
- **Total Transactions:** 3,667 times I moved money 😅
- **What This Covers:** Everything from buying airtime to peer transactions
### What I Discovered
✅ Where my student money actually goes  
✅ Who my biggest income sources are  
✅ Whether I'm spending too much  
✅ What my money habits say about me  
✅ How to manage student life finances better  
 
---

## Tools & Techniques
 
### What I Used
- **Microsoft Excel** - Because it's free (student life!) 💰
- **My OPay Bank Statement** - Downloaded straight from the app
- **Pivot Tables & Charts** - Learned these in class, decided to actually use them
- **Google & YouTube** - For figuring out how to do stuff I didn't know
### How I Did It
I exported my transaction history and basically said "okay, let's see what's really happening here." Excel became my detective tool. Every messy transaction got cleaned up, organized, and categorized.
 
**My Process:**
- Exported raw data (it was chaotic!)
- Sorted through 3,922 messy entries
- Removed duplicates and errors
- Grouped transactions into types (school stuff, transport, food, gifts, etc.)
- Made charts to see patterns
- Built a dashboard so I could see everything at a glance
It took longer than I expected, but it was worth it.
 
---
 
## Dataset Overview
 
### What I'm Analyzing
This is literally my whole financial life for 2025. Every naira that came in and went out. From my parents' allowance to money my friends send me to pay them back, to airtime I buy, to everything.
 
### The Data Breakdown
 
| Account | Records | What It Shows |
|---------|---------|--------------|
| **Main Account** | 3,667 | My main spending (where student money goes) |
| **Savings** | 1,617 | Money I tried to save (not much 😅) |
| **Raw Data** | 3,922 | Original messy bank export |
| **Summary** | Key numbers | Quick overview of the year |
 
### What Each Transaction Tells Me
- **Date & Time** - When I spent/received money
- **What I bought** - Airtime? Food? Sent to friends?
- **How much** - In naira
- **Balance left** - How much I had after
- **Channel** - Mobile app or USSD

  ### The Numbers For My Student Life
```
MY MAIN ACCOUNT IN 2025
├─ Started 2025 with: ₦974.50 (basically broke lol)
├─ Money came in: ₦4,419,040.67 (allowance + other sources)
├─ Money went out: ₦4,420,015.17 (spent almost everything)
└─ Ended with: ₦0.00 (broke again 😅)
 
MY SAVINGS ACCOUNT IN 2025
├─ Started with: ₦2.61 (who puts 2 naira in savings?)
├─ Tried to save: ₦1,474,461.80
├─ Earned in interest: ₦2,510.24 (basically nothing)
└─ Ended with: ₦2,512.85 (still basically nothing)
```
 
**Average per month:** ₦368,968 coming in, ₦368,334 going out. Literally living month to month.
 
---
 
## Data Cleaning Process
 
Okay so this was actually painful. The raw data was a mess - like getting a test back and it has red marks everywhere. But I had to fix it to make sense of my money.
 
### Step 1: Understanding the Chaos 😅
Downloaded my statement and it had headers everywhere, dates in weird formats, symbols mixed with numbers. Basically unreadable. Had to figure out where the actual transaction data started.
 
### Step 2: Fixing the Dates and Numbers 📅
Dates looked like "01 Jan 2025" and amounts had naira symbols (₦) all over them. Excel didn't recognize them as real data. I had to:
- Remove the ₦ symbols
- Make sure Excel understood these were dates and numbers
- Clean up inconsistent formatting
### Step 3: Understanding Income vs Expenses 💸
Every transaction was either me receiving money OR sending money, not both. Some cells looked empty when they just meant "nothing in this direction." I kept it that way so I could tell money coming in from money going out.
 
### Step 4: Finding Duplicates 🔍
Found **255 duplicate transactions**! Probably happened when I had internet issues or the app glitched. Carefully removed them without deleting real transactions.
 
### Step 5: Double-Checking the Math ✓
Made sure that:
- Each balance = previous balance + money in - money out
- All my debits added up correctly
- All my credits added up correctly
- Everything matched the OPay statement
Took forever but worth it - everything checked out!
 
### Step 6: Organizing into Categories 🏷️
Read through thousands of descriptions and put them into groups:
- **Airtime** - When I buy credit
- **Data** - Internet bundles
- **Transfers** - Money to/from friends and family
- **School stuff** - Anything school-related (if applicable)
- **Food & Transport** - Getting around and eating
- **Gifts** - Sending money as gifts
- **Other** - Stuff that doesn't fit
### Final Stats 📊
 
| What | Result |
|------|--------|
| Started with | 3,922 messy entries |
| Ended with | 3,667 clean transactions |
| Removed | 255 duplicates |
| Data accuracy | 100% ✓ |
| Time spent | Way longer than expected 😅 |
 
Honestly? This step taught me that the OPay statement is pretty reliable. No major errors once I cleaned it up.
 
---
## Excel Dashboard
<img width="992" height="391" alt="dashboard 2" src="https://github.com/user-attachments/assets/c7d594f6-4110-49db-879a-15466f23eded" />

### 1. **The Big Picture** 🎯
At the top - the numbers that matter:
- **3,667 transactions** - That's like 10 per day. I move money A LOT.
- **₦4.43M spent** - Total money that left my account
- **₦4.42M received** - Total allowance/money people sent me
- **Started with** ₦8,578.30
#### 2. **Month by Month** 📈
A chart showing what I spent vs what I received every month. Some months are way higher than others - February I spent SO much. June was my best month.
 
#### 3. **Top 5 People Sending Me Money** 💎
Shows who actually pays/supports me:
 
| Who | How Much | How Many Times |
|-----|----------|---|
| Lateef | ₦1,474,461.80 | 1,104 times! |
| Abireyor Venture | ₦867,000 | 11 times |
| WAKILI DAUDA | ₦850,000 | 28 times |
| Family/Friends | ₦1.7M | Regular transfers |
 
Real talk: One person sends me 33% of my money. That's either my parents or someone very important to my finances.
 
#### 4. **Where My Money Goes** 💸
Breaking down my spending:
- **Big transfers** - 95.5% (sending money to other accounts, people, etc.)
- **Airtime** - 1.6% (keeping my phone working)
- **Mobile data** - 2.8% (staying online)
- **Fees** - 0.1% (annoying bank charges)
#### 5. **Charts & Trends**
Visual stuff showing:
- Monthly spending patterns
- Income sources
- Spending by category
- Days I spend the most  
---
## Key Insights
 
Looking at my data, some things honestly shocked me. Here's what I found out about my student money habits:
 
### 1. **I'm Living Exactly at My Means** ⚖️
Money in = ₦4,419,040.67  
Money out = ₦4,420,015.17  
Difference = ₦8,578 (basically ZERO)
 
I'm balanced, but not in a good way. I'm not saving. I'm spending every naira I get. This is fine while I'm in school and can ask for more, but it's a terrible habit to have.
 
### 2. **I Depend On One Person Way Too Much** 🚨
One person (Lateef? Parent? Sponsor?) sends me 33% of my income - ₦1.4M out of ₦4.4M. 
 
If that stops, I'm broke. This is risky. Even as a student.
 
### 3. **I Don't Actually Know Where 95% of My Money Goes** 🤔
95.5% of my spending shows up as "transfers." That's a huge red flag. Do I:
- Send money to my parents to manage?
- Pay for bigger expenses through transfers?
- Use a joint account with family?
- Send money to friends and they buy things for me?
I literally can't tell. This is a problem.
 
### 4. **Some Months I Spend WAY More** 📊
- February: ₦466,374 (ouch!)
- April: ₦304,953 (expensive month)
- June: ₦152,893 (my best month!)
Why the massive swings? School fees in Feb? Exams period requiring more stuff in April? No idea. I should figure this out.
 
### 5. **I Move Money Around Like It's My Job** 🔄
3,667 transactions in 355 days = 10.3 transactions EVERY DAY.
 
That's a lot! Am I:
- Splitting bills with friends?
- Helping family members?
- Moving money between accounts?
- Just impulsive?
Probably a mix of everything.
 
### 6. **My Communication Costs Are Actually Reasonable** 📱
I spent ₦193,409 for the whole year on airtime and data. That's only ₦16,116/month or about ₦535/day.
 
For a student who needs to stay online? That's pretty good. Not wasting money here.
 
### 7. **I Use My Phone App More Than USSD** 📲
Most transactions are through the mobile app, not USSD codes. Shows I'm tech-savvy and probably prefer the easier way.
 
### 8. **My Savings Account Is Basically Fake** 😅
I moved ₦1.4M to savings but only earned ₦2,510 in interest (0.17% return). It's basically a savings graveyard. The money just sits there doing nothing.
 
As a student, I probably can't afford better rates, but still... that's rough.
 
### 9. **Weekends = More Money Movement** 🎉
Friday and weekends have more transactions. Makes sense - that's when I'd hang out, buy things, send money to friends for stuff.
 
### 10. **I'm Living Paycheck to Paycheck (But I'm a Student, So...)** 💭
My ending balance: ₦0.00
 
I spend everything I get. This would be scary if I wasn't a student. But honestly? That's kind of normal student life. You get allowance, you spend allowance, you wait for next allowance.
 
**HOWEVER** - this is a terrible habit to start building now. The fact that I have ₦0 buffer means:
- One emergency = asking for more money from parents
- Can't handle unexpected costs
- No safety net
Even students should try to have SOME emergency money.
 
--- 
## Conclusion
This analysis just helped me see what's actually happening with my money instead of wondering where it all goes.
