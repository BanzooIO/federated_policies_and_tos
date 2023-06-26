{{ THIS DOCUMENT IS PROVIDED AS-IS. IT HAS NOT BEEN REVIEWED BY LAWYER. IT IS PROVIDED AS A BASIC FRAMEWORK THAT ONE WOULD SUPPLY TO THEIR LAWYER TO PROVIDE CONTEXT }}

This privacy policy describes how {{your_instance_name}} ("{{your_instance_name}}", "we", "us") collects, protects and uses the personally identifiable information you may provide through the {{your_instance_name}} website or its API. The policy also describes the choices available to you regarding our use of your personal information and how you can access and update this information. This policy also describes how your engagement (profile information, posts, comments, direct messages, votes) is distributed and accessed. This policy does not apply to the practices of companies or organizations that {{your_instance_name}} does not own or control, or to individuals that {{your_instance_name}} does not employ or manage.

By joining this service you are engaging in, and contributing to, the very exciting and emerging space of free open communication on the internet. **HOWEVER YOU ARE JOINING WITH THE UNDERSTANDING THAT THIS SERVICE IS RUNNING ON VERY EARLY RELEASE SOFTWARE AND SHOULD BE CONSIDERED ENTIRELY EXPERIMENTAL. ALTHOUGH ALL REASONABLE PRECAUTIONS HAVE BEEN TAKEN TO MAINTAIN THE SECURITY OF YOUR PERSONAL DATA, WE CAN NOT GUARANTEE THAT THE SOFTWARE OR THIS INSTANCE CONFIGURATION IS FREE FROM DEFECT THAT MAY RESULT IN THE EXPOSURE OF ANY OR ALL SUBMITTED DATA.**

**You also understand that there are controls to prevent the distribution of your email and IP address. However due to the nature of federated services, all of your *engagement* (your profile;posts;comments;messages;votes) on this platform should be considered public. We feel that proper precautions should be taken by the user regardless of what services they choose to use to engage in internet discourse, but it is highly recommended that you do not share any information on {{your_instance_name}}, or the Lemmy platform, that could in any way personally identify you.**


# **What information do we collect?**



* **Basic account information**: If you register on this server, you may be asked to enter a username, an e-mail address and a password. You may also enter additional profile information such as a display name and biography, and upload a profile picture. The username, display name, biography, profile picture are always listed publicly.
* **Posts, comments, subscribing, voting, and other public information**: Communities you subscribe to may be disclosed to the admins of remote instances. Although user vote records are not accessible through the UI, this should also be considered public, and there are conditions which result in it becoming publicly viewable. When you post, the date and time is stored as well as the application you posted from. Posts and comments may contain media attachments, such as pictures and videos. Posts and comments are available publicly. Anything displayed on your profile is also publicly available information. Your comment history is available publicly. Your posts are delivered to the communities they are posted on, in some cases it means they are delivered to different servers and copies are stored there. When you delete posts, this is likewise broadcast to other instances, however there is no guarantee that the removal request will be respected, or even broadcast to all instances. There are conditions that may result in copies of your profile, posts, comments, voting record not being removed or editable when requesting so from your local instance. This service interoperates with other federated services such as Mastodon; the format, interpretation, and display of your engagement may function differently than it does on Lemmy. \
 \
**In essence, your IP address and email remain private to this local instance, however due to the nature of federated services all engagement should be considered public and you are responsible for taking appropriate precautions in how you engage. Do not share any sensitive or information you do not want public over Lemmy.** 
  
* **Direct messages**: All messages are stored and processed on the instance. In some cases it means they are delivered to different instances and copies are stored there. We make a good faith effort to limit the access to these direct messages to only authorized persons, but other instances may fail to do so. Therefore it's important to review the instances of users you are engaging with. **Please keep in mind that the operators of the instance and any receiving instance may view such messages**, and that recipients may screenshot, copy or otherwise re-share them. **Do not share any sensitive information over Lemmy.**
* **IPs and other metadata**: When you log in, we record the IP address you log in from, as well as the name of your browser application. The latest IP address used is stored for up to {{maximum_retention_user_ip}}. We also may retain server logs which include the IP address of every request to our server.


# **What do we use your information for?**

Any of the information we collect from you may be used in the following ways:



* To provide the core functionality of Lemmy. You can only engage with other people's content and post your own content when you are logged in. For example, you may subscribe to other communities for content discovery.
* To aid moderation of the community, for example comparing your IP address with other known ones to determine ban evasion or other violations.
* The email address you provide may be used to send you information, notifications about other people interacting with your content or sending you messages, and to respond to inquiries, and/or other requests or questions.


# **How do we protect your information?**

We implement a variety of security measures to maintain the safety of your personal information when you enter, submit, or access your personal information. Among other things, your browser session, as well as the traffic between your applications and the API, are secured with SSL, and your password is hashed using a strong one-way algorithm. 

We are disclosing that Lemmy currently does not support SSL for PostgreSQL. This instance has mitigated this security risk by {{running the PostgreSQL service on the same host as the instance backend, and has blocked all incoming and outgoing network connections to the PostgreSQL service **OR** hosts the PostgreSQL database on a separate server and connects via a secure tunnel. All incoming and outgoing network access to the PostgreSQL server outside of this secured tunnel has been blocked}}

{{add any additional hardening your instance employes to ensure the security of user data, backup policies, etc}}


# **What is our data retention policy?**

We will make a good faith effort to:



* Retain server logs containing the IP address of all requests to this server, in so far as such logs are kept, no more than {{maximum_retention_request_logs}}.
* Retain the IP addresses associated with registered users no more than {{maximum_retention_user_ip}}.

You may irreversibly delete your account at any time. **However, this does not guarantee all instances will be notified or respect the deletion of your public data.**

{{provide relevant backup retention policies}}


# **Do we use cookies?**

Yes. Cookies are small files that a site or its service provider transfers to your computer's hard drive through your Web browser (if you allow). These cookies enable the site to recognize your browser and, if you have a registered account, associate it with your registered account.

We use cookies to understand and save your preferences for future visits.


# **Do we disclose any information to outside parties?**

We do not sell, trade, or otherwise transfer to outside parties your personally identifiable information. This does not include trusted third parties who assist us in operating our site, conducting our business, or servicing you, so long as those parties agree to keep this information confidential. We may also release your information when we believe release is appropriate to comply with the law, enforce our site policies, or protect ours or others rights, property, or safety.

Your public content may be downloaded by other servers in the network. Your public and community posts are delivered to the servers where the community resides, and direct messages are delivered to the servers of the recipients, in so far as those communities or recipients reside on a different server than this.

When you authorize an application to use your account, depending on the scope of permissions you approve, it may access your public profile information, your subscription list, all your posts, and your voting history. Applications can never access your e-mail address or password from the API, however it may be required to give access to your account (ie. logging in).


# **Site usage by children**

If this server is in the EU or the EEA: Our site, products and services are all directed to people who are at least 16 years old. If you are under the age of 16, per the requirements of the GDPR (General Data Protection Regulation) do not use this site.

If this server is in the USA: Our site, products and services are all directed to people who are at least 13 years old. If you are under the age of 13, per the requirements of COPPA (Children's Online Privacy Protection Act) do not use this site.

Law requirements can be different if this server is in another jurisdiction.


---

This document is CC-BY-SA. Originally adapted from the [Mastodon privacy policy](https://mastodon.social/privacy-policy), which was originally adapted from the [Discourse privacy policy](https://github.com/discourse/discourse).
 
