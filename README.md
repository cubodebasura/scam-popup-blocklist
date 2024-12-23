# Introducing the Scam Pop-Up Blocklist
Simply copy https://raw.githubusercontent.com/cubodebasura/scam-popup-blocklist/refs/heads/main/list.txt into your Pi-hole config.

## What does this list block?
This list mainly aims to block scam pop-ups (think "Windows virus! Call this toll-free number!").
It also blocks a few ConnectWise (ScreenConnect) servers that have been identified as belonging to scammers.

## How reliable is it?
Some domains are added to here before the scammers even have a chance to deploy them.
It does appear to block more US-aimed Microsoft scams, but some others have been found too.
A solution is being worked on to find pop-ups targeting other countries, such as Australia, Ireland, UK, and New Zealand.
