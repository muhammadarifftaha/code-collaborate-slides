---
theme: apple-basic
image: "/bg.jpg"
layout: intro-image
title: Welcome to CodeColaborate
author: Muhammad Ariff Taha
download: true
transition: fade-out
exportFilename: CodeCollaborate
export:
  format: pdf
fonts:
  # basically the text
  sans: "Poppins"
  # use with `font-serif` css class from windicss
  serif: "Robot Slab"
  # for code blocks, inline code, etc.
  mono: "Fira Code"
---

<div class="absolute top-10 left-10">
  <p class="font-size-3 !mb-0">
    Muhammad Ariff Taha
  </p>
  <p class="font-size-2 !mt-0">
    For Engineering Weekly - 12/09/2023
  </p>
</div>

<div class="absolute bottom-10 left-10">
  <h1 id="cover-title">Aleph's CodeCollaborate</h1>
  <h3>The engineering team's encyclopedia and knowledge base</h3>
</div>

<!-- Hello, My name is Taha and today I'll be talking about CodeCollaborate. Take notes and write down your questions and we'll address them at the end of the presentation -->

---
layout: image-left
image: "/alephdevhub.png"
transition: slide-left
class: text-left
preload: false
---

<div class=" p-4">
<h1 class="text-blue">Table of Contents</h1>

<ul>
  <li 
    v-motion
    :initial="{ x : 100, opacity : 0 }"
    :enter="{ x: 0, opacity: 1, transition: { duration: 1000 }}"
    > What is CodeCollaborate?</li>
  <li
    v-motion
    :initial="{ x : 100, opacity : 0 }"
    :enter="{ x: 0, opacity: 1, transition: { duration: 1000 ,delay : 200}}"
    >CodeCollaborate Features and How to use them</li>
    <li
    v-motion
    :initial="{ x : 100, opacity : 0 }"
    :enter="{ x: 0, opacity: 1, transition: { duration: 1000 ,delay : 600}}"
    >  How to contribute to CodeCollaborate</li>
</ul>
</div>


<!-- Today, we will talk about what is CodeCollaborate, its features (current and future/planned), how to use it and how to contribute to it. -->
 

---
layout: default
transition: fade-out
---

<div className="w-full h-full flex flex-col justify-center items-start">
  <h1>What is CodeCollaborate?</h1>

  <p class="w-2xl">CodeCollaborate is place where we can share knowledge and information about our
    engineering team. It is a place where we can share our knowledge and experience
    with each other.
  </p>

  <p>Uses:</p>
  <ul>
    <li>Knowledge Sharing</li>
    <li>Standardising Code and Practices</li>
    <li>Improve Skills & Develop New Ones</li>
    <li>References</li>
  </ul>
</div>

<!-- 

Knowledge sharing is a key part of our engineering culture.

Engineers and engineering as a whole can only improve if we share and support each other. 

I hope we can fully utilise this platform for everyone's benefit.

CodeCollaborate will be our one stop destination to share knowledge with our peers. 

In the future we hope to also implement standars across all our projects.

This will not only benefit us here, where we can have multiple projects,

some with similar requirements, but also those in the future. 

If we ever decide to continue our journey elsewhere, at least handover doesn't have to be difficult 

We can also use this platform to improve our skills and develop new ones.

For example, recently I've noticed gaps in my knowledge while helping out with other projects.

I might not know where to find the information I need, I would probably have to put in effort to find it.

I've been trying to fill those gaps by reading up on the topics and sharing what I've learnt with the team.

And I can share what I've learnt with the team through CodeCollaborate, so you don't have to struggle as I did.

Lastly, it can also be a platform for references for when we need to look back on something we've done before.

-->

---
transition: slide-up
---

<div class="w-full h-full flex flex-col justify-center items-start">
  <h1 class="heading">Features</h1>

<div >
  <p class="w-2xl">CodeCollaborate is built on top of <a href="https://nextjs.org/">Next.js</a>. A React framework with server side rendering capabilities. It is also built with <a href="https://tailwindcss.com/">TailwindCSS</a>, a utility-first CSS framework.
  </p>

  <ul>
    <li>Sections</li>
    <li>Links</li>
  </ul>
</div>

  </div>

<!-- 
  CodeCollaborate is built on top of Next.js and uses TailwindCSS for styling.

  It is hosted on Vercel and uses MongoDB Atlas for its database.

  Currently, CodeCollaborate has 2 main features, Sections and Links.
 -->
---
layout: default
transition: slide-up
---

<div class="w-full h-full flex flex-col justify-center items-start p-4">
  <h1 class="heading">Features - Section</h1>

<div class="grid grid-cols-2 gap-2 grid-rows-2 grid-justify-center grid-items-center">
  <img src="/sections.png" class="row-span-1 w-80" />
  <img src="/edit-sections.png"  class="row-span-2 w-100" />
  <img src="/create-sections.png" class="row-span-1 w-80" />
</div>

</div>

<!-- 
  Sections are where we can categorise our content.
  
  You can add a new Section by clicking on the "Add Section" button.

  Each section has a title and a description.

  Title is mandatory while description is optional.

  The slug is automatically generated from the title and will be used in the URL.

  The button can be found on the home page.

  You can also edit the section by clicking on the "Edit" button.

  On the edit screen, you can edit, deleted and add links attached to the section.

 -->

---
layout: default
transition: slide-up
---

<div class="w-full h-full flex flex-col justify-center items-start  p-4">
  <h1 class="heading">Features - Links</h1>

<div class="grid grid-cols-2 gap-2 grid-rows-2">
  <img src="/links.png" class="row-span-1" />
  <img src="/add-links.png"  class="row-span-2" />
</div>

</div>


<!-- 

  Links are where we can add our content.

  You can add a new Link by clicking on the "Add Link" button.

  Each link has a title, url, section and an image.

  All fields are mandatory.

  The image is currently hosted on Cloudinary.

  You can also edit the link by clicking on the "Edit" button.

 -->

---
layout: default
transition: slide-up
---

<div class="w-full h-full flex flex-col justify-center items-start  p-4">
  <h1 class="heading">Features - Future</h1>

  <ul>
    <li>Posts</li>
    <li>User Accounts
      <ul class="!mt-0">
        <li>Authentication & Authorisation</li>
        <li>User Contribution</li>
        <li>Comments & Discussion</li>
      </ul>
    </li>
    <li>Search with AI</li>
    <li>Improved UX
      <ul class="!mt-0">
        <li>Light/Dark Mode</li>
        <li>Design Improvements</li>
      </ul>
    </li>
  </ul>

</div>


<!-- 

These are some of the features that we are planning to implement in the future.

Firstly, we want to have a blog like feature where we can post articles and tutorials.

This will be useful for sharing knowledge and experience that can't be shared through links.

Ideally, we want to have a login system where only Alephians can access CodeCollaborate.

This will allow us to have more control over the content and who can access it as well as display user contributions.

Which means Links and Posts can be attributed to the user who created them.

We also want to have a search feature where you can search for content and possibly AI integration to improve the search results.

Lastly, we want to improve the UX of CodeCollaborate.

We want to have a light and dark mode for those who prefer one over the other.

We also want to improve the design of CodeCollaborate to make it more appealing and easier to use.

This is where we need your help.

-->

---
layout: default
transition: fade
---

<div class="w-full h-full flex flex-col justify-center items-start p-4">
  <h1 class="heading">How to contribute</h1>

  <ul>
    <li v-click>Ideas</li>
    <li v-click>Code</li>
    <li v-click>Improvements</li>
    <li v-click>Feedback</li>
  </ul>


</div>

<!--
How to contribute to CodeCollaborate?

You can contribute to CodeCollaborate in many ways.

Ideas.

If you have any ideas on how to improve CodeCollaborate, you can share them with us.

Code.

If you don't have any ideas, but you want to contribute, you can help us with the code.

We have a list of features and improvements that we want to implement.

Improvements.

If you think there are things that can be improved, better implementation, better design, etc.

Feedback.

Lastly, if you have any feedback, share. 

We want to make CodeCollaborate as useful as possible for everyone.
-->

---

<div class="w-full h-full flex flex-row justify-center items-start p-4">
  <div class="w-1/2 flex gap-4 flex-col">
    <h1 class="heading">Discord Server</h1>
    <ul>
      <li>Discuss</li>
      <li>Help Desk</li>
      <li>Share</li>
      <li>Connect</li>
    </ul>
  </div>
  <div class="flex flex-col justify-center items-center">
    <p>Scan to Join the Aleph MY Engineering Server</p>
    <img src="/AlephMyEngineering.svg" class="w-70 mx-auto" /> 
    <p>Or visit <a href="https://discord.gg/hhD5BfFm">https://discord.gg/hhD5BfFm</a></p>
  </div>
</div>

<!-- 
We also have a Discord server for the engineering team.

You can join the server by scanning the QR code or by visiting the URL.

We can use the server to discuss, ask for help, share and connect with each other.

We have prepared some roles for you to choose from. 

You can choose the roles that describes you best and you will be notified when there are updates.

We hope that the discord server will be a place where we can connect with each other and share our knowledge and experience.

It will also help engineers in the same project to communicate and collaborate with each other through the dedicated project channels.

If your role is not listed, or you want to add a new role, create a new channel or category, implement a new feature, bots, etc, you can contact an admin to have it added.
-->

---

<div class="w-full h-full flex flex-row justify-center items-center p-4">
 <div class="w-1/2 flex gap-4 flex-col">
  <h1 class="heading">Thank you</h1>
  <p>Thank you for your time.</p> 
  <p>Any Questions?</p>
  </div>

  <div>
    <p>Scan to access CodeCollaborate</p>
    <img src="/CodeColaborate.svg" class="w-70 mx-auto" /> 
    <p>Or visit <a href="https://alephdevhub.vercel.app">alephdevhub.vercel.app</a></p>
  </div>
  
</div>

<!--

Thank you for your time.

I hope you found this presentation useful and maybe even enjoyable.

We hope that CodeCollaborate will be a useful tool for everyone.

Any Questions?

-->
