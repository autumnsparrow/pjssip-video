

#2017-11-27


- **Problem:**

![][gdb-eclipse-problem]


- Solution for Eclipse debug pjsip


   [choose another gdb](http://wiki.eclipse.org/CDT/User/FAQ#How_can_I_choose_another_debugger_integration_for_CDT.3F)
   
   
   **NOTICE**
   
   - when generate the cert in the system keychain app and using custom ,must fufill the email address.


	*Let me override the defaults*
	
   ![][gdb-cert-1]
   
   *email address*
   
   ![][gdb-cert-2]
   
   *System keychains*
   
   ![][gdb-cert-3]
   

   
   
   - when setting the debugger in eclipse ,also need to change the location of .gdbinit

	![][gdb-init]
   
   
   >AppledeMacBook-Pro:x86_64-apple-darwin17.2.0 apple$ more ~/.gdbinit
   `
set startup-with-shell off
`
   
   
   
 [gdb-eclipse-problem]: ./images/gdb-problem.png
 [gdb-cert-1]: ./images/gdb-cert-1.png
 [gdb-cert-2]: ./images/gdb-cert-2.png
 [gdb-cert-3]: ./images/gdb-cert-3.png
 [gdb-init]: ./images/gdb_init.png