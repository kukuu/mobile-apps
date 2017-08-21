# Understanding front-end vs back-end performance metrics for mobile apps

Discussions of mobile performance tend to focus on optimizing for different devices, browsers, operating systems, and carriers. These are important topics, but what if you looked at performance from an end-user perspective? Users care about things like mobile app download time, page load speed, image quality, flow of actions, security, and overall user experience.

For your mobile app to succeed, you need to consider both the view of your application from the perspective of the end user (front end) and the factors that affect performance at the back end and in turn influence the end-user experience.

## Front end performance-related metrics include:

1. Application response time

Users have little patience for slow apps. Acceptable mobile response times tend to be in the two-to-three-second range. If your mobile app does not perform to this level, users will simply move on to something that does, leaving your products and services behind.

There are several things you can do to optimize your mobile app performance. Examples include:

i. Having fewer unique objects on the page so your app makes fewer HTTP requests

ii. Having fewer URL redirects

iii. Removing components like Flash

iv. Reducing cookie size


When building an application, consider different types of responses: How long does it take for your application to load, serve up images, or respond to the user's input? Do these response times vary depending on how or where your mobile app is used?

Also consider how much of the data (and time) is traversing the network via request and reply messages. What impact does that have on mobile app performance?



2. Screen rendering times

It's not good enough to have great response times if your mobile app does not render well. Content, images, and animations developed on or for desktop screens do not render well on mobile screens. Ask yourself:

i. What is the mean time to rendering?

ii. How well does your application render in different screen sizes and different operating system environments?

iii. How well adjusted are the dimensions of a web page to the width of the mobile device screen?

iv. Are font sizes consistent?

v. Do your users have to zoom in or zoom out to read content and interact with your application?

vi. Are images scaled down properly to match how they will be displayed on the mobile device?

vii. Avoiding CSS expressions can help improve screen-rendering times by limiting the frequent evaluations that are otherwise involved each time a page is resized or scrolled or when the user manipulates the screen. Similarly, referencing images in HTML instead of CSS can speed up rendering times on your mobile app.


3. Memory, battery, and data plan usage

Users tend to dislike mobile applications that consume resources such as CPU, memory, and battery. Mobile devices are much more powerful than they were a few years ago. Even so, they have somewhat constrained resources compared to desktop devices. If your mobile app consumes a lot of CPU, drains battery power, or is very chatty; chances are that users will simply jettison your app or stop using it altogether.

4. App crashes

Crashes are not acceptable, nor can I imagine a business embracing a failure rate as acceptable. An app crash is the ultimate front-end performance failure, especially for end users in the wild utilizing your products and services.

How often does your application crash? What percentage of your users has suffered a crash? How often does your application hang or encounter a failed network request?




## Back-end performance metrics include:

1. Server response time

Your mobile app might be well designed for look and feel and usability, but how does your mobile app impact the back-end infrastructure supporting your app? If the back-end server response time is slow, your app will be slow.

Several factors can contribute to slow server response times, including a lack of server resources, overloaded servers, memory leaks that impact the memory on the server, and the speed of the network connection that your end users are using your mobile app.


2. Time to first byte (TTFB)

One good indicator of server response time is the time to first byte. TTFB basically measures the time from when a user first initiates a web request to when the first byte of the requested data appears on the end user's device. Keeping an eye on such issues is critical to ensuring that application response times match users' expectations.

You can measure TTFB by determining when the first byte clears your firewall, but for true metrics, you should emulate end-user devices.


3. Number of HTTP calls


The more requests that your application makes with a back-end server in order to complete a user request, the more the opportunities for your app to slow down or crash. So reducing the number of calls or requests that your application makes with back-end servers and services when a user interacts with your application is one way to improve server response times.

Developers can take other steps as well. 

i. For example, avoiding empty SRC or HREF tags eliminates the need for the server to waste computing cycles on pages that will not be viewed. 

ii. Avoiding HTTP 404 errors and the use of cookies for static components are other ways of ensuring that server resources are not wasted.

iii. Where cookies are needed for authentication and personalization purposes, it is best to keep them small to minimize impact on server response times.


4. TCP connection times

Wireless and mobile networks have significantly less bandwidth, more latency, more packet loss, and more jitter than their wired counterparts, so it is more important to manage the connections that your apps make to the back end and capacity.

Opening up too many connections in a mobile app can create serious resource management issues. It is better to make fewer TCP connections but keep them open longer to reduce traffic and the time it takes to establish new connections.

5. DNS Lookup

DNS lookups take a lot longer to perform on a mobile network than on a traditional wired network and contribute significantly to application performance issues. A DNS lookup for an IP address on a mobile network takes between 120 and 400 or more milliseconds, a period during which the browser cannot download anything else.

A single mobile DNS lookup can have the same effect as downloading multiple object requests. So reducing DNS lookups can boost application performance.



# Mobile App Development Trends 

1. Security is a Key Area

The large number of online payment modes has made security an important trend in the mobile app world. Advanced encryption, SSL, and HTTPS ensure that e-commerce remains trustworthy and safe. The development community is anticipating an increase in maintenance projects involving storage security, privacy enforcement, secure logging, and information confidentiality. Identity and data theft pose a clear and present danger, and the best mobile application development company does not cut corners while ensuring security and privacy of network connections and data storage.


2. Android Instant Apps

The traditional approach to mobile apps involved downloading and installing freeware/shareware followed by purchase of the comprehensive app with a license. Monetization has also been achieved using other marketing and advertising channels. The new forth commingtrend is instant apps pioneered and promoted by Google Android smartphones. All you need is the Android phone and a high-speed internet connection to search and play the app without installation. The design and animation of these trendy instant apps ensure a beautiful experience for the users.


3.  Smart Apps and Augmented Reality

Utility apps have their value, but smart apps with augmented reality (AR) are the future. The AR apps have a wide variety of uses, and they ensure a composite view by superimposing the user's reality with computer-generated virtual images. The customer interactivity and engagement are enhanced, thereby improving your business brand and sales productivity.  AR apps are also useful in education, location hunting, GPS, online marketing, and instant messaging.


4. Rapid Deployment For Larger Businesses

Business processes have relied on HTML-based micro-apps that assisted in simple, mono-functional, and targeted operations. The multi-featured enterprise mobile apps have been efficient in project management and collaboration. It has become trendy for mobile app developers to rely on Agile development, continuous delivery, and deployment strategies to provide advanced mobile apps with numerous enhanced features. This trend is bound to improve the quality and performance of business organizations.


5. Swift

Apple iOS mobile apps developed using Swift programming language have become fashionable in recent times. The native apps, requiring iPhones, make use of Swift's advanced programming features to develop high-performing apps overcoming stiff competition from Objective-C, Perl, and JavaScript.


6. World Of Big Data

Data mining and big data have transformed the landscape of information gathering and data analytics. Mobile sensors, social networking data, and user flows facilitate exploration of innovative quality and security assessments for big data in the context of mobile apps.


7. Innovative Mobile Payments

New mobile payment options for m-commerce are being unleashed by the proprietary brands such as Apple, Microsoft, and Samsung. Credit cards, debit cards, and PayPal are being replaced by Google and Microsoft Wallets as well as Apple Pay and Samsung Pay.


8.  Cloud And Internet

Powerful mobile apps with direct cloud interaction are set to revolutionize the smartphone industry. The phones will require less internal memory and the cloud-based mobile app traffic has seen a sharp rise. The application areas include entertainment, browsing, messaging, as well as smart apps for businesses. The rules of UI/UX are bound to change with the seamless integration of smartphones, smart devices, cloud storage, and instant apps. The "internet of things" is not just real, it is big and bound to be a trendsetter.



