# Foundational Flask: Creating Your Own Static Blog Generator
### Christopher Roach


If you're a web developer, you've no doubt heard of Django&#8212;the go–to web development framework for Python. While Django is a superb framework for developing complex web applications, it can be slightly cumbersome when developing something a bit smaller. That's where knowing a good micro-framework can come in handy, and [Flask][flask] fits that use case perfectly. Not content with being just a micro-framework for small web apps, Flask&#8212;built atop the powerful [Werkzeug][werkzeug] WSGI library&#8212;has the ability to grow with the complexity of your app, making Flask, in many cases, the only framework you'll ever need. Join [Christopher Roach][croach] as he shows you how to use the Flask micro-framework through the creation of a simple static blog generator.

## Chapter 1 Getting Started

### 1 - Introduction ()

We begin by discussing the role of micro-frameworks and why you should learn one if you already know a "full power" framework such as Django. We'll also discuss how Flask can grow with your app's complexity and may, therefore, be the only framework you need to know. Finally, this lesson will point the user to the Python Power Tools video on virtuanenv and virtualenvwrapper.

### 2 - Hello Flask ()

In this lesson, we'll install Flask and create our very first "Hello World" application.


---

## Chapter 2 Creating the Blog

### 3 - Templates

In this episode we create our first template and discuss about template inheritance.

### 4 - Add the Post Class

In this episode, we add a simple Post class to abstract away the details of the underlying text file.

### 5 - Debugging Flask Applications

In this episode, we take a look at the built in Werkzeug Debugger and its use in debugging Flask applications. In addition we also take a quick look at using the pdb/ipdb for more in-depth debugging sessions.

### 6 - Add Post Metadata

In this episode, we add support for YAML formatted meta data in the header of the blog post markdown files.

### 7 - Create a Custom Jinja Filter

In this episode, we create a custom Jinja filter for formatting the date in our templates.

### 8 - Add the index.html Template

In this episode, we create the index.html template and update the Post class with a url property.

### 9 - Add a Posts Class

In this episode, we add a Posts class that's responsible for loading all of the blog posts for our app.

### 10 - Add the SortedDict Class

In this episode, we add the SortedDict class to make sure that all of our blog posts are in properly sorted.

### 11 - Handling Static Files

In this episode, we'll see how to serve static files and we'll add syntax highlighting for code samples in our blog posts.

---

## Chapter 3 Loose Ends

### 12 - Generating a Feed

This episode demonstrates how easy it is to use the underlying Werkzeug library within a Flask app by using the [AtomFeed][atom] class to generate a Atom feed for our blog.

### 13 - Generate the Static Website

In this episode, we use the Frozen Flask extension to generate our static website.

### 14 - Configuration

In this episode, we explore how configuration in Flask works and we clean up our Blog and Post classes a bit by adding some configuration to our application.

### 15 - Syntax Highlighting

In this episode, we add syntax highlighting with pygments.

---

## Chapter 4 Deployment and Conclusion

### 16 - Deployment

In this episode, we'll see one way that we can deploy our new blog for free with Github pages.

### 17 - Conclusion

Well, that wraps up this course. If you've followed along with the entire course, you should have both a working knowledge of how to create web applications with Flask and a fully functioning static blog generator that you can put to immediate use. I hope you all have enjoyed this series, and, if you have, keep on the lookout for my next series where we'll dig a bit deeper into Flask and create a little more standard database-backed website. I hope to see you all in the next course!



[flask]: http://flask.pocoo.org
[werkzeug]: http://werkzeug.pocoo.org
[croach]: http://christopherroach.com
[atom]: http://werkzeug.pocoo.org/docs/contrib/atom/
