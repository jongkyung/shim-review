Make sure you have provided the following information:

 - [ ] link to your code branch cloned from rhboot/shim-review in the form user/repo@tag
 - [ ] completed README.md file with the necessary information
 - [ ] shim.efi to be signed
 - [ ] public portion of your certificate embedded in shim (the file passed to VENDOR_CERT_FILE)
 - [ ] any extra patches to shim via your own git tree or as files
 - [ ] any extra patches to grub via your own git tree or as files
 - [ ] build logs


###### What organization or people are asking to have this signed:
`[Gooroom]`

###### What product or service is this for:
`[Gooroom OS]`

###### What is the origin and full version number of your shim?
`[shim 15+1533136590.3beb971-0ubuntu1+grm1u1]`

###### What's the justification that this really does need to be signed for the whole world to be able to boot it:
`[To make secure boot on Gooroom OS]`

###### How do you manage and protect the keys used in your SHIM?
`[no]`

###### Do you use EV certificates as embedded certificates in the SHIM?
`[no]`

###### What is the origin and full version number of your bootloader (GRUB or other)?
`[grub2 ]`

###### If your SHIM launches any other components, please provide further details on what is launched
`[none]`

###### How do the launched components prevent execution of unauthenticated code?
`[We will show messages that execution of unauthenticated code isn't working]`

###### Does your SHIM load any loaders that support loading unsigned kernels (e.g. GRUB)?
`[no]`

###### What kernel are you using? Which patches does it includes to enforce Secure Boot?
`[linux 4.9.110-3+deb9u6+grm1u2]`

###### What changes were made since your SHIM was last signed?
`[no, It's first time]`

###### What is the hash of your final SHIM binary?
`[sha256shum fb501b838fe9b91b6adfd9eaa5ff0c5824c7f802fcdc1f960d13a11f3a3db76c  ./shimx64.efi]`
