# Offensive Security Intro — TryHackMe Writeup

## What is Offensive Security?
Offensive security is the practice of thinking like a hacker — breaking into systems, finding vulnerabilities, and exploiting loopholes in order to understand how to better defend them.

## The Task
I was given access to a simulated banking website called FakeBank in a safe, legal environment. My goal was to find hidden pages on the website that shouldn't be publicly accessible.

## Tool Used — GoBuster
GoBuster is a command-line tool that brute-forces websites by trying a long list of possible directory names and reporting back which ones actually exist.

## Command Used
gobuster -u http://fakebank.thm -w wordlist.txt dir

## What I Found
GoBuster discovered a hidden `/bank-transfer` page that wasn't linked anywhere on the site. I used that page to transfer money between accounts — demonstrating how a real attacker could exploit an exposed admin page left unprotected.

## Key Takeaway
Even if a page isn't visible or linked on a website, it can still be accessible if not properly secured. Tools like GoBuster help ethical hackers find these gaps before malicious actors do.
