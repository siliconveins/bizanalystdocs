---
title: "Biz Analyst Docs"
date: 2017-11-10T13:56:43+05:30
draft: false
---

## Overview

Biz Analyst is a *&quot;Tally on mobile&quot;* application which sync's your **Tally ERP 9** data and shows it on your mobile. You can view *Sales*, *Purchase*, *Receivable*, *Payable*, *Cash / Bank balances*, *Delivery Note*, *Receipt Note*, *Sales Order*, *Purchase Order*, *Party*, *Items*, *Inactive Customers*, *Inactive Items*, *Ledger Report*, *Day Book* and many more things on your mobile. 

Our platform consists of two applications:
1. Desktop app
2. Mobile app (Android / IOS)

### 1. Desktop app

It is the medium which sync's your **Tally ERP 9** data with **Biz Analyst Android/IOS** app. It resides on your computer where *Tally ERP 9* is installed.

You can manage (*add, edit, delete*) your *Tally ERP 9* companies whose data you want to see on your mobile through this app.

The *Biz Analyst Desktop* app fetches data from your *Tally ERP 9* (for the companies which you have added in *Biz Analyst* to sync) then **encrypt's** that data and saves it on our server (hosted on Amazon Web Services).

It periodically checks for any changes in *Tally ERP 9* data and only saves the new data on the server instead of fetching everything again.

The Sync runs automatically and no user intervention is required.

### 2. Android / IOS app

This is the app you install on your phone to see your synced *Tally ERP 9* data. You get a list of companies from the ones you've added on *Biz Analyst* through the *Desktop application*.

Selecting a company from the list downloads its corresponding data from our server to your mobile device and later on **decrypt's** it for you to see.

You can set a *Passcode* (feature built-in) for the app so no other person can access your data without your permission.