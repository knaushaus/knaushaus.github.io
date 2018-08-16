# knaushaus.github.io
Knaus Haus literary journal website

### Structure

- The top-level pages should be few: /about, /submit, /toc. 
- The most complex is a live updating table of contents, /toc/, which lists all the posts in /posts, sorted by issue. 
- The issue content being put into boxes is done automatically, when you make a post and give it the YAML category up top issue1, issue2, etc. 
- Alternative ways to navigate to content:
    - You can also see each individual issue at /category/issue*/ , which is separate page that you can design - say if you want an theme issue. (I could see this starting to get confusing though, if there's a Main TOC. Basically, how many different ways do we need to access content? The fewer seems more straightforward.
    - It is trivial to completely list all content in a single list: /content/, but it is ugly (right now)

### To-do

1. Within an issue, being able to navigate to Next and Previous piece. 
1. Mobile/responsive layout
1. Clean up directory structure. Right now, a piece is made as a blog post and dumped along with all others in /\_posts/
1. There is probably a way to be even more fine-grained about categories, using tags. Say, Fiction versus Essays. And it is certainly possible to list just fiction or essays.
1. Submit facility: just email? forms are neat but a bit annoying to make from scratch, can we bootstrap a google form or something?
1. Content from other magazines to consider: Contributors list, legal terms / disclaimers, dedicated contact page, socials, merch
