Find my weekly posts here - https://jeenogeorge.github.io

Follow along - https://chadbaldwin.net/2021/03/14/how-to-build-a-sql-blog.html

# To make a new post

1. Navigate to the _posts folder on GitHub
2. Click Add file > Create new file
3. Name your file 2024-01-31-your-new-blog-post.md
4. Set the title of your blog post by using a markdown header
5. Write this as the first line ## This is my first blog post
6. Add some content…write some random things, whatever you want
      Throw in a code block (code blocks are created by surrounding your code snippet with three backticks at each end and an optional “language hint”), copy paste this in:Copy
       ```tsql
       SELECT *
       FROM sys.tables
       WHERE [name] = 'SomeTable'
       ```

Important note, if you’re using T-SQL code, make sure to use the tsql tag. This will tell your site that you want to use the SSMS style formatting.
Click the Preview tab so you can see what it looks like so far.
