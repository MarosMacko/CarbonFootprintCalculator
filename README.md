# CarbonFootprintCalculator
Calculate your carbon footprint, and find out how much you have to do to eliminate it!
This repo is in the alpha state. It works, but oh my, it is ugly. Waiting to be implemented on actual site :)
___

# What is "Carbon footprint"?
A carbon footprint is historically defined as the total emissions caused by an individual, event, organisation, or product, expressed as carbon dioxide equivalent.
[https://en.wikipedia.org/wiki/Carbon_footprint](https://en.wikipedia.org/wiki/Carbon_footprint)

# Who is this for?

This calculator is for anyone using electricity, who wants to know how much carbon footprint they produce, and eliminate it (by presenting the output equivalent to trees planted). This is called offsetting the carbon footprint. Of course, electricity is just a fraction of our total carbon footprint. But if you consume a lot of it, you might want to do something. Originally the calculator was made for Cryptocurrency miners, as they are very energy intensive.

# How accurate is this?

Well... There are numbers of factors which we have to talk about. 

- The most important thing is to know where your electricity comes from. Unless you have 100% self-sufficient source of electricity, or you have exact data from your electricity provider, you don't know where exactly it is from. 
- We provide list of countries and their energy source percentages. But, some countries are very big, and the national average may not be even close to where your electricity comes from (source at the end of this document). Also, countries can buy and sell electricity from other countries. 
- We also provide median values for how much CO2 each power plant type produces. Again, they are just median (most "common") values (source at the end of this document) for each power plant type. This may differ based on exact model, age, or system used in each particular power plant. 
- Apart from that, calculations are straight forward and precise.

# How can I offset my carbon footprint?

- [https://trees.org](https://trees.org) is the site to go, if you ask me. But that is up to you. Be responsible for your footprint on the planet!
- How often to donate you ask? It takes few years for the tree to grow up to full potential, but then it "works" for you for around 40 years. This is continuous, so while you consume the same amount of energy every year, the tree manages to take care of that same amount - as calculated.


# Sources

### Energy sources by country
- [http://wdi.worldbank.org/table/3.7](http://wdi.worldbank.org/table/3.7) (data from 2015)
- You can see/use this information in /Sources folder processed into .xlsx  and .csv formats

### Amounts of CO2 produced per kWh based on power plant type
- Original source: "2014 IPCC, Global warming potential of selected electricity sources"
- Found at [https://en.wikipedia.org/wiki/Life-cycle_greenhouse-gas_emissions_of_energy_sources](https://en.wikipedia.org/wiki/Life-cycle_greenhouse-gas_emissions_of_energy_sources) - read more if you are interested, or want to use other (more optimistic or pessimistic) values for gCO2/kWh calculations

### kG of CO2 eliminated per tree
- According to [https://www.tfaforms.com/4666774](https://www.tfaforms.com/4666774), it is roughly 15.7kg

# Dependencies

We can proudly say that this calculator does not need any dependencies. It is pure HTML, CSS and JavaScript. Just open the html file in any modern web browser (note: not tested, [and won't be] in IE), and you are good to go!
