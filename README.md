BackChannel007
==============
<p>Backchannel is an online platform where students and instructors come together to learn and teach. It offers a refined Q&A environment along with key features and can model the face-to-face discussion among students and instructors.</p> </p>
<h2>
Get Started
<p>Execute:</p>

<pre><code>$ bundle
</code></pre>

<p>And then execute:</p>

<pre><code>$ rails server
</code></pre>

<h2>
Features

<ol>
</ol>
<li>Anyone can create an account by filling out a form that comes up on the homepage of the app.</li>
<li>Any user with an account can post. A category must be associated with each post; students can select from categories created by the administrator. Students are also welcome to create and use their own tags.</li>
<li>Anyone (account or not) can search by user or content or category or tag, by using the Search box on the homepage. Also, (s)he can see all posts associated with that category when (s)he searches by category. This way if the category is homework1 user can see
all posts associated with homework1.</li>
<li>Any logged­in user can edit/delete their own post/comment.</li>
<li>Any logged­in user can “up vote” any post or comment.
<ul>
<li>The system maintains a count of votes for each post.</li>
<li>When the system displays a post or comment, next to the post or comment should be the number of votes.</li>
<li>You cannot vote up your own posts or comment.</li>
<li>You cannot vote up the same post or comment more than once.</li>
</ul>
<li>Any logged­in user can reply to a post (but not to a reply; i.e., only to a depth of 1).</li>
<ul>A user can also vote up a reply (by someone else).</ul>
<li>The “most active” questions are displayed at the top. “Most active” is determined by the combined number of votes on the posts and comments on that post, as well as time elapsed. For example, you can assign each question a fixed weight, which decays over time. Use this weight along with the number of votes to calculate the final metric which decides the most active questions. Feel free to design your own metric, along these general lines. For example, you may wish to use a metric which eventually decays to 0, at which time the question is hidden.</li>
<li>If a user logs in as an admin, (s)he sees a different interface from what non­admins see.</li>
<ul>
<li>a. There should be a ‘super’ admin in system that his role of admin cannot be
removed. There should be code to handle that this user cannot be deleted</li>
<li>b. Administrators can create other admin accounts.</li>
<li>c. An administrator can delete his/her own account, but no one other admin’s.</li>
<li>d. Administrators can see the list of users with their credentials</li>
<li>e. Administrators can delete
<ol>
<li>posts</li>
<li>users</li>
</ol>
</li>
<li>f. View reports on post activity during certain time period, including number of votes
for each post such that it is possible to use this report to assign grades. For
example, an admin can view reports from past 10/15/... days.</li>
<li>g. An administrator can create categories for posts. </li>
</ul>

<h2>
Testing
<p> Test::Unit is used in this app </p>

<h2>Credit
<p> Members in this projuect are:</p>
<ul>
<li>Xianyu Wu</li>
<li>Yefei Huang</li>
<li>Hongwei Wang</li>
</ul>

<h2>
Supported Software Versions:
<p>The following versions are required</p>
<ul>
<li>Ruby 1.9.3</li>
<li>Rails 3.x (and associated dependencies). </li>
<li>SQLite 3.7.2 (on Windows, place the DLL and DEF file in C:\Ruby192\bin)</li>
</ul>

