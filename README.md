Download Link: https://assignmentchef.com/product/solved-ecgr3180-assignment-3-queuelist
<br>



<ol>

 <li> Fill in the functions for the code snippet below. The functions will implement an integer <u>stack</u> using <u>deques</u> Try to implement it using only one deque, but a solution with two deques will also be accepted. You may add additional public helper functions or private members/functions. Do not submit your test code (<strong>main()</strong> function), but your functions need to account for test cases (e.g. pop when the stack is empty, etc).</li>

</ol>

What is the Big-Oh <strong><em>O()</em></strong> time for your implementation of the functions <strong>push()</strong> and <strong>pop()</strong> below? Assume there are <em>n</em> elements in stack.

The list of available options for a deque is available at: <a href="http://cplusplus.com/reference/deque/deque/">http://cplusplus.com/reference/deque/deque/</a>  Your MyStack class will be instantiated via a pointer and called as shown below:




<strong>MyStack *ptr = new MyStack(); ptr-&gt;push(value); int pop1 = ptr-&gt;pop(); int pop2 = ptr-&gt;pop(); </strong>

<strong>bool isEmpty = ptr-&gt;empty(); </strong>

Name the file you submit  <strong>MyStackDeque.cpp </strong>

<table width="557">

 <tbody>

  <tr>

   <td width="557"><strong>class MyStack { public: </strong><strong>    // Default Constructor </strong><strong>    MyStack() {// … } </strong><strong>     </strong><strong>    // Push integer n onto top of stack     void push(int n) {// … } </strong><strong>     </strong><strong>    // Pop element on top of stack     int pop() {// … } </strong><strong>     </strong><strong>    // Get the top element but do not pop it (peek at top of stack)     int top() {// … } </strong><strong>     </strong><strong>    // Return whether the stack is empty or not     bool empty() {// … } }; </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<ol start="2">

 <li><strong>(10 pts)</strong> Implement the <strong>MyStack</strong> class in Problem 1 using <u>vectors</u>. Name the file you submit</li>

</ol>

<strong>MyStackVector.cpp </strong>

<ol start="3">

 <li> Fill in the functions for the code snippet below. The functions will implement an integer <u>list</u> using a <u>dynamic array</u> only (an array that can grow and shrink as needed, uses a pointer and size of array.) For more information: <a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">https://www.geeksforgeeks.org/how</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">–</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">do</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">–</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">dynamic</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">–</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">arrays</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">–</a><a href="https://www.geeksforgeeks.org/how-do-dynamic-arrays-work/">work/</a> You may add additional public helper functions or private members/functions.</li>

</ol>

Do not submit your test code (<strong>main()</strong> function), but your functions need to account for test cases (e.g. pop when the list is empty, etc). <strong> </strong>

Your  <strong>MyList</strong> class will be instantiated via a pointer and called similar to the code in Problem 1. Name the file you submit  <strong>MyListDyn.cpp </strong>

<table width="557">

 <tbody>

  <tr>

   <td width="557"> <strong>class MyList { </strong><sup> </sup><strong>public: </strong><strong>    // Default Constructor </strong><strong>    MyList() {// … } </strong><strong>     </strong><strong>    // Push integer n onto the end of the list     void push_back(int n) {// … } </strong><strong>     </strong><strong>    // Push integer n onto the beginning of the list     void push_front(int n) {// … } </strong><strong> </strong><strong>    // Pop element at the end of list     int pop_back() {// … } </strong><strong> </strong><strong>    // Pop element at the beginning of list     int pop_front() {// … } </strong><strong>     </strong><strong>    // Adds value at index pos. Indices start at 0     void emplace(int pos, int value) {// … } </strong><strong>     </strong><strong>    // Return whether the list is empty or not     bool empty() {// … } }; </strong></td>

  </tr>

 </tbody>

</table>


