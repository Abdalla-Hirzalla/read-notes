# Local Storage 

### In the beginning:
 there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.) IE does not present any form of permissions dialog, and there is no allowance for increasing the amount of storage available.

### Intro HTML5 STORAGE :
 What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5
 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.


### BEYOND NAMED KEY-VALUE PAIRS:
**COMPETING VISIONS**
While the past is littered with hacks and workarounds, the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage is… how shall I put it… well, there are competing visions.

# FURTHER READING:


**HTML5 storage:**
- HTML5 Storage specification
- Introduction to DOM Storage on MSDN
- Web Storage: easier, more powerful client-side data storage on Opera Developer Community
-
 **Early work by Brad Neuberg et. al. (pre-HTML5)**
- Internet Explorer Has Native Support for Persistence?!?! (about the userData object in IE)
- Dojo Storage, part of a larger tutorial about the (now-defunct) Dojo Offline library
- dojox.storage.manager API reference
- dojox.storage Subversion repository
- Web SQL Database:

**Web SQL Database specification**
- Introducing Web SQL Databases
- Web Database demonstration
- persistence.js, an “asynchronous JavaScript ORM” built on top of Web SQL Database and Gears

**IndexedDB:**
- Indexed Database API specification
- Beyond HTML5: Database APIs and the Road to IndexedDB
- Firefox 4: An early walk-through of IndexedDB