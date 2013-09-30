BackChannel007
==============
<p>Backchannel is an online platform where students and instructors come together to learn and teach. It offers a refined Q&A environment along with key features and can model the face-to-face discussion among students and instructors.</p> </p>
<h2>
Get Started
<p>Install missing gems. Execute:</p>

<pre><code>$ bundle install
</code></pre>

<h2>
Features

<ol>
</ol>
<li>Students can create an account by filling out a form, include user name, password, and email address, that comes up on the homepage of the app.</li>
<li>Only registered user can create or reply a post. A category is mandatory to be associated to a post; users can select from categories created by the administrators.</li>
<li>Categories can only be created by administrators.Students are allowed to create and use their own tags for posts.</li>
<li>Any viewer (registered or not) can search by user or content or category or tag, by using the Search box on the posts homepage.</li>
<li>Logged-in ussr can edit/delete their own post/comment.</li>
<li>Administrators are allowed to edit/delete any post/comment</li>
<li>Loggedin user can edit their own profile, include change name/password/email</li>
<li>Administrators can edit/delete students' profiles/account and their own profile/account</li>
<li>Administrators can create other administrators' accounts. Administrators can delete their own account, but not other administrators'</li>
<li>Super administrator can edit/delete any existing account. It is impossible to delete the super administrator.</li>


<ul>
<li>A count of votes for each post/comment is stored in database, and the number of vote will be shown next to the post/comment.</li>
<li>Logged-in usesr can “up vote” any post/comment.</li>
<li>Users cannot vote up their own posts/comment, and each post/comment can not be voted more than once.</li>
</ul>
<li>The “most active” 10 posts are displayed at the top of the post list. “Most active” is determined by the combined number of votes on the posts and comments on that post, as well as time elapsed.</li>
<ul>

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
<li>Rails 3.2.14 (and associated dependencies). </li>
<li>SQLite 3.7.2 (on Windows, place the DLL and DEF file in C:\Ruby192\bin)</li>
</ul>

