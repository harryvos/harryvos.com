---
title: What product managers can do to reduce CO₂
description: Very few product managers in tech are trying to reduce CO₂ emissions. I’m sharing a practical guide to quickly start reducing your product’s CO₂ emissions.
date: 2022-11-17
image: /img/data-centre.jpeg
tags:
- post
layout: layouts/post.njk
canonical: "https://www.harryvos.com/posts/product-managers-reduce-co2/"
---

![Black and white aerial view of a data centre as the sun sets](/img/data-centre.jpeg "Data centre")

Photo: [Some rights reserved](https://creativecommons.org/licenses/by/2.0/) by [Chad Davis](https://www.flickr.com/photos/146321178@N05/). Desaturated from the original.

We're witnessing the devastating effects of the climate crisis. Yet very few product managers working in tech are trying to reduce CO₂ emissions. I’m sharing what I hope is a practical guide to quickly start reducing your product’s CO₂ emissions. I also show how to benchmark carbon emissions using my most recent product launch, GOV․UK Forms, as an example.

## Why so few product managers are talking about product CO₂ emissions

Make it effortless. That’s what we say. We build products that are so easy, they hide all the complexity. Somewhere, our software uses hardware to send information across the world. Most products run in cloud data centres. So it’s likely most of us will never see the hardware that keeps our products running. We might have once ventured into a basement and heard the whirr of fans keeping servers cool. Not any more. For most of us, that audible reminder of energy use has long gone.

Most tech products emit CO₂. I think part of the reason we don’t talk about it is because cloud infrastructure makes it almost invisible. Yet, as product managers, we’re good at measuring things to make them more visible. If we don’t, who will?

The [IT sector was estimated to have emitted 3 to 3.6% of greenhouse gases in 2020](https://doi.org/10.1016/j.jclepro.2017.12.239), overtaking [flights](https://theicct.org/sites/default/files/publications/ICCT_CO2-commercl-aviation-2018_20190918.pdf). We can’t wait for hardware manufacturers and cloud providers to reduce CO₂ emissions. As product managers, we have an opportunity right now to reduce the CO₂ emissions of our software.

## How to measure a product’s CO₂ emissions

Very basically, the more data our software transfers back and forth, the more CO₂ our product emits. Luckily, there’s some great open source tools to calculate CO₂ emissions. You just need to know how much data you’re transferring.

For publicly-available web pages, this is easy to measure with [Website Carbon](https://www.websitecarbon.com/). If you want to automate measuring many pages over time, you can use their API.

It’s a little more effort to set up for products that might not have publicly-available URLs. For example, certain web apps, iOS, Android, MacOS, Windows or Linux apps. The Green Web Foundation has a tool which you can build into your apps. It's called [CO2.js](https://developers.thegreenwebfoundation.org/CO2js/overview/). If you feed it a quantity of bytes that your apps transfer or process, it’ll throw out grams of CO₂ emitted. You could use it to analyse which of your features or apps are most carbon intensive.

Even better, don’t spot high emissions parts of your product once you’ve shipped. Instead, build in a carbon budget to your development workflow. You could only allow people to merge pull requests if the changes keep the app below its carbon budget. This might encourage getting rid of unnecessary code before adding new code.

Your organisation might have specific carbon emissions commitments. In other cases, it might be hard to introduce CO₂ emissions into regular product performance conversations. Though just because nobody is asking the question, it doesn’t stop us from sneaking in an extra slide. After the rest of your objectives and key results (OKRs), try it out and ask for feedback. Each quarter, you could report the total grams of CO₂ emitted when you use every feature in your product. Have the emissions gone down? If not, why not? Are we getting close to using up our carbon budget for the product?

## Carbon benchmarking GOV․UK Forms

As well as measuring a product’s CO₂ emissions, we can also compare it to alternatives. I’ve made some rough calculations using my most recent product launch as an example. [GOV.UK Forms](https://www.forms.service.gov.uk/) makes it easy to create accessible online forms for the UK government website, GOV․UK. without needing any technical knowledge.

Before customers start using GOV․UK Forms, they are generally using PDF forms sent over email. Some big organisations in the UK government make you send in forms by post. I've compared carbon emissions across different ways of completing government forms. I've used these three estimates:

- 35,000mg of CO₂ emitted when posting a paper form with supporting evidence in a large letter with Royal Mail

- 9mg of CO₂ emitted when sending a PDF form and evidence over email

- 7mg of CO₂ emitted when completing an online form and submitting evidence with GOV․UK Forms

[See detailed calculations and sources](https://docs.google.com/spreadsheets/d/1BILwwyCM2m0v8JUOG9aK1CEcAqwRb6rG03su_XwXN1o/edit?usp=sharing).

If a form is sent in 10,000 times a year, and they start using GOV․UK Forms, they could expect to see around:

- 35kg of CO₂ emissions avoided per year, which is more than [driving 100km in an average car](https://CO2.myclimate.org/en/portfolios?calculation_id=5228804)

Or if a form is sent in 100,000 times a year:

- 350kg of CO₂ emissions avoided per year, which is more than driving 1000km in an average car

That’s just for one form. With around 8,000 PDF forms on GOV․UK, there’s an opportunity to see around:

- 70 tonnes of CO₂ emissions avoided per year, which is more than driving 10km in an average car every day for 55 years

These simple calculations make it easy to start comparing your product's carbon emissions. As more people start using your product, you can track how much carbon you've avoided emitting. Then celebrate!

It’s good to reduce a product’s carbon footprint. Though to reduce the catastrophic effects of the climate crisis, we need zero emissions as soon as possible.

## Use cloud infrastructure that runs on sustainable energy

![Yellow fibre optic cables with green connectors going into network switches in a server rack](/img/green-connectors.JPEG "Green connectors")

Photo by [Kirill Sh](https://unsplash.com/@kirill2020?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/servers?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).

Hardware is the biggest source of emissions in the tech industry. The next biggest chunk comes from data centres using higher emissions power sources. So getting to zero carbon emissions requires cloud providers to use sustainable energy.

For a smaller organisation it might be simple to switch to a more sustainable provider. Though for a larger organisation, it could take some internal lobbying. I struggled to find much information on current energy sources of cloud providers. Though most of them have committed to improve in the future. 🤔

## Share potential CO₂ savings to grow product sales

There's a growing number of ethical consumers and businesses. Showing reduced CO₂ emissions could help to grow your sales or increase conversion. For example, [Organic Basics show how their products’ CO₂ emissions compare to similar products](https://organicbasics.com/pages/impact-index).

Though you should think carefully about what you compare your product to. Don't brag about emitting less CO₂, if you’re still far off zero emissions. Otherwise, you’re probably [greenwashing](https://en.wikipedia.org/wiki/Greenwashing).

## Start small. Test your first page now

You might be thinking, “I’ll get round to this when things quieten down.” If you have one minute, [test your public product page or company home page](https://www.websitecarbon.com/). Then share the result in your team’s group chat.

When you have half an hour in a quieter week, block out time in your calendar and link to this post. Then you can come up with some initial estimates to work on with a developer.

## Sharing

If you think more product managers need to talk about product carbon emissions, please repost this to share it with your network.

To help me write better posts, I’d love to get your feedback.

![Photo of Nyhavn, Copenhagen, with sticky notes on buildings reading, "environmental impact, product management and social impact"​](/img/copenhagen-interests.jpeg "Harry's interests in Copenhagen")

Photo on screen: [Some rights reserved](https://creativecommons.org/licenses/by/2.0/) by [Jorge Franganillo](https://www.flickr.com/photos/franganillo/).

I’ve recently moved to Copenhagen, Denmark. I'm looking for my next product management role with opportunities for environmental or social impact. If you’re interested, please [connect](https://www.linkedin.com/in/harryjvos/) and let’s get kaffe!
