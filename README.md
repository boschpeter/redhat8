# redhat8

Met nieuwe op ontwikkelaars gerichte functies, zoals containerhulpprogramma's, geavanceerde taalondersteuning en applicatiestromen, 
is Red Hat Enterprise Linux 8 (RHEL) de meest ontwikkelaarvriendelijke Linux ooit. 
Red Hat Developer-leden hebben volledige toegang tot RHEL 8-software, documentatie en how-to's.
Als je bekend bent met Red Hat Enterprise Linux, dan is dit de plek om aan de slag te gaan.


````
Get started on RHEL 8
Red Hat Enterprise Linux 8 introduces new features that accelerate your application development including installation, coding, tool selection and setup. It includes dozens of runtime languages, compilers, databases, and web and cache servers.

Start with these commands below for your first time through.

For the impatient, use this yum syntax to install an Application Stream @modulename[:version]

Most recent version:

  # yum install @postgresql       # installs the default, PostgreSQL 10
Or, install a specific version:

  # yum install @postgresql:9.6   # installs PostgreSQL 9.6
Use this if you want to see a list of what’s available:

  # yum module list               # find available application streams
For container development, RHEL 8 adds new Linux container tools:  Buildah (container building), Podman (running containers) and Skopeo (sharing/finding containers). You can easily build images based on the many Application Streams.

For a quick reference to new RHEL 8 commands, download the Red Hat Enterprise Linux 8 Cheat Sheet for tips.

 

````

## ssh-copy-id -i ~/.ssh/id_rsa.pub boscp08@redhat_01

etc/hosts.  redhat_01 192.168.2.15
````
osxs-mbp:~ osx$ ssh-copy-id -i ~/.ssh/id_rsa.pub boscp08@redhat_01
/usr/bin/ssh-copy-id: INFO: Source of key(s) to be installed: "/Users/osx/.ssh/id_rsa.pub"
The authenticity of host 'redhat_01 (192.168.2.15)' can't be established.
ECDSA key fingerprint is SHA256:QUqp3PlzOP6L6l1UlaJpiXw02hFxhZvnhyE1szLbVB4.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
/usr/bin/ssh-copy-id: INFO: attempting to log in with the new key(s), to filter out any that are already installed
/usr/bin/ssh-copy-id: INFO: 1 key(s) remain to be installed -- if you are prompted now it is to install the new keys
boscp08@redhat_01's password: 

Number of key(s) added:        1

Now try logging into the machine, with:   "ssh 'boscp08@redhat_01'"
and check to make sure that only the key(s) you wanted were added.

````
