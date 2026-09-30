# WordPress VPS hosting: What to look for, how much you actually need, and where LisaHost fits

WordPress VPS hosting makes sense when shared hosting is starting to feel cramped but you do not want to pay managed WordPress prices for features you may not use. The catch is that a VPS gives you the server, not a magic button that turns server administration into someone else’s problem.

That distinction matters more than the number of CPU cores on a product page.

For WordPress today, the official baseline is PHP 8.3 or newer, MariaDB 10.11+ or MySQL 8.0+, and HTTPS. WordPress also recommends Apache or Nginx, although either a properly configured server can run the software.

LisaHost is relevant here because its catalog is built around VPS products with KVM virtualization, public IPv4 addresses, several network routes, and configurations ranging from very small 1-core servers to much larger instances. It does **not** market a conventional WordPress-specific managed hosting product, so you should think of it as a VPS on which you install and maintain WordPress rather than as a turnkey WordPress platform. Its own help center includes Linux administration material and SSH connection guidance, which fits that model.

## What WordPress VPS hosting really gives you

A VPS gives your WordPress site an allocated virtual machine rather than a typical shared-hosting account. That matters when you need more control over PHP, the web server, caching, databases, firewall rules, or other server-level settings.

But VPS hosting also moves responsibility toward you.

Recent 2026 WordPress VPS guides consistently split the market into two groups: managed services, where the host or platform handles much of the server administration, and unmanaged VPS, where you are responsible for the operating system, security updates, web stack, backups, monitoring, and troubleshooting.

LisaHost sits much closer to the second category. Its public documentation discusses Linux, SSH, firewall settings and system administration rather than presenting a managed WordPress dashboard.

That can be a good fit for a developer or technically comfortable site owner. It can also be a poor fit for someone who expects support to include routine WordPress optimization, plugin troubleshooting, backups, and server maintenance.

A useful way to think about the trade-off is:

> **Managed WordPress hosting buys you less server work. A VPS buys you more control.**

Neither is automatically the right answer.

## How much VPS power does a WordPress site need?

Start with the site, not the plan name.

A simple brochure site, personal blog, documentation site, or small business website usually does not need an enormous amount of CPU or RAM. A WooCommerce store, membership site, high-traffic publication, or WordPress installation running several heavy plugins has a very different workload.

For a modest single-site installation, 1 vCPU and 1 GB RAM can be technically enough to run WordPress, but that leaves little headroom for database growth, caching, background jobs, WooCommerce processes, image processing, or traffic spikes. The current LisaHost catalog has several 1-core/1-GB configurations, so these are legitimate low-cost entry points, but they should be treated as small VPS environments rather than comfortably oversized WordPress servers.

For a more general-purpose WordPress setup, **2 vCPU and 2 GB RAM** is a much more flexible starting point. LisaHost has multiple plans in that range, including 9929, 4837 and several regional VPS families.

For WooCommerce, multiple sites, a larger database, or heavier plugins, 4 vCPU and 4 GB RAM gives you substantially more room. LisaHost also offers 4-core/4-GB configurations in several product families.

The important part is that RAM and CPU are only half of the decision. Storage technology, network location, traffic allowance, backups and your own server configuration can matter just as much.

## What makes a VPS suitable for WordPress?

There is a surprisingly simple checklist.

You want a current Linux distribution, a supported PHP version, MariaDB or MySQL, HTTPS, and a web server such as Nginx or Apache. WordPress itself does not require some exotic hosting architecture.

You should also be able to connect to the machine and administer it. LisaHost's current documentation explicitly covers SSH connections to Ubuntu and CentOS machines, including direct SSH access to public IP addresses.

That makes the server technically suitable for a manually installed WordPress stack.

What the public LisaHost pages do **not** establish is that every VPS is preconfigured as managed WordPress hosting, that backups are automatically handled for WordPress, or that WordPress performance tuning is included as part of the hosting package. Those are separate questions and should not be assumed from the fact that the server can run WordPress.

## LisaHost's current WordPress-relevant VPS pricing

LisaHost does not present a neat WordPress-only pricing page. Its public catalog is organized by network, location and product type. The table below covers the general-purpose VPS products that are directly relevant to a WordPress use case and whose current public configurations I could verify.

Prices below are the publicly displayed prices visible during the current September 27, 2026 check. LisaHost displays most prices in Chinese yuan (CNY/RMB). Some products are explicitly marked as limited-time offers.

| VPS plan | CPU / RAM / storage | Bandwidth / traffic | Price & billing | Purchase |
| --- | --- | --- | --- | --- |
| US CN2 GIA Trial | 1 vCPU / 1 GB / 10 GB SSD | 10 Mbps / 1 GB, 1 day | **¥2 / 1 day** | [ Check current offer](https://bit.ly/LIsahost) |
| US CN2 GIA Basic | 1 vCPU / 1 GB / 20 GB SSD | 15 Mbps / 500 GB | **¥35 / month** | [ Check current offer](https://bit.ly/LIsahost) |
| US International Basic | 1 vCPU / 1 GB / 20 GB SSD | 60 Mbps / 2 TB | **¥132 / quarter** | [ Check plan](https://bit.ly/LIsahost) |
| US International Advanced | 2 vCPU / 2 GB / 40 GB SSD | 80 Mbps / 4 TB | **¥223 / quarter** | [ Check plan](https://bit.ly/LIsahost) |
| US International Deluxe | 4 vCPU / 4 GB / 80 GB SSD | 100 Mbps / 8 TB | **¥508 / quarter** | [ Check plan](https://bit.ly/LIsahost) |
| US 9929 Lite | 1 vCPU / 1 GB / 10 GB NVMe | 50 Mbps / 1 TB | **¥68 / month** | [ Check 9929 plans](https://bit.ly/LIsahost) |
| US 9929 Basic | 1 vCPU / 1 GB / 20 GB NVMe | 60 Mbps / 2 TB | **¥88 / month** | [ Check 9929 plans](https://bit.ly/LIsahost) |
| US 9929 Advanced | 2 vCPU / 2 GB / 40 GB NVMe | 80 Mbps / 4 TB | **¥158 / month** | [ Check 9929 plans](https://bit.ly/LIsahost) |
| US 9929 Deluxe | 4 vCPU / 4 GB / 80 GB NVMe | 100 Mbps / 8 TB | **¥899 / month** | [ Check 9929 plans](https://bit.ly/LIsahost) |
| US 9929 Unlimited Lite | 2 vCPU / 2 GB / 40 GB NVMe | 20 Mbps / unlimited | **¥498 / month** | [ Check 9929 plans](https://bit.ly/LIsahost) |
| US 9929 Unlimited Pro | 4 vCPU / 4 GB / 80 GB NVMe | 50 Mbps / unlimited | **¥1,288 / month** | [ Check 9929 plans](https://bit.ly/LIsahost) |
| US 9929 Annual Special | 1 vCPU / 1 GB / 10 GB NVMe | 50 Mbps / 600 GB monthly | **¥499 / year** | [ Check annual plan](https://bit.ly/LIsahost) |
| US 4837 Basic | 1 vCPU / 1 GB / 20 GB NVMe | 300 Mbps / 3 TB | **¥68 / month** | [ Check 4837 plans](https://bit.ly/LIsahost) |
| US 4837 Advanced | 2 vCPU / 2 GB / 40 GB NVMe | 500 Mbps / 8 TB | **¥100 / month** | [ Check 4837 plans](https://bit.ly/LIsahost) |
| US 4837 Deluxe | 4 vCPU / 4 GB / 80 GB NVMe | 1 Gbps / 20 TB | **¥699 / month** | [ Check 4837 plans](https://bit.ly/LIsahost) |
| US 4837 Unlimited Lite | 2 vCPU / 2 GB / 20 GB NVMe | 200 Mbps / unlimited | **¥398 / month** | [ Check 4837 plans](https://bit.ly/LIsahost) |
| US 4837 Unlimited Pro | 8 vCPU / 8 GB / 80 GB NVMe | 500 Mbps / unlimited | **¥998 / month** | [ Check 4837 plans](https://bit.ly/LIsahost) |
| US 4837 Annual Special | 1 vCPU / 1 GB / 10 GB NVMe | 100 Mbps / 600 GB monthly | **¥399 / year** | [ Check annual plan](https://bit.ly/LIsahost) |
| US CN2 GIA Unlimited 1 Mbps | 1 vCPU / 1 GB / 10 GB SSD | 1 Mbps / unlimited | **¥30 / month** | [ Check CN2 plans](https://bit.ly/LIsahost) |
| US CN2 GIA Unlimited 2 Mbps | 1 vCPU / 1 GB / 20 GB SSD | 2 Mbps / unlimited | **¥65 / month** | [ Check CN2 plans](https://bit.ly/LIsahost) |
| US CN2 GIA Unlimited 5 Mbps | 2 vCPU / 2 GB / 40 GB SSD | 5 Mbps / unlimited | **¥299 / month** | [ Check CN2 plans](https://bit.ly/LIsahost) |
| US CN2 GIA Unlimited 10 Mbps | 4 vCPU / 4 GB / 60 GB SSD | 10 Mbps / unlimited | **¥799 / month** | [ Check CN2 plans](https://bit.ly/LIsahost) |
| US CN2 GIA Unlimited 20 Mbps | 8 vCPU / 8 GB / 100 GB SSD | 20 Mbps / unlimited | **¥1,999 / month** | [ Check CN2 plans](https://bit.ly/LIsahost) |
| US CERA Trial | 1 vCPU / 1 GB / 10 GB SSD | 10 Mbps / 1 GB, 1 day | **¥2 / 1 day** | [ Check CERA plans](https://bit.ly/LIsahost) |
| US CERA Slim | 1 vCPU / 512 MB / 10 GB SSD | 10 Mbps / 100 GB | **¥40 / month** | [ Check CERA plans](https://bit.ly/LIsahost) |
| US CERA Basic | 1 vCPU / 1 GB / 20 GB SSD | 15 Mbps / 500 GB | **¥50 / month** | [ Check CERA plans](https://bit.ly/LIsahost) |
| US CERA Advanced | 2 vCPU / 2 GB / 20 GB SSD | 25 Mbps / 1.2 TB | **¥256 / quarter** | [ Check CERA plans](https://bit.ly/LIsahost) |
| US CERA Deluxe | 4 vCPU / 4 GB / 40 GB SSD | 50 Mbps / 3 TB | **¥396 / month** | [ Check CERA plans](https://bit.ly/LIsahost) |
| New York Basic | 1 vCPU / 1 GB / 20 GB NVMe | 300 Mbps / 3 TB | **¥68 / month** | [ Check New York plans](https://bit.ly/LIsahost) |
| New York Advanced | 2 vCPU / 2 GB / 40 GB NVMe | 500 Mbps / 8 TB | **¥100 / month** | [ Check New York plans](https://bit.ly/LIsahost) |
| New York Deluxe | 4 vCPU / 4 GB / 80 GB NVMe | 1 Gbps / 20 TB | **¥300 / month** | [ Check New York plans](https://bit.ly/LIsahost) |
| New York Unlimited Lite | 2 vCPU / 2 GB / 40 GB NVMe | 200 Mbps / unlimited | **¥198 / month** | [ Check New York plans](https://bit.ly/LIsahost) |
| New York Unlimited Pro | 8 vCPU / 8 GB / 120 GB NVMe | 500 Mbps / unlimited | **¥498 / month** | [ Check New York plans](https://bit.ly/LIsahost) |
| New York Annual Special | 1 vCPU / 1 GB / 10 GB NVMe | 100 Mbps / 600 GB monthly | **¥399 / year** | [ Check New York plans](https://bit.ly/LIsahost) |
| Chicago Basic | 1 vCPU / 1 GB / 20 GB NVMe | 300 Mbps / 3 TB | **¥68 / month** | [ Check Chicago plans](https://bit.ly/LIsahost) |
| Chicago Advanced | 2 vCPU / 2 GB / 40 GB NVMe | 500 Mbps / 8 TB | **¥100 / month** | [ Check Chicago plans](https://bit.ly/LIsahost) |
| Chicago Deluxe | 4 vCPU / 4 GB / 80 GB NVMe | 1 Gbps / 20 TB | **¥300 / month** | [ Check Chicago plans](https://bit.ly/LIsahost) |
| Chicago Unlimited Lite | 2 vCPU / 2 GB / 40 GB NVMe | 200 Mbps / unlimited | **¥198 / month** | [ Check Chicago plans](https://bit.ly/LIsahost) |
| Chicago Unlimited Pro | 8 vCPU / 8 GB / 120 GB NVMe | 500 Mbps / unlimited | **¥498 / month** | [ Check Chicago plans](https://bit.ly/LIsahost) |
| Chicago Annual Special | 1 vCPU / 1 GB / 10 GB NVMe | 100 Mbps / 600 GB monthly | **¥399 / year** | [ Check Chicago plans](https://bit.ly/LIsahost) |
| Hong Kong Basic | 1 vCPU / 1 GB / 20 GB NVMe | 30 Mbps / 1 TB | **¥88 / month** | [ Check Hong Kong plans](https://bit.ly/LIsahost) |
| Hong Kong Advanced | 2 vCPU / 2 GB / 40 GB NVMe | 50 Mbps / 2 TB | **¥188 / month** | [ Check Hong Kong plans](https://bit.ly/LIsahost) |
| Hong Kong Unlimited Lite | 2 vCPU / 2 GB / 40 GB NVMe | 30 Mbps / unlimited | **¥998 / month** | [ Check Hong Kong plans](https://bit.ly/LIsahost) |
| Hong Kong Unlimited Pro | 4 vCPU / 4 GB / 80 GB NVMe | 50 Mbps / unlimited | **¥1,988 / month** | [ Check Hong Kong plans](https://bit.ly/LIsahost) |
| Hong Kong Annual Special | 1 vCPU / 1 GB / 10 GB NVMe | 50 Mbps / 600 GB monthly | **¥566 / year** | [ Check Hong Kong plans](https://bit.ly/LIsahost) |

The public catalog also contains specialized residential-IP VPS/VDS offerings in Japan, Korea, Singapore, Taiwan, Germany, the UK and Vietnam, plus physical-server products. They are not automatically better WordPress choices simply because they offer residential IP addresses or unusually large traffic allowances. LisaHost's catalog clearly emphasizes those features for use cases such as regional access, social platforms and media services, whereas a conventional WordPress site usually cares more about CPU, memory, storage, connectivity, backups and server administration.

## Which LisaHost configuration makes sense for WordPress?

For a normal WordPress site, there are a few useful dividing lines.

### A small blog or brochure site

A 1-core, 1-GB VPS can run WordPress when the workload is light. LisaHost has several options in this configuration, including the US 9929 Lite, US 4837 Basic, New York Basic and Chicago Basic.

The question is not whether WordPress can start. It can.

The better question is what happens when you add WooCommerce, a page builder, image processing, scheduled jobs and a few busy plugins. That is where a tiny VPS can become a false economy.

### A general business site or content site

A **2 vCPU / 2 GB** configuration is easier to live with.

LisaHost's US 9929 Advanced is 2 vCPU, 2 GB RAM, 40 GB NVMe and 4 TB traffic at ¥158/month. The US 4837 Advanced has the same CPU/RAM/storage class but a much larger 8 TB traffic allowance and a 500 Mbps advertised port at ¥100/month.

Those two illustrate why comparing the headline price alone can be misleading. The 4837 package offers a much larger traffic allowance and network port, while the 9929 configuration uses the 9929 route and a different product positioning. The right choice depends on where your visitors are and what sort of network path you actually need.

### WooCommerce or a busier site

At this point, 4 vCPU and 4 GB RAM becomes much more comfortable.

LisaHost's larger 9929 configuration provides 4 vCPU, 4 GB RAM, 80 GB NVMe, 100 Mbps and 8 TB traffic. The equivalent 4837 Deluxe has 4 vCPU, 4 GB RAM, 80 GB NVMe, 1 Gbps and 20 TB traffic.

That does **not** mean the 4837 package will automatically make WordPress faster. The advertised port speed is not the same thing as end-user page-load speed, and WordPress performance is heavily affected by PHP workers, database queries, caching, CDN configuration, plugin quality and the distance between users and the server.

## The network choice matters more than a lot of hosting comparisons admit

LisaHost sells several different network paths, including CN2 GIA, AS9929 and AS4837 options.

That is useful when your audience is geographically concentrated, but it can also make product selection confusing.

The US CN2 GIA unlimited products are explicitly built around traffic limits of “unlimited” paired with very low port speeds from 1 Mbps through 20 Mbps.

That makes them very different from the 4837 or 9929 products offering hundreds of Mbps and multi-terabyte traffic allocations.

For a normal WordPress business website, “unlimited traffic” sounds attractive until you notice the 1 Mbps or 2 Mbps network cap. A site can remain online under that configuration, but the word *unlimited* should not be mistaken for unlimited throughput.

The opposite mistake is buying a very large 1 Gbps VPS when your actual WordPress site barely uses a fraction of that capacity.

A sensible decision starts with:

* where most visitors are located;
* whether the site is content-heavy or transaction-heavy;
* how much traffic you realistically expect;
* whether your application needs unusually large file transfers;
* whether you need a specific network path for your visitors.

## Residential IP is usually not the reason to buy a WordPress VPS

This is one of the most important LisaHost-specific distinctions.

The company's catalog prominently promotes dual-ISP residential IP products, especially in the US. The 9929 and 4837 families, for example, are described as residential-IP VPS products with large traffic allowances and network-specific routing.

That can matter for certain location-sensitive applications.

For a standard WordPress website, however, your public IP being marketed as a residential IP does not replace the things WordPress actually needs. WordPress still needs a functional PHP/database/web-server stack and HTTPS.

So do not pay a large premium simply because a plan includes a feature that your website does not need.

For WordPress, **server resources and management requirements usually deserve more attention than residential-IP branding**.

## How hard is WordPress installation on an unmanaged VPS?

This is where the search intent around “WordPress VPS hosting” often gets mixed up with managed WordPress hosting.

A bare VPS generally means you need to prepare the server yourself:

1. Provision the VPS and choose a supported Linux distribution.
2. Connect over SSH.
3. Update the operating system.
4. Configure a firewall and a non-root administrative workflow.
5. Install Nginx or Apache.
6. Install PHP and the extensions WordPress needs.
7. Install MariaDB or MySQL.
8. Create the database and user.
9. Configure the domain and HTTPS.
10. Install WordPress.
11. Configure caching, backups and monitoring.
12. Keep the operating system, PHP and WordPress components updated.

WordPress's own documentation supports both automated and manual installation approaches, and explicitly notes that server access through FTP or shell may be required for manual administration.

LisaHost's own documentation confirms that SSH administration is part of the normal workflow for its Linux machines.

So, technically, the workflow is straightforward.

The operational part is what people underestimate.

A WordPress site on a VPS is your responsibility unless your particular service includes management that is explicitly stated by the provider. That includes backups that you can actually restore, security updates, server monitoring, disk-space management and recovery from configuration mistakes.

## One LisaHost policy worth paying attention to

LisaHost currently states that services can qualify for a full refund when cancelled within 48 hours of provisioning, with exceptions for heavily used services, certain fees and abuse; after the 48-hour window, requests are considered case by case. Its terms specify that using more than 5% of allocated bandwidth or 20 GB, whichever is smaller, disqualifies a heavily used service from the refund policy.

That makes the small trial products particularly relevant for cautious buyers.

The site currently lists a **¥2 one-day CN2 GIA trial** with 1 vCPU, 1 GB RAM, 10 GB SSD, 10 Mbps and 1 GB of traffic. It also has a separate ¥2 one-day CERA trial. Both are explicitly listed with no refund on the trial product itself.

Those numbers are useful because they let you test the kind of network and server environment you are considering without pretending a one-day trial can reproduce an entire production workload.

## Is there a LisaHost discount code right now?

There is one current code with unusually strong third-party confirmation.

LisaHost's official Telegram announcements have recently published:

**`TS-CBP205DQJE` — 10% off**

The code is also reported by multiple current third-party coupon pages as a recurring 90%-price discount, with one current tracker listing an expiry of **December 31, 2026**.

Because coupon systems can change at checkout, the sensible way to use it is to enter the code and confirm that the cart actually recalculates the price before paying.

[👉 Check LisaHost with the current affiliate offer](https://bit.ly/LIsahost)

Some third-party sources also claim additional billing-cycle discounts, such as lower effective pricing on quarterly or annual payments. Those claims are not presented consistently enough on the current public product pages to treat every advertised stacking combination as guaranteed, so the checkout total is the figure that matters.

## What about LisaHost reviews?

The review picture is unusually thin.

Trustpilot currently shows LisaHost at **3.2/5 from one review**, including one negative review published in January 2026. One review is far too small a sample to establish a meaningful overall customer rating, but it is still useful as a reminder not to mistake a lack of complaints on affiliate pages for independent evidence of service quality.

Third-party LisaHost reviews are much more plentiful in niche VPS communities, but many are affiliate-style comparisons or promotional reviews. They tend to focus heavily on residential IPs, international routes and region-specific access rather than WordPress administration.

That distinction matters.

A host can be interesting for one workload and inconvenient for another without either conclusion being contradictory.

## LisaHost vs managed WordPress hosting

This is probably the most useful comparison to make before buying.

A managed WordPress service typically packages WordPress-specific conveniences around the infrastructure: automatic updates, backups, staging, security tooling, support workflows and a WordPress-focused control panel. WordPress itself recognizes that WordPress-specific hosting may offer backups, updates and developer tools beyond generic hosting.

LisaHost's public documentation instead looks like a conventional VPS environment. You get a virtual server and the ability to administer it, with Linux and SSH material available in the help center.

That means the comparison is really:

**Pay more for less server administration**, or **pay for a VPS and do more of the administration yourself**.

For a developer managing several WordPress installations, the latter can be attractive because you control the stack. For someone who just wants to publish a company website and never touch Nginx, PHP or system updates, the convenience of managed WordPress hosting can be worth paying for.

## A practical LisaHost starting point

For a conventional WordPress site, I would narrow the current LisaHost catalog much more aggressively than the marketing catalog suggests.

A small personal blog can begin around the 1 vCPU / 1 GB class.

A business site, content site or light WooCommerce installation is better matched to the **2 vCPU / 2 GB** class. Within LisaHost's catalog, that includes products such as the US 9929 Advanced at ¥158/month and US 4837 Advanced at ¥100/month.

A heavier WooCommerce site or multi-site setup can justify **4 vCPU / 4 GB** and more storage. The US 9929 Deluxe and US 4837 Deluxe are both in that resource class, although their pricing and network characteristics differ considerably.

I would not move directly to an 8-core “unlimited” plan just because the numbers look impressive. WordPress bottlenecks are often caused by inefficient plugins, database queries, PHP worker limits, poor caching or a badly configured stack rather than a lack of raw bandwidth.

## A simple checklist before you order

Before choosing any WordPress VPS hosting package, verify these in this order:

**WordPress stack:** PHP 8.3+, MySQL 8.0+ or MariaDB 10.11+, HTTPS, and a properly configured Nginx or Apache environment.

**Resources:** Start around 2 vCPU / 2 GB for a general-purpose site unless your workload clearly points lower or higher.

**Storage:** NVMe is useful for busy sites and databases, but capacity matters too. Make sure the disk can accommodate WordPress, uploads, databases, logs and backups.

**Traffic:** Look beyond the word “unlimited.” A 1 Mbps unlimited plan is a radically different proposition from a multi-terabyte plan with hundreds of Mbps of bandwidth.

**Administration:** Decide whether you are comfortable maintaining Linux, PHP, the web server, firewall rules and backups.

**Geography:** Put the server reasonably close to your main audience unless you have a specific networking reason not to.

**Recovery:** Check what the refund policy actually says and maintain your own restorable backups. LisaHost's current terms provide a 48-hour refund window with significant usage and abuse exceptions.

## Bottom line

WordPress VPS hosting is less about finding a server with the largest specification sheet and more about matching the machine to the workload you actually have.

LisaHost is a **general VPS provider rather than a managed WordPress specialist**. Its public catalog offers a wide range of KVM VPS configurations, including small 1-core machines, 2-core/2-GB midrange servers, larger 4-core options, several network routes and multiple regional locations.

For WordPress, the more interesting LisaHost configurations are the ones that give you enough RAM and CPU without charging a premium for features you do not need. The **2 vCPU / 2 GB class** is a practical middle ground; 4 vCPU / 4 GB makes more sense once the site or application genuinely needs the extra headroom.

And before spending more money for “unlimited” traffic, residential IPs or a huge port speed, check what your WordPress site is actually going to do. A well-configured 2 GB VPS with sensible caching can be far more useful than a monster VPS running an inefficient plugin stack.

[👉 Compare the current LisaHost VPS options](https://bit.ly/LIsahost)
