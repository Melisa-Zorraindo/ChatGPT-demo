# ChatGPT-demo

Welcome to the ChatGPT case study repository, where I explore the exciting potential of this chatbot in web development. Through this case study, I aim to demonstrate its strengths and weaknesses as well as the challenges it faced in designing and implementing the task.

## Choosing a task

One of the initial challenges I faced was finding an attainable task for the bot. As my original goal was for ChatGPT to code an entire website, I had to consider its limitations, such as its inability to generate drawings or pictures. Additionally, it appeared to struggle with understanding the complexity of some popular games.

To overcome this challenge, I chose a more manageable objective, which was to programme an analog clock using HTML, CSS, and JavaScript.

## The procedure

To begin the case study, I asked ChatGPT to build a clock using HTML, CSS, and JavaScript. However, the initial HTML code provided in `images/code-snippets/1` was incomplete, as it lacked basic code such as links to the CSS and JavaScript files. Nevertheless, it is fair to mention that in previous attempts to create an app the bot sometimes provided the entire HTML code - it appears inconsistent in this regard. Therefore, I had to manually add the necessary code.

Moving on to the CSS, `images/code-snippets/2` illustrates that the CSS code was also incomplete. The bot apologised for the mistake and provided a new code snippet, which was again incomplete. Although I requested only the remaining code for the incomplete class, the bot generated another incomplete code snippet. Eventually, I managed to obtain the lines of code that were missing for the last class in the code snippet, as shown in `images/code-snippets/3`.

In images/code-snippets/4`, the bot provided the JavaScript code. However, as there were issues in obtaining the complete CSS code, it 'forgot' to give me the JavaScript and I had to request it again. Additionally, it provided an explanation on what the functions it had coded were designed to do. See `images/code-snippets/5`.

The clock displayed in `images/results/1-html-css.PNG` illustrates that the dots representing the time were positioned incorrectly, and only one hand was visible. To address the visibility issue, I requested the bot to modify the relevant classes, which are presented in `images/code-snippets/6`. The updated clock with the modified code is displayed in `images/results/2-added-missing-hands.PNG`.

Since I preferred to have numbers instead of dots to mark the time, I asked the bot to replace them. However, the prompt may have been too vague for the bot to comprehend my request, as it generated a new CSS file with replaced classes in `images/code-snippets/7`. Subsequently, I requested an HTML file that matched the CSS with numbers instead of empty `<div>` tags in `images/code-snippets/8`, which is illustrated in `images/results/3-replace-dots-for-numbers.PNG`.

Next, I requested the bot to fix the position of the numbers, but it provided an incomplete CSS file. I then requested the remaining code, but, as seen in `images/results/4-failed-at-fixing-numbers-position.PNG`, it did not solve the issue. There were two bugs here. The first one had to do with the assignment of the CSS classes, which I fixed manually as seen in `images/results/5-human-fixed-name-classes.PNG`. The second one was in the properties `top`, `bottom`, `right`, and `left`, which were given percentages that didn't display the numbers in the right position. I also fixed this manually, as shown in `images/results/6-human-fixed-numbers-position.PNG`.

Similarly, I requested the bot to fix the position of the hands, but the code provided in `images/code-snippets/9` did not solve the issue, as shown in `images/results/7-failed-at-fixing-hands-position.PNG`. Therefore, the bug had to be fixed manually, which is demonstrated in `images/results/8-human-fixed-hands-position.PNG`.

Finally, I requested the bot to fix the time, as there was a discrepancy of 3 hours and 25 minutes with my actual time. The bot provided an explanation for the issue (see `images/code-snippets/10`) and generated a new code snippet for the JavaScript file, as presented in `images/code-snippets/11`. However, the code did not solve the issue, and I requested a bug fix. The bot provided a different explanation for the issue as shown in `images/code-snippets/12` and generated another code snippet, which is illustrated in `images/code-snippets/13`. Nonetheless, the code still did not solve the bug, and I had to fix it manually, as shown in `images/results/9-human-fixed-javascript-function.PNG`.
