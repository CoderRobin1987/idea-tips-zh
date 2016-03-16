135.Pressing the same shortcut after you have invoked Smart-type Completion when there's an array of expected type in context will suggest to get an element from this array. 

 ![](135.png)

136.Pressing the same shortcut after you have invoked Smart-type Completion when a collection type is expected will search for arrays with same component type and suggest to convert them using Arrays.asList() call. 

 ![](136-1.png)

 ![](136-2.png)

137.Pressing the same shortcut after you have invoked Smart-type Completion will search for chained expressions which have expected type. 
 
 ![](137.png)

138.When using Code Completion, you can accept the currently highlighted selection in the popup list with the Ctrl+Shift+Enter, IntelliJ IDEA will not just insert the selected string, but also will do its best to turn current code construct into syntactically correct one (balance parentheses, add missing braces and semicolons, etc.) 

139.When using Code Completion in Java, you can accept the currently highlighted selection in the popup list with the exclamation sign (!) character. It will be inserted before the boolean method or variable you were completing, thus negating the whole expression. 
 
 ![](139-1.png)

After pressing '!': 
  
 ![](139-2.png)
 
140.To quickly complete a method call of a static method located anywhere in your project, libraries or JDK, enter a prefix and press Ctrl+空格 twice. You'll see all the matching methods. If you want the method you chose to be imported statically, press Alt+Enter and see what happens: 
 
 ![](140.png)

141.When you invoked Basic Completion (Ctrl+空格) in Java and didn't find your desired class in the list, it means that it's not yet imported in current file. Pressing Ctrl+空格 once more to view all accessible classes. 
 
 ![](141.png)

142.Pressing the same shortcut after you have invoked Smart-type Completion when an array type is expected will search for collections with same component type and suggest to convert them using toArray() call. 
 
 ![](142-1.png)
  
 ![](142-2.png)
 
143.You can switch between sorting completion variants by relevance or alphabetically by using an icon at the bottom right: 
  
 ![](143.png)
 
144.Postfix code completion is applied "from right to left" and lets you avoid backward caret jumps when coding. After the code fragment that you want to change, type a dot (.), optionally press Ctrl+J and select the desired option. 
  
 ![](144.png)
 
145.Scratch files allows you experiment and prototype right in the editor, without creating any project files. 
To create a scratch file, press Ctrl+Alt+Shift+Insert, and then select its language. 
  
 ![](145.png)
 
146.If you've changed a live template, it becomes blue. If you want to return to the original text, right-click such a blue template, and choose Restore defaults on the context menu.

147.Add several cursors to your editor. To do that, press Ctrl twice and hold the key, and then press the arrow keys. 
On Mac use Alt instead of Ctrl. 
  
 ![](147.png)
 
148.Clone the cursor strictly upwards or downwards. To do that, press Ctrl+Shift+A, type Clone caret, and then choose the desired action. 
 
 ![](148.png)
 
149.When choosing a live template from a suggestion list, press Ctrl+Q to view quick documentation - to be sure you make a right choice: 
 
 ![](149.png)
 
150.You don't need to invoke quick documentation explicitly (Ctrl+Q) - if you just move your mouse pointer over the desired symbol, the quick documentation pop-up window will show automatically. 
To enable this feature, select the check box Show quick doc on mouse move in the editor settings. 
