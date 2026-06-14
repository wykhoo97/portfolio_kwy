+++
author = "Khoo Wei Yang"
title = "Harmonizing climate finance data"
date = "2026-06-13"
description = "Braving the task of data harmonization"
tags = ["blog","data"]
+++

Finance is an integral part of climate action. Building resilience against climate change often comes with little monetizable returns to the private sector. Hence, mobilization of resources for public goods like climate adaptation is crucial. Luckily, international treaties have made provisions for climate finance to be channeled across countries. There are [over $2 trillion of finance sloshing around globally](https://www.climatepolicyinitiative.org/publication/global-landscape-of-climate-finance-2025/). Data on these finance streams are publicly available, however, there are little consolidated information.

Since September 2025, I was involved in a collaboration[^1] in appraising the state of international climate finance. The main attempt was to mark out the finance flow to Southeast Asia. We ran into a number of problems involving harmonizing and verifying diverse streams of public climate finance data. Regrettably, the exercise have proved inadequate, and reliability of the results pending verification[^2]. With two members involved, the project simply lacked the manpower it required. 

This blog post serves as a record of the trials and errors in putting together a harmonized dataset, and *hopefully* help future researchers and analysts interested in working with (*braving*) public climate finance dataset. 

### Multi-channel, multi-source, multiverse

There are two main channels of climate finance: (1)multilateral channels and (2) bilateral channels. Under the Paris Agreement's Financial Mechanism, multilateral channels are administered by [special funds and operating entities](https://unfccc.int/process-and-meetings/bodies/funds-and-financial-entities) that manage the applications, approvals and financing of climate-related activities (and/or projects). Bilateral climate finance are financing initiatives undertaken by two entities who enter into a agreement. These could be bilateral agreements between two governments, two corporations, a multinational and a government, and so on.

The financial instruments — how the funds are financed and in what form they are delivered — also vary by projects. [Instruments are basically financial contracts](https://www.parlamericas.org/uploads/documents/Primer_on_Climate_Financing_ENG.pdf). The type of instruments matter because each entails a different set of implications. This is especially crucial for developing countries with varying circumstances that constrain their debt tolerance. 

There are four main type of instruments in the UNFCCC classification: (1) concessional loans, (2) non-concessional loans, (3) grants and (4) equity. There are plenty of other instruments that involve capital subscription and a mixtures of the main types.

Besides the channels and instruments, we also have to deal with the sources of data. As noted, there is a family of operating entities set up by Article 11 to administer climate finance, namely Global Environment Facility (GEF) and Green Climate Fund (GCF). There are also a number of other entities including developmental banks, e.g. World Bank, that earmark finances for climate action. While data of the convention-backed entities are [published on the UNFCCC climate finance data portal](https://unfccc.int/climatefinance?home), the others are either unavailable publicly or remained scattered. 

##### Reported contributions to funds by instruments 

<iframe width="100%" height="684" frameborder="0"
  src="https://observablehq.com/embed/e244c11dcfc9c8b5?cells=chart"></iframe>

Part of my task was to figure out how much finance has been transferred from developed countries to developing countries, as part of the [obligations provisioned under Article 9](https://unfccc.int/topics/climate-finance/the-big-picture/climate-finance-in-the-negotiations/climate-finance). This is fairly simple for bilateral finance, as parties report their [contribution to bilateral projects/agreements](https://unfccc.int/climatefinance/nc/party_contributions), recipient-tagged and all. The problem is often the regional and sub-regional categorization, which follows international standards loosely, making it hard to carve out figures for any single recepient country. There is also a problem of double-reporting, where both sides report in their respective National Communications. These numbers have not been reliably checked for alignment in our exercise.

The same problem stands for data of multilateral finance. Here, contributions are pooled in funds presided over by financial entities. Implementing entities that run the projects then apply for funding via these financial entities. Now, both the instuments and receipient classifications are scrambled across entities. Since I am no finance expert, there isn't much to do expect for re-classifying mixed and non-conventional instruments into a big "others" bucket, which isn't the best way. Similarly, there are a host of other allocation methods apart from Convention-backed entities or development banks.

While it can be suggested that precise accounting rules matters little as long as parties honored their reporting obligations, weeding through classes and categories make for an ultimately laborious (and reward-less) challenge. This does not help when adjudicating fair shares and global cooperation hinges so much on these figures.  

### What is the trend of climate finance in ASEAN countries?

ASEAN is a region highly vulnerable to climate risks. A bulk of the countries in the bloc are developing countries with limited financial means of adaptation and mitigation, many have been hit hard by physical impacts. International climate finance inflow to the region is critical to support climate action in countries with limited capacities. 

##### Reported finance tagged with ASEAN countries

<iframe width="100%" height="409" frameborder="0"
  src="https://observablehq.com/embed/e244c11dcfc9c8b5@242?cells=viewof+variable%2Cchart2"></iframe>

Let's take a look at the reported climate finance received by ASEAN members through the multilateral finance channel. As the finance flows are generally project-tagged, we can count how many projects have been tagged with an ASEAN country recipient. A big headache of this approach is that many projects are actually tagged to regional groupings. For example, a project tagged to Asia Pacific would've included countries in ASEAN. It is, of course, not the best to count the total finance to one country of the grouping, neither ignoring the project altogether (as many projects are region-tagged). But how do we approach disaggregation? My compromise was to divy-up the total equally across all countries within the grouping. 

To be sure, this could not in any way a satisfactory solution to the problem. The clear way out is to obtain the high-res data from responsible entities directly. Haing the exact figure helps thid-party validation of these reports, pre-empt double-counting (which is a problem in a great deal of climate accounting), and hold parties accountable. Nonetheless, it would be valuable for ASEAN governments and stakeholders to strategize better, wielded with an understanding of the landscape at hand. For instance, while we find that most of the contributions by Annex-I countries are in the form of grants, the bulk of finance received by ASEAN countries are, in fact, non-grants. This could mean very different approaches to accessing available finance and adjusting modality of national climate actions.

### Coda

Although the exercise inevitably ran aground on a host of issues, it has nonetheless resulted in some interesting lessons (or if I am allowed to believe so unabashedly). In a way, the bugbear that is climate accounting is itself a product of the methodological nationalism that underline all international commons problems. While global cooperation is indubitably important for any plausible solution to the climate problem, one cannot help but wonder: where does all of the smokes and mirrors that come with this system of coordination eventually lead us? Does it foster greater action? Will it help more responsible parties hide behind its apparent unsurmountable complexities? Will it bloat to a risible proportion and mean little in the face of even massively scaled impacts?


[^1]: I owe my big thanks to Nurul Farhana Abdul Shukor, my collaborator, who published some [important pieces on the subject.](https://www.krinstitute.org/people/nurul-farhana-binti-abdul-shukor)
[^2]: Climate Policy Initiative publishes an impressive report on the landscape of global climate finance regularly, which disaggregates data by public-private, instruments, and sectors. One impetus for our project has to do with the lack of aggregates on ASEAN countries.
