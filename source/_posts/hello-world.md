---
title: How to Download and Use Hexo
date: 2023-12-26 19:10:21
categories:
- tech
tags:
- Hexo
---

Welcome to my tech blog. In this post, I will guide you on how to download and use Hexo for setting up your personal blog.

## Introduction to Hexo

Hexo is a fast, simple, and highly efficient blogging framework. It parses articles using Markdown or other markup languages and quickly generates static web pages.

## Installation Steps

1. **Install Node.js and Git**  
   Hexo requires Node.js and Git. Make sure they are installed on your computer.

2. **Install Hexo**  
   Use the command 
   ``` bash
    $ npm install -g hexo-cli
    ```
   to install Hexo CLI globally.

3. **Create a New Blog**  
   Execute 
    ``` bash
    $ hexo init blog
    ```
    to create a new blog directory.

4. **Start the Server**  
   Run 
    ``` bash
    $ hexo server
    ```
    or
    ```
    $ hexo s
    ```
    in your blog directory and then preview your blog in a browser.

5. **Create a New Post**  
   Add a new article with 
    ``` bash
    $ hexo new "Your Article Title"
    ```
6. **Generate Static Files**  
   Use 
    ``` bash
    $ hexo generate
    ```
    or
    ``` bash
    $ hexo g
    ```
    to generate static web pages.

7. **Deploy Your Blog**  
   Finally, deploy your blog to a remote server with 
   ```
   $ hexo deploy
   ```
   or
   ```
   $ hexo d
   ```

For more information and tutorials, please refer to [Hexo's Official Documentation](https://hexo.io/zh-cn/docs/index.html).
