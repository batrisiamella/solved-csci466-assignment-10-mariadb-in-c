Download Link: https://assignmentchef.com/product/solved-csci466-assignment-10-mariadb-in-c
<br>
For this assignment, you will be writing a C/C++ program that prints reports on the books found in the henrybooks database from our MariaDB server.

<h2>Requirements</h2>

Your program will show a menu with three options for reports to show. The user will choose an option, and your program will use the MariaDB C API to run the necessary queries, displaying the results, neatly formatted, in the terminal.

<ol>

 <li><strong>BookList</strong>: For each book, print the title, the author(s), and the cost. Do not assume that a book will be written by a single author. Use a subquery to accomplish this. Sort the authors for each book based on their Sequence.</li>

 <li><strong>Author Search</strong>: Prompt the user for the name of an Author. Print a report showing all books by authors whose first or last names match the user-supplied name. For each of the books found, show a line in your output with the book code, the title, the name of the author that matched your search, and the price; then show individual lines (indented below the original line) for each branch, each showing how many of the current book are on hand, or a single line indicating that it is out of stock everywhere if no branches have any on hand. Branches should be displayed as their names and not as their numerical identifiers, in alphabetical order.</li>

 <li><strong>TitleSearch</strong>: Same as the author search in feature 2, but search by title instead of by author. For the author field, use the first author only (by sequence number).</li>

</ol>

There should also be an option to quit. After performing whichever option is chosen (obviously except for the one to quit), your program should show the menu again and allow the user to choose a new option to run.

<h2>Notes</h2>

<ul>

 <li>The grading for this will be done by compiling and running this program on turing and/or hopper. If your program does not compile and run properly on turing and hopper, you will not receive credit, so make sure to test it there.</li>

 <li>If your program needs any flags other than the ones used in the examples of gcc/g++ in the slides in order to compile, you need to let us know when you submit.</li>

 <li>Don’t forget to document your code.</li>

 <li>It is <em>not </em>a requirement that every feature be implemented with a single query. You can break the tasks down into smaller queries if you find it makes solving the problem easier.</li>

 <li>As always, you should be submitting your own work. Do not try to cheat or plagiarize other people’s programs.</li>

</ul>