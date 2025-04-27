# cs-251-data-structures-project-01-spam-filter-program-solved
**TO GET THIS SOLUTION VISIT:** [CS 251 : Data Structures Project #01: Spam filter program Solved](https://www.ankitcodinghub.com/product/cs-251-data-structures-project-01-spam-filter-program-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;55894&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS 251 : Data Structures  Project #01: Spam filter program Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Assignment

Most email systems automatically filter “spam” into a separate folder.&nbsp; The filtering process is typically based on a “spam list” that identifies spam when email is loaded into your inbox.&nbsp; In this assignment you’re going to create a C++ program that is able to

&nbsp;

<ol>
<li>load a spam list,</li>
<li>display the contents of a spam list,</li>
<li>check a single email address to see if it’s spam,</li>
<li>filter an email list and output the resulting emails to a file</li>
</ol>
&nbsp;

For example, to the right is a screenshot of the program in action, loading “spamlist1.txt”, displaying the contents, checking a couple email addresses to see if they are spam, and then filtering an email list in “emails1.txt” to eliminate spam emails.&nbsp; The currently loaded spam list defines what is considered spam; the user can load different spam lists.

&nbsp;

Pay close attention to the formatting of the output, as the Gradescope submission system will require you to adhere to this output format.&nbsp; Also note that when the program ends, some stats are output based on how efficiently the problem was solved.&nbsp; If M is the # of emails processed and N is the # of emails in the spam list, your solution should insert at most O(N) elements, and access at most O(MlgN) elements.

&nbsp;

<h2>Assignment details</h2>
The goals of this assignment are to (1) practice creating <strong>functions</strong>, (2) work with C++ <strong>strings</strong> and string functions, (3) work with <strong>vectors</strong>, and (4) read and write files.&nbsp; Many of you are new to C++, so working with strings, vectors, and files are an important introduction to C++.

&nbsp;

When you load a spam list, you are required to input the data into 1 or more vectors.&nbsp; You cannot use any other data structure, and you cannot use a C-based array — you must use a vector.&nbsp; In fact, you’ll use an implementation of vector we provide:&nbsp; <strong>ourvector&lt;T&gt;</strong>, which is available on the course dropbox under Projects, <a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">project01</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">–</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">files</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">.</a>&nbsp; Your program must support 4 commands:&nbsp; load, display, check, and filter.&nbsp; Each of these commands must be implemented by a function that is called by main().&nbsp; You can (and should) have additional functions, but these 4 are required.&nbsp; Finally, since efficiency is an important component of this class, you are required to search the spam list using <strong>binary search</strong>.&nbsp; Binary search requires only O(lgN) time, whereas linear search takes O(N) time.&nbsp; <u>Example</u>:&nbsp; if N = 1,000,000 elements, binary search takes roughly 20 comparisons to find an element, whereas linear search takes an average of 500,000 comparisons.&nbsp; Big difference.

&nbsp;

Note that a spam list is guaranteed to be in sorted order by domain, and if two spam entries have the same domain, they are ordered by username (where “*” is naturally sorted first).&nbsp; This implies that binary search can be used without the need to sort the spam list.

&nbsp;

Two larger lists are provided for you to test the efficiency of your program.&nbsp; As shown in the screenshot below, the file “spamlist_10k.txt” contains 10,000 spam entries.&nbsp; This list is then used to filter an email list of 1,000 emails (“emails_1k.txt”).&nbsp; Let M = 1,000, and N = 10,000.&nbsp; If your solution is efficient, searching the spam list once should required O(lgN) = log<sub>2</sub>(10,000) = 14 comparisons / vector accesses.&nbsp; This search is repeated 1,000 times (once for each email), so an efficient filtering should require roughly 14,000 vector accesses.&nbsp; As shown below in the stats, the vector was accessed 12,949 times, denoting an efficient O(M * lgN) solution.

&nbsp;

&nbsp;

<h2>Input and Output file formats</h2>
A spam list contains 1 or more lines, where each line contains a single string denoting a spam address.&nbsp; There are 2 possible formats for a spam address:&nbsp; domain:* or domain:username.&nbsp; The “*” means any username associated with that domain is spam; otherwise an email is spam only if the username and domain both match.&nbsp; Here’s the contents of “spamlist1.txt” that was shown earlier (and again in screenshot to right):

&nbsp;

<strong>aaa.com:user bestbuy.com:coupons bestbuy.com:offers groupon.com:* groupon.com:reseller important.com:dont_ignore massemail.com:* organicfoods.com:noreply uic.edu:accc uic.edu:chancellor uic.edu:rewards xyz.com:user1 </strong>

&nbsp;

The file is guaranteed to be in alphabetical order by domain; if 2 strings have the same domain, they will be ordered by username (“*” will proceed any other username).

&nbsp;

The other possible input file is an email list, which is processed by the filter command.&nbsp; An email list consists of 1 or more lines, which each line contains 3 values:

&nbsp;

<strong>MsgID&nbsp; EmailAddress&nbsp; Subject </strong>

&nbsp;

For example, here is the contents of the “email1.txt” file used in the screenshot shown above:

&nbsp;

<ul>
<li><strong>jhummel2@uic.edu Question about grading… </strong></li>
<li><strong>coupons@bestbuy.com This week only: free TV with purchase </strong></li>
<li><strong>pooja@piazza.com Please update profile </strong></li>
<li><strong>abcd@uic.edu This is not spam, seriously, not spam </strong></li>
<li><strong>adef@uic.edu This is also not spam, seriously, spam it is not </strong></li>
<li><strong>reed@uic.edu Can you help? </strong></li>
<li><strong>offers@bestbuy.com Please buy more stuff! </strong></li>
<li><strong>techsupport@bestbuy.com Please update your profile </strong></li>
</ul>
<strong>33 user@xyz.com Important msg frm user </strong>

<ul>
<li><strong>user1@xyz.com A really non-important msg </strong></li>
<li><strong>user1@xyzz.com Seriously, this one is important </strong></li>
<li><strong>reseller@groupon.com Yup, you got me, spam </strong></li>
</ul>
<strong>99 fred@massemail.com you’ll like this offer </strong>

<strong>121 jon@groupon.com Please update your pwd </strong>

<strong>123 sue@groupons.com You can’t miss this deal </strong>

<strong>155 chancellor@uic.edu Just kidding </strong>

<ul>
<li><strong>accc@uic.edu VPN is now operational </strong></li>
<li><strong>accc@uic.edu VPN is down </strong></li>
</ul>
<strong>254 important@uic.edu Tuition waivers for all! </strong>

<ul>
<li><strong>rewards@uic.edu Subway sandwiches free every friday </strong></li>
<li><strong>testing@uic.edu Testing</strong></li>
</ul>
&nbsp;

The message ID is always an integer, the email address is a single string (i.e. no spaces), and the subject is a string containing 1 or more words.&nbsp; The message IDs may or may not be in ascending order.&nbsp; As noted later on in the section entitled “Learning C++”, use the <strong>&gt;&gt;</strong> operator to input the message ID and email address, and use the <strong>getline()</strong> function to input the multi-word subject.

&nbsp;

Based on a spam list and an email list, the filter command filters the email and produces a corresponding output file containing the email list with spam emails removed.&nbsp; Given the spam list and email lists shown above, the program would filter and produce the following output file (“output1.txt” in the screenshot):

&nbsp;

<strong>9 jhummel2@uic.edu&nbsp; Question about grading… </strong>

<ul>
<li><strong>pooja@piazza.com Please update profile </strong></li>
<li><strong>abcd@uic.edu This is not spam, seriously, not spam </strong></li>
<li><strong>adef@uic.edu This is also not spam, seriously, spam it is not </strong></li>
</ul>
<strong>21 reed@uic.edu&nbsp; Can you help? </strong>

<strong>23 techsupport@bestbuy.com&nbsp; Please update your profile </strong>

<strong>33 user@xyz.com&nbsp; Important msg frm user </strong>

<strong>42 user1@xyzz.com&nbsp; Seriously, this one is important </strong>

<strong>123 sue@groupons.com&nbsp; You can’t miss this deal 254 important@uic.edu&nbsp; Tuition waivers for all! </strong>

<strong>261 testing@uic.edu&nbsp; Testing </strong>

&nbsp;

Sample input files — both spam lists and email lists — are provided in the course dropbox under Projects, <a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">project01</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">–</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">files</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">.</a>

<h2>Program functionality</h2>
Email filtering is based on the currently loaded spam list.&nbsp; Your program should support filtering by different spam lists.&nbsp; An example is shown here:

&nbsp;

&nbsp;

&nbsp;

<strong><u>Hint</u></strong>: your program should have a spam vector with the currently loaded spam list.&nbsp; When the user loads a

new spam list, clear the vector before loading the new spam entries.

&nbsp;

Your program is required to work properly if the input or output files cannot be opened, the user specifies an unknown command, the user inputs a badly-formed email address, or the user tries to display / check / filter before loading a spam list.&nbsp; Examples with expected output:

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Keep in mind that our Gradescope submission system will be auto-grading your output, so you need to match the responses shown above *exactly*.

<h2>Learning C++</h2>
You may be new to C++, or perhaps new to the features of C++ needed in this assignment.&nbsp; Homework #01 and #02 will help you prepare, so we strongly recommend you complete those HW exercises before starting.

&nbsp;

You’ll need some string processing, namely finding characters within a string, and extracting a substring.&nbsp; While you can certainly write these functions yourself, it’s expected that you’ll use the .find() and .substr() functions built into the <strong>string</strong> class provided by C++:&nbsp; <a href="http://www.cplusplus.com/reference/string/string/">http://www.cplusplus.com/reference/string/string/</a><a href="http://www.cplusplus.com/reference/string/string/">.</a>&nbsp; Don’t forget to #include &lt;string&gt;.

&nbsp;

Your solution is required to store all data in a <strong>vector&lt;T&gt;</strong> class — to be precise, in an vector-compatible implementation we are providing:&nbsp; <strong>ourvector&lt;T&gt;</strong>.&nbsp; For the purposes of this assignment, always start with an empty vector, and then add data to the vector by calling the <strong>push_back()</strong> member function.&nbsp; When you need to access an element of the vector, use the <strong>.at()</strong> function, or the more convenient and familiar <strong>[ ]</strong> syntax.&nbsp; To empty a vector in order to load a new spam list, use the <strong>.clear()</strong> function.&nbsp; For more info on vector&lt;T&gt;: <a href="http://www.cplusplus.com/reference/vector/vector/">http://www.cplusplus.com/reference/vector/vector/</a><a href="http://www.cplusplus.com/reference/vector/vector/">.</a>&nbsp; Don’t forget to #include “ourvector.h”, which is available on the course dropbox under Projects, <a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">project01</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">–</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">files</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">.</a>

&nbsp;

Finally, to work with files, #include &lt;fstream&gt;.&nbsp; To read from a file, use an <strong>ifstream</strong> object, and use the <strong>&gt;&gt;</strong> operator when inputting a single value (e.g. integer or single word).&nbsp; When you need to input 1 or more words into a single string variable, such as the email subject, use <strong>getline(infile, variable)</strong>.&nbsp; Example of reading a file that contains one string per line, where each string is just one word (i.e. no spaces):

&nbsp;

string infilename; infilename = …;

&nbsp;

ifstream <strong>infile</strong>(infilename);&nbsp; // use infile object to read from file

if (!<strong>infile</strong>.good())&nbsp; // unable to open input file: {&nbsp;&nbsp;&nbsp; … } else

{ string oneWord;

<strong>infile</strong> &gt;&gt; oneWord; while (!<strong>infile</strong>.eof())&nbsp; // until we hit the end-of-file: {

.

.&nbsp; // process

.

&nbsp;

<strong>infile</strong> &gt;&gt; oneWord;

}

<strong>infile</strong>.close();

}

&nbsp;

&nbsp;

To write to an output file, use an <strong>ofstream</strong> object and the <strong>&lt;&lt;</strong> operator.&nbsp; Here’s an example of writing the string “hello world!” to a file:

&nbsp;

string outfilename; outfilename = …;

&nbsp;

ofstream <strong>outfile</strong>(outfilename);&nbsp; // use outfile object to write to file

if (!<strong>outfile</strong>.good())&nbsp; // unable to open output file:

{ … } else

{ <strong>outfile</strong> &lt;&lt; “hello world!” &lt;&lt; endl;

<strong>outfile</strong>.close();&nbsp; // make sure contents are written by closing file: }

&nbsp;

<h2>Programming Environment</h2>
You are free to program on whatever platform you want, using whatever compiler / programming environment you want.&nbsp; Input files and “ourvector.h” are available in the course dropbox under Projects, <a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">project01</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">–</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">files</a><a href="https://www.dropbox.com/sh/a5q1i2q50xvn7gd/AABanIBYFDHAazxn9q5tT2JWa?dl=0">.</a>&nbsp; If you do not have a C++ programming environment that you like, we recommend <strong>Codio</strong>; see the appendix at the end of this document for getting started with Codio.

&nbsp;

Be aware that we are using <strong>Gradescope</strong> as our grading platform, and it’s common for C++ programs to

“work on my platform” but fail on Gradescope.&nbsp; This is due to logic errors in *your* program, not an error with Gradescope.&nbsp; The most common mistake is a memory-related error, e.g. using an uninitialized variable or accessing memory outside the bounds of an array or via an invalid pointer.&nbsp; These errors are hard to find; the tools <strong>valgrind</strong> and <strong>cppcheck</strong> (available on Codio) can help.

&nbsp;

Gradescope is running on Ubuntu Linux, and we are compiling via <strong>g++</strong> with <strong>-std=C++11</strong>.&nbsp; Do not ask us to change the C++ version; we are compiling against C++ 11.

&nbsp;

<h2>Requirements</h2>
<ol>
<li>You must use <strong>ourvector&lt;T&gt;</strong> (“ourvector.h”) for storing all data. No other data structures may be used.</li>
<li>Each input file may be opened and read exactly once; store the data in ourvector&lt;T&gt; if need be.</li>
<li>You must use binary search to search the spam list, and you must write the algorithm yourself; do not call the built-in binary search function provided by C++.</li>
<li>The # of inserts must be O(N), where N is the # of spam list entries in the input file(s).</li>
<li>The # of accesses must be O(MlgN), where M is the # of emails in the input file(s).</li>
<li>Your main.cpp program file must have a header comment with your name and a program overview. Each function must have a header comment above the function, explaining the function’s purpose, parameters, and return value (if any).&nbsp; Inline comments should be supplied as appropriate; comments like “<em>declares variable</em>” or “<em>increments counter</em>” are useless.&nbsp; Comments that explain non-obvious assumptions or behavior *are* appropriate.</li>
<li>Each command (load, display, check, filter) must be implemented using a function; this implies a complete solution must have at least 4 functions.</li>
<li>No global variables; use parameter passing and function return.</li>
<li>The <strong>cyclomatic complexity</strong> (CCN) of any function may not exceed 15, including main(). This will be reported when you submit on Gradescope, and you’ll be warned if you exceed this threshold.&nbsp; In short, cyclomatic complexity is a representation of code complexity — e.g. nesting of loops, nesting of if-statements, etc.&nbsp; You should strive to keep code as simple as possible, which generally means encapsulating complexity within functions (and calling those function) instead of explicitly nesting code.&nbsp; Here’s an example of simpler code with low CCN:</li>
</ol>
&nbsp;

while (…) {

if (searchFunctionFindsWhatWeNeed(…))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; doSomething();

&nbsp;

next value;

}

&nbsp;

Here’s an example of complex code with high CCN:

&nbsp;

<strong>while</strong> (…) {

<strong>for</strong> (…)&nbsp; // loop to do search

{

if (search condition is met)

{&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>for</strong> (…) // now do something:

{

…

}

}

}&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; next value;

}

&nbsp;

As a general principle, if we see code that has <strong>more than 2 levels</strong> of explicit looping — an example of which is shown above — we will score that code as 0, even if it’s technically correct.&nbsp; The solution is to move one or more loops into a function, and call the function.

&nbsp;

&nbsp;

<h2>Have a question?&nbsp; Use Piazza, not email</h2>
As discussed in the syllabus, questions must be posted to our course Piazza site — questions via email will be ignored.&nbsp; Remember the guidelines for using Piazza:

&nbsp;

<ol>
<li><em><u>Look before you post</u></em> — the main advantage of Piazza is that common questions are already answered, so search for an existing answer before you post a question. Posts are categorized to help you search, e.g. “HW”.</li>
<li><u>Post publicly</u> — only post privately when asked by the staff, or when it’s absolutely necessary (e.g. the question is of a personal nature). Private posts defeat the purpose of piazza, which is answering questions to the benefit of everyone.</li>
<li><u>Ask pointed questions</u> — do not post a big chunk of code and then ask “help, please fix this”. Staff and other students are willing to help, but we aren’t going to type in that chunk of code to find the error.&nbsp; You need to narrow down the problem, and ask a pointed question, e.g. “on the 3<sup>rd</sup> line I get this error, I don’t understand what that means…”.</li>
<li><u>Post a screenshot</u> — sometimes a picture captures the essence of your question better than text. Piazza allows the posting of images, so don’t hesitate to take a screenshot and post; see <a href="http://www.take-a-screenshot.org/">http://www.take</a><a href="http://www.take-a-screenshot.org/">–</a><a href="http://www.take-a-screenshot.org/">a</a><a href="http://www.take-a-screenshot.org/">–</a><a href="http://www.take-a-screenshot.org/">org/</a> .</li>
<li><u>Don’t post your entire answer / code</u> — if you do, you just gave away the answer to the ENTIRE CLASS. Sometimes you will need to post code when asking a question — in that case post only the fragment that denotes your question, and omit whatever details you can.&nbsp; If you must post the entire code, then do so privately — there’s an option to create a private post (“visible to staff only”).</li>
</ol>
&nbsp;

<h2>Grading, electronic submission, and Gradescope</h2>
Your score on this project is based on two factors:&nbsp; (1) correctness as determined by your Gradescope submission, and (2) manual review by the TAs for commenting, style, and approach (e.g. use of functions and efficiency of solution).&nbsp; The entire project is worth 150 points:&nbsp; 100 points for correctness, and 50 points for commenting, style, and approach.&nbsp; In this class we expect all submissions to compile, run, and pass at least some of the test cases; do not expect partial credit with regards to correctness.&nbsp; <u>Example</u>:&nbsp; if you submit to Gradescope and your score is a reported as a 0, then that’s your correctness score.&nbsp; The only way to raise your correctness score is to re-submit and obtain a higher score by passing one or more test cases.&nbsp; You have unlimited submissions on this project assignment.

&nbsp;

Note that the TAs will also review for adherence to requirements; breaking a requirement can result in a final score of 0 out of 150.&nbsp; We take all requirements seriously.

&nbsp;

A bonus of 10% is earned for submitting by the “Bonus” deadline on page 1.&nbsp; Bonus points are accumulated and can be applied to a future project.&nbsp; To earn bonus points, your submission must post before the Bonus deadline, earn a correctness score of 100, *and* meet all project requirements — in this case required # of functions, efficiency, etc.&nbsp; In other words, you cannot submit a correct but inefficient solution and expect to earn bonus points.&nbsp; Bonus points are reserved for early and well-written submissions.

&nbsp;

To submit to Gradescope, you must first create an account; check your UIC email for an invitation to

&nbsp;

Gradescope.&nbsp; If you cannot find this invitation email, post privately on Piazza and we will send another invite; you cannot register yourself.&nbsp; Gradescope is running on Ubuntu Linux, and we are using <strong>g++</strong> with <strong>-std=C++11</strong>.&nbsp; Do not ask us to change the C++ version; we are compiling against C++ 11.&nbsp; Our grading script assumes your program will be found in a single “main.cpp” file; do not create additional .h, .hpp, or .cpp files.&nbsp; You may submit as many files as you want (e.g. the .zip produced by Codio’s Project &gt;&gt; Export as Zip command), but we extract and run only your “main.cpp” file.

&nbsp;

By default, we grade your <strong><u>last</u></strong> submission.&nbsp; Gradescope keeps a complete submission history, so you can <strong><u>activate</u></strong> an earlier submission if you want us to grade a different one; this must be done before the due date.&nbsp; We assume *every* submission on your Gradescope account is your own work; do not submit someone else’s work for any reason, otherwise it will be considered academic misconduct.

&nbsp;

<h2>Policy</h2>
Late work *is* accepted.&nbsp; You may submit as late as 24 hours after the deadline for a penalty of 10%.&nbsp; After 24 hours, no submissions will be accepted.

&nbsp;

All work submitted for grading *must* be done individually.&nbsp; While we encourage you to talk to your peers and learn from them (e.g. your “iClicker teammates”), this interaction must be superficial with regards to all work submitted for grading.&nbsp; This means you *cannot* work in teams, you cannot work side-by-side, you cannot submit someone else’s work (partial or complete) as your own.&nbsp; The University’s policy is available here:

&nbsp;

<a href="https://dos.uic.edu/conductforstudents.shtml">https://dos.uic.edu/conductforstudents.shtml</a> .

&nbsp;

In particular, note that you are guilty of academic dishonesty if you <u>extend or receive any kind of unauthorized</u> <u>assistance</u>.&nbsp; Absolutely no transfer of program code between students is permitted (paper or electronic), and you may not solicit code from family, friends, or online forums.&nbsp; Other examples of academic dishonesty include emailing your program to another student, copying-pasting code from the internet, working in a group on a homework assignment, and allowing a tutor, TA, or another individual to write an answer for you.&nbsp; It is also considered academic dishonesty if you click someone else’s iClicker with the intent of answering for that student, whether for a quiz, exam, or class participation.&nbsp; Academic dishonesty is unacceptable, and penalties range from a letter grade drop to expulsion from the university; cases are handled via the official student conduct process described at <a href="https://dos.uic.edu/conductforstudents.shtml">https://dos.uic.edu/conductforstudents.shtml</a> .

&nbsp;

&nbsp;

&nbsp;

<em>Page </em>

<h2>Appendix:&nbsp; Codio Programming Environment</h2>
Here’s a quick summary of how to get started with Codio.&nbsp; Codio is cloud-based, and accessible via a web browser.&nbsp; It’s platform-neutral and works from any platform, but you must be online to use it.&nbsp; The first step is to create a Codio account and join the class (“CS 251 Spring 2020”):

&nbsp;

<a href="https://codio.com/p/join-class?token=forum-jamaica">https://codio.com/p/join</a><a href="https://codio.com/p/join-class?token=forum-jamaica">–</a><a href="https://codio.com/p/join-class?token=forum-jamaica">class?token=forum</a><a href="https://codio.com/p/join-class?token=forum-jamaica">–</a><a href="https://codio.com/p/join-class?token=forum-jamaica">jamaica</a>

&nbsp;

Be sure to register using your UIC email address, especially since you may be using this account in future CS classes.&nbsp; The above link will provide access to Codio, and the resources associated with CS 251.

&nbsp;

Once you successfully login to Codio, you’ll see the project “<strong>cs251-project01-spam-filter</strong>” pinned to the top of your dashboard.&nbsp; This represents a container-based C++ programming environment — think light-weight virtual machine (VM).&nbsp; When you are ready to start programming, click “Ready to go” and Codio will startup the VM and within a few seconds you’ll have a complete Ubuntu environment at your disposal.&nbsp; In particular, you’ll have access to C++ via the GNU g++ compiler.&nbsp; You also have super-user (root) access, so you can install additional software if you want (“sudo aptget install XYZ”).

&nbsp;

Once I login, I normally split the right-side into 2 windows: the top as my editor pane, and the bottom as my terminal window.&nbsp; This can be done via the View menu, Panels, Split Horizontal.&nbsp; Then click on the bottom window, drop the Tools menu, and select Terminal.&nbsp; Here’s a snapshot showing “student.cpp” open in the editor, and the terminal window open below it:

&nbsp;

&nbsp;

&nbsp;

&nbsp;

For the purposes of project #01, nothing is provided other than a makefile and some input files for testing purposes.&nbsp; Use the File menu to create a new “main.cpp” file, and then open a terminal windows and use the provided makefile to compile and run:&nbsp; type “make build” to compile, and assuming no compilation errors, type “make run” to execute.

&nbsp;

&nbsp;

<em>Page </em>
