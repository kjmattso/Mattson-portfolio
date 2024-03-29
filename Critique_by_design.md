| [home page](https://kjmattso.github.io/Mattson-portfolio/) | [visualizing-government-debt](https://kjmattso.github.io/Mattson-portfolio/Visualizing_gov_debt.html) | [critique by design](https://kjmattso.github.io/Mattson-portfolio/Critique_by_design.html) | [final project I](https://kjmattso.github.io/Mattson-portfolio/Final_project_pt1.html) | [final project II](https://kjmattso.github.io/Mattson-portfolio/Final_project_pt2.html) | [final project III](https://kjmattso.github.io/Mattson-portfolio/Final_project_pt3.html) |

# Critique by Design

I elected to redesign a visualization from Howmuch.net that shows which University in each state had the highest amount of new student loans borrowed by students in 2020 and 2021.

![U.S. Universities with the Most Loan Originations 2020-2021](https://cdn.howmuch.net/articles/university-with-the-most-student-loan-originated-in-every-state-10b5.jpg)

The issue of rising student loan debt is obviously salient to myself, as as current student. The title of this graph alone drew me eye, and I immediately looked at the states I had connections to. It was a relief not to see Carnegie Mellon as Pennsylvania's listing! However, even when I knew what I wanted to see, it was hard to parse out complete information from the graph. My eyes were drawn to many places and I was overloaded with information. Looking at this graph for even a moment inspired me to make changes on it, some were obvious and some were not. 

Obviously, I found the information from this graph relevant and important. I knew that I was well trained to read visualziations and I still struggled to read this one. Because of that, I chose to remake this graph. I think any redesign of it will greatly benefit audiences, as I believe the intended one for this is incoming college students, and they deserve to have the information communicated clearly and effectively to help them make decisions. 

To start my initial redesign, I addressed my biggest issues first. My main issues were the use of school logos, utilizing both seperate colors and colors scales, the redundancy of the color scales and dollar amount labels, and changing the format from the graph away from a U.S. map. I felt the use of school logos added unnecessary clutter and introduce opportunity for confusion is if logos are unrecognizable or are mistaken for another institution. I felt this confusion overrode any benefits of building a connection to the visualization with the logos. The use of colors to show both cost and type lead to a palette with almost 10 colors. If I had used color, I would have done so with it varying only across one dimension, but I elected not to use a color scale as I felt the information conveyed was distracting from theh main point of the visualization. This also solved the redundancy of the color scale and dollar amount labels. 

Finally I chose to change the format to a bar graph, sorted in descending order. I felt this better communicated the extreme points of the graph. The disparities across locations and insitutions felt like one of the most compelling pieces of information of the graph, and resonated with the intended audiences best, prospective students and researchers. Finally, I added a better title that I felt was in simpler language. The first redesign is pictured below:

![First Recreation](IMG_9375.png)

To get initial critiques, I interviewed two different coworkers about their initial thoughts. Both are mid-twenties and are attending college at this time, and I felt they would find this very interesting. However, there was a lot of confusion I had to account for and adjust in my final visualization. 

I asked the two of them the same 7 questions. I listed them below, along with their answers. We will call them "J" and "K"!

### 1. Where does your eye go to first?

Both J and K answered that the bars on the graph drew their attention first. I took that as good news - that their first instinct was to look at the data. I hoped it meant that I had avoided distracting design details, and they knew to look at the graph's data, or "story" as I like to call it. 

### 2. What do you think this graph is trying to tell you?

J: What college system in each state bas the most student loans, in all 50 states. Not proportional to population, just the total sum.

K: How much money people meed to borrow to go to school, and the highest is Arizona.

### 3. Did the graph leave you with additional questions? Or, did you want any more info. from the graph?

J: Yes, is it the total sum of each state? For example, Arizona v. Vermont?

K: I want to know if it's scaled by population?

### 4. Did anything confuse you? 

J: Are the students both in-state and non-residents? And the y-axis, it took me a moment to interpret. 

K: Is it both in-state and non-resident students?

### 5. Did you find anything surprising?

J: Just the results.

K: Arizona being first, and California not being in the top 5 given that it has the highest population.

### 6. Is there anything you personally would do differently?

J: No. 

K: Not all blue, with the labels, axis, and titles. Just the bars should be blue.

### 7. What audience would use this graph?

J: Policy-makers.

K: Department of Education.

Following the two interviews, I realized that the graph in it's current form was not communicating it's "story" very well yet. While they agreed that it was not confusing to read the values and results, it was hard to tell what the actual basis of each measurement was - top instution per state. The graph's current form did not allows them to grasp that, despite it's other strengths. I decided the best way to improve this was to clear up the graph axes, improve the title, and add a caption to the title. I elected to make the visualization in tableau to add additional interactive features to the graph. These included hover-boxes that shared the institution's name and type, as well as the abbreviated state/territory's full name - in case the abbreviations were not clear. 

The original visualization site did not have the data available. I had to manually input the data into an Excel sheet to import it into Tableau. I did save a but of time by finding a publicly available .xlsx sheet that had all 50 states and abbreviations, and I only had to add the 3 territories. I did have to isolate each institution name, type, and amount from the visualization and also add it to the sheet. 

The .xlsx I found was online in a publicly-available Google Sheet. You can find that [here](https://docs.google.com/spreadsheets/d/14wvnQygIX1eCVo7H5B7a96W1v5VCg6Q9yeRoESF6epw/edit#gid=0)

Once I uploaded the data, I created my first visualization in Tableau, incorporating the changes needed above. See that below:

<div class='tableauPlaceholder' id='viz1707230190897' style='position: relative'><noscript><a href='#'><img alt='Where in the U.S. did students take out the most new loans in 2020-2021? Ranked by the institution in the state or territory with the largest amount of new loans borrowed. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HW&#47;HW3and4-FirstDraft&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HW3and4-FirstDraft&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HW&#47;HW3and4-FirstDraft&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1707230190897');                   
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>

However, after the in-class critique, I realized that I wasn't quite finished. My group mates did understand the graph much better, but there was still some questions about the content. I adjusted the axes and the title to make a bit clearer and address their feedback. I also added value labels to the top state's, in addition to the hover bars. Here is my final design, after all critiques:

<div class='tableauPlaceholder' id='viz1707231249965' style='position: relative'><noscript><a href='#'><img alt='Where in the U.S. did students take out the most new loans in 2020-2021?Ranked by the university in each state that had the most new loans borrowed by student&#39;s to covert he cost of attendance in 2020-2021, regardless of loan type. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ne&#47;NewLoans-final&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NewLoans-final&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ne&#47;NewLoans-final&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1707231249965');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>
