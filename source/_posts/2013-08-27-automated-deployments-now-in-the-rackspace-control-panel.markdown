---
layout: post
title: "Automated Deployments Now in the Rackspace Control Panel"
date: 2013-08-27 13:40
comments: true
author: Ziad Sawlha
published: true
categories:
- Deployments
---
The hardest part about using new technology is knowing where to begin. Spending hours sifting through blog posts and documentation to set up a server environment is often enough to extinguish the excitement about a new framework or application. By the same token, it is frustrating to deploy hosting architecture when you are excited to see how your latest code will perform. And no one likes having to do the same things over and over to create consistent testing, staging and production environments.

Deploying your application to the cloud requires expertise in both system administration and development; often, people have expertise in some areas while having gaps in others. The Rackspace Deployments Service was created so we could collect this information and expertise in machine and human readable format and use it to automatically and consistently deploy hosting configurations, frameworks and applications and alleviate some of this stress. <!--More-->
<p><a name="video"></a></p>
{% youtube z3o4iFe8Ucs %}
<p><a name="video"></a></p>
<br />
##Blueprints For Success

Our Rackers are experts in [hybrid cloud][1] hosting, so we drew on this knowledge to create hosting architecture blueprints. The expertise was captured in one place with simple options that you could select to create your hosting environment. From the blueprints, a configuration will be automatically built on those best practices that can be immediately used.

{% img center /images/2013-08-27-automated-deployments/blueprints.png %}

##Like Chef Or Puppet For The Cloud

While [Chef][2] and [Puppet][3] are awesome tools to configure host machines or VMs, they do fall a little short in deploying full environments: you can’t run Chef on a Cloud Load Balancer or Cloud Database. This is where the Rackspace Deployments Service comes in. This system looks at the entire topology and configures your environment (servers, load balancers and databases) in a holistic way, based on best practices, for you to run your application.

{% img center /images/2013-08-27-automated-deployments/configure.png %}


When it is time to configure the application on a host machine, the Rackspace Deployments Service will use Chef or Puppet. Ultimately, our deployment offering is the orchestrator above everything; it ensures that your environment is setup to run the application along with verifying the app is configured correctly.

##Battle Tested Solution

Our [Managed Cloud][4] team has been using the Rackspace Deployment Service to build and scale out customer configurations. This means that you are getting a battle-tested solution that has been working in the real world that is ready for prime time. The Rackspace Deployment Service is actively used by the experts who know how these applications should run and by Rackers who know how to support them if something goes awry.

{% img center /images/2013-08-27-automated-deployments/build.png %}

We are excited to roll out the Rackspace Deployments Service and to get it in the hands of our customers. To get started, [click this link][5] or simply log into the [Rackspace Control Panel][6], click the drop down arrow on the Create Server menu and select Create Deployment.

We currently offer blueprints for Ruby on Rails, PHP, WordPress, Cassandra, Drupal, Magento, MySQL with replication, Django and MongoDB. We’re working on Windows, Node.js, etherpad, and multi-region Cassandra blueprints right now and new ones will be coming frequently. Go [try it out][5]. Let us know what you want to see on the list!

[1]: http://www.rackspace.com/cloud/hybrid/
[2]: http://www.opscode.com/chef/
[3]: https://puppetlabs.com/
[4]: http://www.rackspace.com/cloud/managed_cloud/
[5]: https://mycloud.rackspace.com/#deployments/create
[6]: http://mycloud.rackspace.com/