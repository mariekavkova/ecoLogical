# ecoLogical?
Final project for the Building AI course

<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->


## Summary

Plastic or paper? Meat or veggies? Car or bus?
More and more people try to reduce an impact we as a humanity has on our planet by changing their lifestyles and prefering environment friendly options such as recycling, using less plastic, eating plant based meals or prefering public transportation. But are those solutions allways the best? Is it really better to use cotton bag for storing rice instead of plastic?  What if producing this cotton bag costs a lot more emissions? What if it uses a lot more water or you have to transport those bags at huge distances?

We tend to look solely on a final product and do not realize the complex mechanisms behind. But what if we have a tool which would show us the whole journey of a product from materials used, through fabrication and finally packaging and transport or an impact a sport activity or other hobbies have on our environment and suggest adjustments. 

An application ecoLogical? would use AI to guide us through our complex world and help reduce carbon emissions and other effects we have on our planet.




## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

False data from companies to make their products or activities look better in the app. 

Greenwashing - for example a company focusing its marketing on particular product standing well in app or even being recommended by it while producing other goods with significantly worse score.

A big chunk of different data (products details, energetic specifics about local gym, information about public transports in thousands of cities). The model could work better on some part of the data and poorly on another. In fact the amount would probably be overwhelming at the beginning and the app would have to start with fewer categories.

Security issues - a decent security system would be a non negotiable part of the app, because of the amount of data about our everyday lives

Using more criteria to measure our impact on the environment apart from carbon emissions, for example amount of water used, lesser waste production etc.

Cost - alternatives recommended by the app may not be financially available for everybody. 


## What next?

No matter how important is a behavior of a single person the biggest producers of carbon emissions are large companies. According to CDP reports (https://www.cdp.net/en/articles/media/new-report-shows-just-100-companies-are-source-of-over-70-of-emissions) 100 global companies produce 71 % of all carbon emissions in the world. This app should be an opening which would show people how complex an ecological behavior could be and give us a hint where to put pressure on companies. But a real impact would be making such app for those businesses, for their products, goods and services. 

The variation of the app for companies should include:
Materials used
Production process
Buildings
Packaging
Trasportation
Business partners
And suggestions for optimization.

## Acknowledgments

Sources of inspiration:

Our world in data (https://ourworldindata.org, especially FAQ on plastics (https://ourworldindata.org/faq-on-plastics#are-plastic-alternatives-better-for-the-environment)

Podcast “Za humny” (https://open.spotify.com/show/5ijP5ndQ4zzHoGXRFBtW16?si=274d862e0e474b47), especially episode 37

CDP reports (https://www.cdp.net/en/)


