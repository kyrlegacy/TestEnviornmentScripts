# TestEnviornmentScripts
Powershell scripts that can help build an enviornment using pre-made settings

This is a side project. With how often I build and tear down my lab enviornment I figured I would automate the things that I can.
Initial scripts include

Domain Setup: 
This script can be run on a fresh AD install to build a test enviornment and set up some basic AD settings such as:
  A test ou with a bunch of site locations and within those locations different departments
  An ou for users and computers within each department for organization
  A NOC department with some more ou underneath; Servers, Service Accounts, Domain Admin accounts
  Creates basic domain admin accounts as well as basic user accounts and adds them to respective groups
  Sets all accounts and user passwords to P@ssword because this is a test enviornment and security isn't the main concern

Domain Controller Setup:
This script can be run on a fresh server install to install AD Domain Services on it without having to go through the gui

