<head>
  <meta charset='utf-8'>
  <script src="markdown-it.min.js"></script>
  <script src="markdown-it-input.js"></script>
</head>


## Songlu Full

###### ORIGIN: *Qimen*, *Anhui*, *China*  
###### YEAR: 2021  ð±
Year/Harvest
###### VENDOR: Harney & Sons Tea  

| ð | ð§ | ð¡ | â±ï¸ | ð¼ | 
| :-: |  :-: |  :-: | :-: | :-: |
| g | mL | FÂ° | #:## |  | 
| 5.0 | 480 | 212Â° | 3:45 | ð¥ | 
| 5.0 | 480 | 205Â° | 3:15 | ð¥ |
| 8.0 | 480 | 200Â° | 3:00 | ð¥ |
| 5.5 | 480 | 212Â° | 3:30 | ð¥ |
| 6.0 | 480 | 212Â° | 4:30 | ð¥ |
| 5.0 | 480 | 212Â° | 4:00 | ð¥ |



| Tea ð« | Country | Region | Locale | Vendor | Type | ðg | ð§mL | ð¡Â°F | â±ï¸ | Result | 
| --- | :-- | :-- | :-- | :-- | :-- | --: |  --: |  --: |  --: | :-- |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 5.0 | 480 | 212 | 4:00 | â­ï¸â­ï¸â­ï¸â­ï¸ | 
| Songluo Full | China | Anhui | Qimen | Harney | Black | 6.0 | 480 | 212 | 4:30 | â­ï¸â­ï¸ |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 5.5 | 480 | 212 | 3:30 | â­ï¸â­ï¸â­ï¸ |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 8.0 | 480 | 200 | 3:00 | â­ï¸â­ï¸ |
| Songluo Full | China | Anhui | Qimen | Harney | Black | 5.0 | 480 | 205 | 3:15 | â­ï¸â­ï¸â­ï¸â­ï¸â­ï¸ |



Here is a simple footnote[^1]  
[^1]: My reference.  


~0~^UI^  

0^UI^  

0^UI^  

0~UI~  

  
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

</div>

  <script>
	document.getElementById('content').innerHTML = markdownit({html: true}).use(input, { prefix: "myform"}).render( document.getElementById('content').innerHTML );
  </script>
