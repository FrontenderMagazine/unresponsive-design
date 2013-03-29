# Ditching responsive design

We've just redesigned our home pages, and moved from a responsive design to an
unresponsive one.

Given the trend towards a responsive web, we thought we'd share why.

## Why we ditched responsive design

When we designed our old home pages we followed the trend towards responsive
design. The result looked great on desktops and went some way towards being
device agnostic.

![Old homepage][Old design of our homepage]

I don't think anyone would argue that it isn't a good thing to provide a mobile
friendly interface for your web applications. However, we had focused on fitting
content to a flexible grid without really assessing the requirements of our
site.

When we came to redesign our site again, we decided to think through the case
for responsive design.There were three factors which tipped the balance against
responsive design:

* **We were pitching to the wrong audience** - it turns out that not many people 
shop around for Direct Debit on their mobiles. When we analysed our traffic, we 
found that only 2% of visits were from mobile devices.

* **It was much slower to implement** - responsive designs took almost twice as 
long to design and implement compared to fixed-width designs. This was valuable 
time we could have spent improving other areas of the product.

* **It constrained our designs** - we didn't have the resource to implement 
entirely different designs for desktop and mobile. This restricted us to simpler 
designs that could work for both formats. In some cases, this even led to 
compromised designs which weren't great for either format.

![Mobile][Samples of old design for mobile devices]

## What did we do instead?

For our new design, we decided to stick to a fixed grid of 980px. This gave us a
canvas that comfortably rendered on almost all desktops as well as on tablets.

![Grid][For our new design, we decided to stick to a fixed grid of 980px]

Using a fixed grid roughly doubled the speed of the design and development
process. It also gave us more flexibility to implement designs which wouldn't
have worked at smaller sizes.

![Invoicing page][New design of invoicing page]

Not only did we save a lot of time by avoiding responsive design, we were also
able to provide a better experience to 98% of our visitors.

## When should you be responsive?

Sometimes the extra effort for responsive design is well worth the investment.
We believe there are two criteria that determine this:

* **The proportion of mobile use** - obviously, if a significant proportion of 
your traffic is mobile, you should design for that audience.

* **The purpose of the visit** - will providing a better user experience for 
mobile users significantly impact your desired outcome?

For example, we believe it is really important to have a fully responsive design
for our checkout pages. Even small changes in checkout page conversion can make
a big difference to our customers. Whilst only ~3% of visitors to our checkout
pages are on a mobile, having an appropriate design can significantly impact
their conversion. So it's worth investing in, even for a small proportion of our
visitor base.

Mobile visitors often have a very different set of objectives for visiting your
site. In those cases, merely squashing content to fit on a smaller screen isn't
particularly helpful. Instead, it is important to consider how different
contexts change the content that users want.

Responsive design is definitely a useful tool to consider, but it's also
important to be clear on the case for it before embarking on any new projects.

[Old design of our homepage]: img/unresponsive-design1%402x.png?raw=true&amp;repo=unresponsive-design
[Samples of old design for mobile devices]: img/unresponsive-design2%402x.png?raw=true&amp;repo=unresponsive-design
[For our new design, we decided to stick to a fixed grid of 980px]: img/unresponsive-design3%402x.png?raw=true&amp;repo=unresponsive-design
[New design of invoicing page]: img/unresponsive-design4%402x.png?raw=true&amp;repo=unresponsive-design