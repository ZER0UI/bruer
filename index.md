<script src="markdown-it-min.js"></script>
<script src="markdown-it-input.js"></script>

## Songlu Full

###### ORIGIN: *Qimen*, *Anhui*, *China*  
###### YEAR: 2021  🌱
Year/Harvest
###### VENDOR: Harney & Sons Tea  

| 🍃 | 💧 | 🌡 | ⏱️ | 🎼 | 
| :-: |  :-: |  :-: | :-: | :-: |
| g | mL | F° | #:## |  | 
| 5.0 | 480 | 212° | 3:45 | 🏅 | 
| 5.0 | 480 | 205° | 3:15 |🏅|
| 8.0 | 480 | 200° | 3:00 | 🥉 |
| 5.5 | 480 | 212° | 3:30 |🥈 |
| 6.0 | 480 | 212° | 4:30 | 🏅|
| 5.0 | 480 | 212° | 4:00 | 🏅 |



| Tea 🫖 | Country | Region | Locale | Vendor | Type | 🍃g | 💧mL | 🌡°F | ⏱️ | Result | 
| --- | :-- | :-- | :-- | :-- | :-- | --: |  --: |  --: |  --: | :-- |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 5.0 | 480 | 212 | 4:00 | ⭐️⭐️⭐️⭐️ | 
| Songluo Full | China | Anhui | Qimen | Harney | Black | 6.0 | 480 | 212 | 4:30 | ⭐️⭐️ |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 5.5 | 480 | 212 | 3:30 | ⭐️⭐️⭐️ |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 8.0 | 480 | 200 | 3:00 | ⭐️⭐️ |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 5.0 | 480 | 205 | 3:15 | ⭐️⭐️⭐️⭐️⭐️ |



  
<div id="content">
Name = ___

"""
"""
<!-- input: { "name":"mytextarea", "value":"Your text\n...\n...\n...", "div":{"id":"myTextareaID"} } -->

Select your option(s) = [] Option 1 [] Option 2 [] Option 3
<!-- input: { "name":"input3", "options": [{},{"checked":"checked"},{}] } -->

Select (exactly) one option = () Option 1 () Option 2 () Option 3

Please select = {Option 1; Option 2; Option 3}
  

Name = ___

Name [yourname] = ___

Name [yourname] = __Your name__

"""
"""

"""c++
#include <iostream>
using namespace std;

int main() 
{
    cout << "Hello, World!";
    return 0;
}
"""[code]
  
Select your option(s)[checkbox] = [] Option 1 | Value 1 [] Option 2 | Value 2 [] Option 3 | Value 3
  
Select (exactly) one option[radio] = () Option 1 | Value 1 () Option 2 | Value 2 () Option 3  | Value 3
  
Please select[dropdown] = {Option 1 | Value 1 ; Option 2 | Value 2; Option 3 | Value 3 }
  
<!-- input: { "name":"input", "value":"Some value", "div": {"class"="input"} } -->
  
</div>

  <script>
	document.getElementById('content').innerHTML = markdownit({html: true}).use(input, { prefix: "myform"}).render( document.getElementById('content').innerHTML );
  </script>
  

Here is a simple footnote[^1]  
[^1]: My reference.  


~0~^UI^  

0^UI^  

0^UI^  

0~UI~  
