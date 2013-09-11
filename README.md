xbmc-hebrew-fonts
=================

---------------------------  
About
---------------------------    

The Problem:  
Some of the fonts that were included with XBMC skins were missing Hebrew glyphs.  

The Solution:  
Merging together Hebrew fonts with the ones that don't include Hebrew glyphs.  
  
I'm not a typographer so I've got no clue on font design, If you do then you're welcome to contribue: pr, open an issue or email to admin-at-xbmc-il.com.  


Tree structure:  
/ 				: The merged fonts.  
/sources_he/ 			: The original Hebrew fonts (without change).  
/sources_he_no_latin_gylphs/ 	: The Hebrew fonts ready to be merged after removing non Hebrew glyphs.  
/sources_latin/			: The originals fonts of XBMC's skins (which aren't support Hebrew).  


Details:  
* OpenSans-Light-xbmc-il = OpenSans-Light + OpenSansHebrew-Light  
* OpenSans-Regular-xbmc-il = OpenSans-Regular + OpenSansHebrew-Regular  
* Roboto-Bold-xbmc-il = Roboto-Bold + DroidSansHebrew-Bold  
* Roboto-Regular-xbmc-il = Roboto-Regular + DroidSansHebrew-Regular  


Fonts Sources and Info:  
* Droid Sans Hebrew: The fonts source is the Android platform frameworks base, designed by Ascender Corporation commissioned by Google | Apache License, version 2.0 | https://github.com/android/platform_frameworks_base/tree/master/data/fonts .  
* Open Sans Hebrew:  The fonts source is Google Fonts Early Accessdesigned by Yanek Iontef | Apache License, version 2.0 | http://www.google.com/fonts/earlyaccess .
* Open Sans: The fonts source is Bello skin created by Nessus85100 and are derivative of the fonts Open Sans designed by Steve Matteson (foundry: Ascender Corporation) | Apache License, version 2.0 | https://github.com/Nessus85100/Bello/tree/master/fonts .  
* Roboto: The fonts source is Confluence skin created by uNiversaI and are derivative of the fonts Roboto designed by Christian Robertson (Commissioned by Google) | Apache License, version 2.0 | https://github.com/uNiversaI/skin.confluence/tree/master/skin.confluence/fonts .  


---------------------------  
LICENSE  
---------------------------  

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
  
     http://www.apache.org/licenses/LICENSE-2.0
  
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

See full licence file LICENSE.txt