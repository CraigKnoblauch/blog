---
date: '2025-07-27T19:04:06-04:00'
draft: true
title: 'Nickel Receipt Ingestion'
---

I've been working on a little personal finance project. The goal of this project is to create datapipelines that serve a central ledger. From that ledger I can build reports for insights into my finances. 

The first pipeline I wanted to build is a receipt ingestion pipeline. One of the most common purchases I make are my day to day purchases that often come with a paper receipt. I used to keep all of these receipts and enter them into a ledger by hand. 

That is an insanely annoying habit to keep up with. 

I always wanted a workflow that would require minimal thought from me and would _automatically_ ingest the receipts for me. After some iteration I think I've got an approach that's working for me.

# Architecture

