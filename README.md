# Aussie Stock Options - in plain English

## Introduction

### What this document isn't - a la DISCLAIMER

I am not an accountant.  The people that have contributed to this document are probably not accountants.  This document is not tax advice.  This document does not take into account your individual circumstances.  If you read this document, you agree that you will not hold me liable for any damages incurred by any actions you took as a result of reading this document.

This document is provided on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied, including, without limitation, any warranties or conditions of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE. You are solely responsible for determining the appropriateness of using or redistributing this document and assume any risks associated with reading it or taking any advice from it.

### What this document is

When I received stock options from a company, I found it incredibly hard to understand what my tax obligations were.  The ATO website describes the tax rules for shares and stock options in incredibly generic accounting terms.  In particular, there was very little overlap used between the terms written in my employee share scheme document provided by my company, and the terms on the ATO website.  This document is an attempt by me to express my interpretation in plain English of the Australian tax laws as they apply to employee shared schemes offered by typical tech startups.  It is intended to be a collaborative work, hosted on GitHub, and contributions can be made either by raising issues, or by submitting pull requests.

It is also an attempt for me to validate my interpretation of the tax laws against the common understanding of whoever reads this document.  In that vein, there are most likely errors (possibly some big) that I have made, so if you think I am wrong in anything, please raise an issue or submit a pull request.

### Who this document is intended for

First and foremost, this document is intended for myself (James Roper) to clarify my understanding of Australian tax laws with respect to the employee share schemes that I am a part of.

Secondly, this document is intended for people who are in a similar situation to me.  That is, they are an Australian resident who must pay tax in Australia, they work for a startup, and they have received shares or stock options from their company.  It is intended to familiarise them with some of the rules, terminology and complexity of Australian tax law with regards to stock options.  It is not tax advice.  See your accountant.

Thirdly, this document is intended for the tax office.  The very existence of this document is an indication that the ATO websites explanation of Australian tax law for share schemes is lacking when it comes to applying it to share schemes that are commonly given to employees of tech startups.  The wording used in this document may be useful as a start to improving the content on the ATO website in such a way that participants in tech startup employee share schemes will be able to easily relate to.

## The typical tech startup employee share scheme

Of course, every employee share scheme is different.  However, the employee share schemes offered by tech start ups are usually very similar from a tax perspective.  This is particularly true if your employee share scheme is for a Silicon Valley based startup, in Silicon Valley employee share schemes are so common and so cheap to set up that usually there's just a template that the company fills out, and that's all it needs.  For Australian companies, things are (apparently) a lot harder and a lot more expensive, but nevertheless the intent is the same.

So a typical employee share scheme might look like this:

* You are granted a number of options at a strike price.
* You may have had to pay a very small (much smaller than the strike price) initial price to purchase the options, or they may have been given to you for free.
* The options vest over a period of time, usually 4 years.  25% vest after the first year, and then incrementally either every month or every quarter after that a small amount vests until they have all vested.
* You may exercise any vested portion of shares at any time.  To exercise means to buy shares at the strike price.
* If you leave the company before the 4 years is up, you forfeit any unvested shares.  The vested portion you may exercise within a certain time period, for example, 90 days, otherwise you forfeit them as well.
* At some point in future, maybe after 7 years, the options will expire and you will lose them if you haven't exercised them by that date.

There are some other aspects of a typical employee share scheme offered in tech startups that may not be so interesting to you, but are important in certain areas of the tax law, if any of these points don't hold true, then parts of this document may not apply to you:

* The options/shares are ordinary shares.  This begs the question, what is an extraordinary share?  The most common non ordinary share in tech startups is preferential shares.  Preferential shares mean when the company is sold, preferential share holders get the first piece of the pie, usually to the value of what they invested.  It's an insurance policy, if the company goes bad, they at least get what they put in back before anyone else makes money.  These types of shares are usually given to venture capitalists when they invest in the startup.  They are never given to employees.  There are a few other types of shares, but in a typical employee share scheme in tech startups, the shares are ordinary.
* Your options/shares are not for more than 5% of the company or more than 5% of the voting rights.  Unless you are a founder of your company, your options are likely to only give you a fraction of a percent of the company.
* The share scheme is granted to at least 75% of the Australian resident employees of the company.  This will be the case in a typical tech startup.

A final note, the Australian tax laws changed in 2009.  This document is only talking about shares received after the laws changed.

## Some terminology

### Discount

When it comes to taxing stock options, one of the most important terms that you will encounter is the *discount*.  The discount is the difference between the strike price, and the value of the share.  It's effectively the discount you receive when you purchase the shares, that you wouldn't have otherwise got if you didn't have the stock option that lets you purchase it at that lower strike price.

### Fair Market Value

Another important term is the *fair market value*.  Since the company you're working for is a startup, the value of the share is not as straight forward as just looking at the price on the stock market, since your company is not yet listed on the stock market.  The shares however do a have a value, and during this stage of not being listed, this value is the fair market value.

In a typical share scheme, you can ask your company what the fair market value of the share was at any time (or get a table of all the prices of the share over time), and they will give it to you.

### Capital gains tax

In Australia, there is this weird rule about a *capital gains discount*.  This rule is incredibly relevant to employee share schemes, so we must explain it here.

When you receive income from an employer, that income counts towards your total taxable income, and then you pay tax on that, like normal.  When you make a profit from selling an asset (eg an investment property or shares), this is called a capital gain, and that gain counts towards your total taxable income, and then you pay tax on that, like normal.  Except, if you owned the asset for more than a year (you will often hear accountants say "a year and a day"), then you can divide the capital gain by two before adding it to your total taxable income.  Thus you end up paying at least half as much tax on the capital gain.  This is known as a *capital gains tax discount*.

This has important consequences to stock options, because is the money you make off stock options regular income, or is it a captial gain?  If the latter, you can pay significantly less tax.  The answer to this question is where a lot of the complexity in stock options arises.

## Paying tax

### Foreign share schemes

First of all, it's important to know that if your share scheme is for a foreign company, the rules are no different than for if they are for an Australian company.  If you are an Australian resident for tax purposes, you have all the same tax obligations regardless of what country the company you hold shares or stock options is in.  You may wonder how the ATO would ever know that you have shares or stock options in a foreign company, and the answer is they won't unless you tell them.  That said, if your company goes well, and then suddenly a million dollars lands in your Australian bank account, you can bet you'll have some tax auditors knocking on your door asking where that money came from.

### When you have to pay tax

Let's start with the default position.  You must pay tax when you are granted stock options.  Because that stock option represents a discount on shares, the stock option itself has a value (equal to the discount), and is therefore income that you have received.  So, you must include this income as regular income (not a capital gain) in your tax return, under the section for employee share schemes.

However, what if you leave the company early?  Since your options have not vested yet you forfeit the options, which means you paid tax on something you never actually received.  For this reason, the tax office defines this rule of *real risk of forfeiture*.  Since your options haven't vested, and since leaving the company will result in you forfeiting your options, there is a real risk of forfeiture.

Stock options for which there is a real risk of forfeiture (there are also a number of other conditions which we won't go into here) are counted as tax deferred options, meaning that you must (this is something I'm not clear on, whether this is a must or whether you have a choice) defer declaring them until certain conditions are true.  One condition is that you cease employment.  Since you lose your unvested options when you cease employment anyway, this condition isn't relevant.  Another condition is if the shares no longer have a real risk of forfeiture.  This happens when they vest.

So, for a typical tech startup employee share scheme, you have to pay tax on the options you receive when they vest.

### How much tax to pay

The question actually isn't how much tax you pay, but how much income you declare.  When your stock options vest, you take the fair market value at the time that the option vested, subtract the strike price, and now you have the discount.  If you paid an initial price to purchase the option, you subtract this from the discount, since this was part of the cost of obtaining the discount and so offsets the discount, otherwise, take the discount as is.  Then multiply that by the amount of options that vested at that time.  Now you have the amount of income you have to declare.

If there were multiple times that options vested through the year (there probably were, since they vest monthly or quarterly), then you need to do this calculation for each month/quarter that the options vested, using the fair market value at that particular month or quarter.

Note that this discount is regular income.  It is not eligable for a capital gains tax discount.

### Further ~~tax~~ income

Of course, the tax you pay when the option has vested is not the only time you will pay tax on the shares.  At some point in future, you may exercise your options, and at that point, or some later point, you may sell the shares.  When this happens, you will need to pay tax on the gain from the fair market value at the time it vested, this is a capital gain.  Note the cost base for the gain here is not the strike price, but the fair market value when the option vested.  You have already paid tax on the gain from the strike price to the fair market value when it vested, you do not need to pay tax twice on that gain.

If you held the share for more than a year, that is, if the time period between when you exercised the option and then sold the share is more than a year (is this true, or is it from when the option vested???), then you will be eligible for the 50% capital gains discount, and so you only have to count half of the capital gain towards your taxable income.  Otherwise you have to count the full capital gain towards your taxable income.

You can see here that timing matters.  You can save a lot of money in tax if you exercise your options a year before you intend to sell them.  For this reason, you may decide to exercise your options early, before you have any opportunity to sell them.  You may decide to exercise your options as soon as they vest, just in case a liquidity event comes that allows you to sell your shares/vested options, so that you can claim the discount.  Obviously though we're now moving into the standard risks of trading shares, if you exercise your shares early, and the company goes broke, then you'll lose money.

### When things happen together

Sometimes the vested date, exercise date and the date you sell them are all the same.  This might be the case if the company is already listed and you sell the shares as they vest, or maybe the company was acquired and there was a condition in your share scheme that caused all your options to vest at once in that event so you can sell them.  In this case, the market value when your options vest is the price you sell them for, so the whole gain from your strike price to the sale price (minus the initial purchase price of the options if there was one) is considered regular income - there is no capital gain, and so no capital gains tax discount.

### When things go sour

If some of your options have vested, and you paid tax on them, but then the company goes broke, or if for some reason you decide not to exercise your options and you forfeit them, then you have made a loss on those options.  The discount that you once declared as income, you can now declare as a capital loss.  Note that what you declare here is the full discount.  If there was a initial purchase price for the options, do not subtract this from the discount when you claim the discount as a capital loss.

## Examples

### Alice

Alice received 1600 options in 1 January 2011 at a strike price of $0.10.  25% of the options vested in the first year, and then every quarter after that 1/16 of the remaining options vest.  On November 1 2014, the company lists on the stock market.  On January 1 2015, she exercises all her options, and then on January 2 2016, she sells them for $2.00 a share.

Alice's company had the following fair market values in the lead up to the IPO:

* January 1 2012: $0.20
* June 3 2012: $0.25
* March 14 2013: $0.40
* November 25 2013: $0.55
* April 12 2014: $0.70

On 1 January 2015, the share price was $1.50.

Alice has declare the following income:

```
* In 2011 - Nothing, no options have vested.
* In 2012 - 500 options vested at $0.20 = $0.10 discount
          = $50
* In 2013 - 300 options vested at $0.25 = $0.15 discount
          - 100 options vested at $0.40 = $0.30 discount
          = $75
* In 2014 - 200 options vested at $0.40 = $0.30 discount
          - 200 options vested at $0.55 = $0.45 discount
          = $150
* In 2015 - 200 options vested at $0.70 = $0.60 discount
          - 100 options vested at $1.50 = $1.40 discount
          = $260
* In 2016 - All shares sold for $2.00, cost base was the FMV at vesting:
          - 500 options at $0.20 = $900.00 gain
          - 300 options at $0.25 = $525.00 gain
          - 300 options at $0.40 = $480.00 gain
          - 200 options at $0.55 = $290.00 gain
          - 200 options at $0.70 = $260.00 gain
          - 100 options at $1.50 = $50.00 gain
          - Total gain: $2505
          - Less CGT discount: $1252.50
          = $1252.50 taxable income
```

It's important to note here that the gains mentioned above are not the same as the cash in hand that Alice received - Alice paid $160 to exercise her options, and sold them at $3200, meaning she made $3040.  If you add the pre CGT discount gains from each year that she declared, they will total $3040.  So she has declared all the money she made, what makes it complex is that only part of that money made was declared in the year she made it, other parts were declared in prior years as the options vested.

## Other types of shares schemes

### Ordinary share grants

If you are given ordinary shares, say, as a bonus, and these shares have no vesting period and no cost to you, then you have to pay tax on those shares, even if they are restricted in some way (ie, even if you can't sell them now).  The fair market value multiplied by the number of shares given to you is declared as regular income, not as a captial gain.  When you sell those shares, you subtract the fair market value at the time they were given to you, and that number is considered the capital gain.  That amount is then added to your taxable income, applying the capital gains discount if the shares were held for more than a year.

## My specific complaints about the ATO website

* I wish that somewhere on the ATO website the word "vest" and the word "tax deferred" were linked.  The rule is simple: tax is deferred until the options vest.  But to understand that, you must read through several pages of information and examples.  Eventually, you stumble across [this page](https://www.ato.gov.au/General/Employee-share-schemes/In-detail/Restrictions-and-forfeiture/Real-risk-of-forfeiture/?page=5#Minimum_term_of_employment), where the term vest is used.  But even then there it's not clear that each month, the vested portion is no longer deferrable and must be declared, the wording makes it seem to me that if any part is still unvested, the whole lot can be deferred.
* Most of the examples on the ATO website talk about a share price as if the shares are traded on the stock market.  But this is never the case for tech startups.  Examples that describe startup situations are sorely needed.
* Most tech startup employee share schemes use the term "fair market value", while the ATO website uses the term "market value".  It would be very useful if the website says "for companies that are not publicly traded, the market value is often referred to as the fair market value.
* For most startups, employees and ex employees can ask what the fair market value was at any time from their employer.  If you don't know that, the ATO website makes it seem like it's this mystical number that it's up to you to use some unpublished methodology to determine, see [this page](https://www.ato.gov.au/General/Employee-share-schemes/In-detail/What-you-need-to-know/Employees/Employee-share-schemes---guide-for-employees/?page=10#Market_value).  It should be stated that employees can usually obtain this from their employer.
* Since there is such thing as a typical employee share scheme for tech startups, and since this is becoming more and more common, the ATO should publish a fact sheet, similar to this very document, which describes *in the same terms as commonly used in employee share schemes for tech startups*, what their tax obligations are.
