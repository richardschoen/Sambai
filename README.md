# Sambai
IBM i Samba Client for transferring files between IBM i and Windows Servers

# Pre-Requisites
IBM i V7R2 and above

Install Samba server from the following link

https://www.ibm.com/support/pages/ibm-i-support-samba

You don't need to start the Samba server so the smbclient component of Samba can be used without disturbing any existing NetServer usage on the IBM i. However the Samba server coule be used instead of NetServer if desired. But that's another topic altogether. Sambai focuses on usinf smbclient from CL or RPG applications to send and receive files between Windows servers. 

