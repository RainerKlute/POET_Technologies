# Pure play AI datacom hardware

*Dr. Suresh Venkatesan, 2024-06-21, presentation at POET Technologies’ AGM – highlighting done by Rainer Klute*

Last year at this time, I shared my enthusiasm and optimism for POET’s future, and today, I have every reason to be even more optimistic. The reasons are many, but we start with the progress we’ve made in our financial stability and customer experiences, and extend to our continued innovation and the remarkable opportunities in front of us.

I would like to provide the shareholders with more insight into how we’re thinking about the company, the businesses we’re pursuing, our future opportunities, and what makes us tick.

## Financial

In 2024, POET has been able to add approximately $29 million to its balance sheet, significantly improving its financial stability, inclusive of private placements, ATM share sales, and warrant conversions. This has enabled POET to re-invigorate its roadmap and make the necessary investment to transform its product roadmap to one explicitly dedicated to the growing demands placed by AI on hardware infrastructure. While we’ve made meaningful progress on our financial measures, what we are most pleased about is the continued product development and customer engagement across our business.

## AI – the catalyst

But first, let’s discuss the markets we serve. Generative AI may be the largest technology transformation since the cloud, which itself is still in the early stages, and perhaps since the Internet. AI is what we at POET have dubbed the market driver for Photonics 3.0, a wave of photonics growth propelled by the insatiable data requirements of generative AI.

Generative AI is typically an application built on what are called foundational models and this is in the creation of these foundational models where the hardware pinch is felt. Foundational models require compute that are needed to train models and generate inferences or predictions and the software that makes it easier to build these models but **the invisible link that makes the compute tick is the data communications fabric that is required to move vast quantities of data with low latency across the compute service. This is the market that POET plays in.**

As we go through 2024 and into 2025, it is now unmistakably clear that AI has established itself as an overarching catalyst propelling our vectors of growth from high-speed 800 gig to 3.2 terabits per second optical engines and modules, and technically differentiated remote light sources that support short-reach data communication links within compute clusters. **Our products provide foundational hardware to the AI ecosystem.**

### Optical data communication applications in an AI server

You can see in this mock-up of a typical NVIDIA DGX box. A DGX box is an AI server which has in it multiple GPUs, memories, and other compute elements. And each DGX box represents a vast number of optical OSFP transceivers, and these are used for server-to-server transfer within an AI cluster. All the other links inside of the DGX box are still copper today, but soon these will also be converted into optical links, and there are numerous companies are vying to penetrate this space with distinct solutions.

POET targets solutions both within the AI server and for server-to-server connectivity. **The primary solution for optical connectivity for AI clusters is pluggable transceivers.** This is like data center networks, except that the data rate and the unit volume requirements for AI clusters is much higher. POET optical engines are highly integrated solutions that address higher speeds of 1.6T and 3.2T, soon, and can scale to high volume because of its wafer-scale assembly and test.

The other part of the AI market that we’re addressing is the chip-to-chip optical communication. A majority of the GPU and memory links today are still electrical, but optical connectivity has benefits, and which is why large AI hardware companies are investing in this technology. POET has its external light source product line that addresses this market and offers a cost-effective and highly scalable solution.

We are fortunate to participate in markets of remarkable opportunity. Not only are they vast and constantly expanding, but they also manifest unique attributes where we tackle complex challenges requiring feature-rich solutions that **preclude any chance of commoditization, giving rise to high barriers of entry that keep potential competitors at bay**.

Coming soon, you will learn about a notable **AI industry award** that we’ve won, highlighting POET’s architectural advantages in AI and providing more third-party validation and exposure.

## Foundations for rapid revenue growth – customers, partners and products

With that backdrop, what we’re doing now sets the foundation for rapid revenue growth in 2025 and 2026. Any successful business requires execution around three vectors: key customers, key partners, and key products and development. We announced our engagement with **Luxshare** last year with a design-in of our 2xFR4 800 gig RX engines. This year, we’ve expanded that relationship to include our differentiated EML-based transmit solutions. Likewise, this year, we announced an agreement with **Foxconn**, one of the premier module suppliers in the world.

Both these engagements are around the 800 gig transceiver products, with an extension to 1.6T as the market prepares for that transition. Companies like Foxconn and Luxshare are rushing to address the gaps in supply chain for optical transceivers for the AI market. With Foxconn, we’re collaborating on developing 800 gig and 1.6T optical transceiver modules that address the demands of the AI industry. Both Foxconn and Luxshare are already established suppliers in the hyperscale datacenter market, and now they are gearing up to address the AI demand.

Particularly with Foxconn, we are working in parallel on both conventional transceivers and solutions for linear pluggable optics, called LPO, which eschews the DSP and saves significant power consumption. We believe LPO will be the future of optical transmission once the kinks are worked out due to the large reduction in power consumption for LPO modules.

We also announced a partnership with **MultiLane** to develop optical transceiver modules using POET’s optical engines. MultiLane is one of the leaders in the optical test equipment segment and has direct ties to the hyperscalers. MultiLane has a desire to expand their product lines to include optical transceivers and have established an internal production capability for modules. **MultiLane’s choice to work with POET was influenced by the low-capex costs for module manufacturing when using our highly integrated optical engines.**

MultiLane has some unique capabilities that complement our technology and products. We’re collaborating with them to design pluggable optical transceivers using our optical engines that will help our customers to accelerate the design cycles even further. The objective is to design cost-optimized 800 gig modules that offer superior power and performance. This collaboration helps reduce POET’s development outlay by nearly $5 million annually as we can leverage MultiLane’s expertise versus building capability in-house.

A year ago, POET was pursuing a DML-based optical engine approach for 800 gig solutions. Despite successfully sampling optical engines with DML lasers, several factors necessitated a change, primary among them being a very large adoption of EML lasers worldwide. This large adoption helped drop prices and also caused vendors to prioritize EML lasers over other solutions. We quickly retooled the interposer architecture and process and transitioned to developing EML-based solutions in Q4 of last year.

We were able to generate **first-time-right designs**, which resulted in a very successful demonstration of our solutions at the OFC in 2024. The ability to now produce 400 gig and 800 gig transmit solutions based on EMLs has been **truly transformational in terms of customer interest**. EML lasers comprise 80+ percent of the optical transceiver usage worldwide, and we’ve developed the world’s **one and only integration platform for EML lasers**. At the OFC, we simultaneously showcased both 100 gig per lane and 200 gig per lane solutions as 400 gig and 800 gig chiplets.

One of the many advantages of the POET platform is its **speed of development**. If the building blocks are done well, we can generate rapid transitions in its products.

We’ve also expanded our supply of EML lasers to include **Mitsubishi Electric** and **Huanye** in addition to **Lumentum**.

With regards to 1.6T, two things need to happen for AI to deploy. First, the 200 gig per lane on the electrical side has to be available for deployment. Large players like NVIDIA and Broadcom have already announced products with 200 gig per lane, and the expectation is that it will be available for deployment late in 2025 and into 2026.

The second thing is the availability of 1.6T optical transceivers. This is where POET is collaborating with several customers to use our optical engines and bring 1.6T transceivers to the market in 2025. Perhaps for the first time since I’ve been at POET, we talk to customers about 1.6T and they tell us we’re early. This has never happened before; we’ve always been playing catch-up. **So, our transition over the past six months to the EML platform and the significant leapfrog in capability is really positioning us at the forefront of optical transceiver adoption.**

But we’re not stopping there. OSFP-XD is an industry standard that is already defined. It can carry 16 lanes of 200 gig, which gets us to 3.2T. The challenge is to fit all the high-speed optical and electrical components inside this package. POET already has a solution today for 16 lanes of 25 gig that fits inside a QSFP-DD that we’re building for ADVA. That’s a package that’s even smaller than an OSFP-XD.

One of the benefits of our interposer technology is its scalability. We can scale our designs from 16 lanes of 25 gig to 16 lanes of 200 gig. Of course, there are several challenges that come with higher speeds, which our engineers are working on now. We’re also collaborating with some industry leaders to come up with innovative solutions for 3.2T, with a goal to showcase our solution at the OFC next year.

### Taking the next step with highly differentiated remote light sources

Likewise, we’re transcending our remote light sources to one that provides immense technical superiority. Stickiness in the market and with customers doesn’t only come with cost; there needs to be a plus-one feature that results in stickiness, and that is what we’re striving to do to capture a disproportionate share of the remote light source market as that market develops and matures.

We’re developing brand-new architectures and concepts around the interposer that can build multiple lanes of lasers on the interposer with **frequency spacings down to 50 gigahertz in an uncooled application**, which is unheard of. So these are things that we’re working on now, and more to follow.

### 200G/lane products enable 3.2T pluggable form factors

We will begin sampling our 100 gig per lane 800 gig transmitter solutions in July, to accompany our already developed receiver solutions, to multiple customers, with three committed to module design across multiple form factors in addition to our MultiLane collaboration.

In parallel, we continue to mature our 200 gig per lane solutions and we will be demonstrating RX and TX configurations at the CIOE in September. We will also be in production on our first generation of the remote light source product, the Starlight, by the end of this year.

## Business model

We also need to constantly look at our business model as the demands on our product are evolving with successive generations. While the demand for optical engines versus modules was muted at lower speeds, the transition to EML architectures has completely transformed this demand picture. We now see significant demand picking up for our optical engines at 800 gig in various form factors: DR8, 2xFR4, LPO, and especially with large suppliers.

So, we are now adopting a dual model: **optical engines to large suppliers** and **optical modules in niche applications**. This prevents direct conflict with our customers and also enables POET to proliferate its solutions outside the mainstream.

Given the shift in demand, especially with the likes of **Foxconn, Luxshare, and a third to be named supplier**, we are working to consolidate our subsidiaries in China to allow more operational control and to be able to recognize revenue sooner.

And then there is the issue of coping with the **China-West split**, especially as it relates to AI and high-speed transmission. While no one explicitly says “no China,” it is implicit. Innolight, Eoptolink, and several module companies in China have established operations in Thailand over the past year. Customers are dictating component choices based on geography. While it’s not clear where this is headed, it would be prudent to project that we will require optical engine manufacturing outside Super Photonics and outside China.

We’re working on this issue with renewed urgency. We believe in the not-too-distant future, we would need to adopt a **bifurcated manufacturing and sales strategy**. Within China, we’ll be setting up a sales and marketing company with external investment, dedicated to winning and growing in China, leveraging Chinese manufacturing and Chinese components, whereas outside China, we will use our internal sales and marketing engine and establish manufacturing, potentially in the Singapore-Malaysia corridor. In both cases, our collaboration with MultiLane provides us a source of optical module manufacturing.

## To conclude

In closing, I’m grateful to our collective teams who have delivered on behalf of our shareholders and customers. These results represent a lot of invention, collaboration, discipline, execution, and reimagination across POET. There is nothing so limiting as viewing opportunities through the same lens as yesterday’s challenges. We at POET strive to innovate with out-of-the-box solutions to challenges versus incremental improvements, which do not sustain in the long term.

We will continue to focus on hiring and retaining versatile and talented employees to the marginal expansion across the sites in specific areas. We know our success will be largely dictated by our ability to attract and retain a motivated employee base, each of whom must think like, and therefore must actually be, an owner. The past year’s development progress is the product of a talented, smart hard-working group, and I take great pride in being part of this team.

Thank you for your time.