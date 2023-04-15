# UFOs
JavaScript, Bootstrap, HTML, Visual Studio Code

https://swilli73.github.io/UFOs/

## Overview of UFOs

#### This analysis was performed to demonstrate newly acquired JavaScript and HTML skills to create an interactive webpage that allows a user to search within a dataset containing North American UFO sightings. The page allows for you to filter the search by date, city, state, country, and shape of the UFO.

## Results

#### Searching through this dataset depending on what you wish to look for is fairly simple—you type in the critera you wish to see in the related field and press the "Enter" key. For example, here is me filtering the dataset by UFO sightings in New Jersey on 1/5/2010. 
![New Joisey](https://i.gyazo.com/10a3bbf09fa6d11777ec11e2c92318ef.png)

## Summary

#### I noticed one drawback of this webpage design, and have two recommendations for further development. 

- Perhaps it is a just limitation of the dataset, but the search filtering is 100% case sensitive and does not account for any differences in case or date format. For example, "benton" is accepted (as it is the first entry in the dataset), but "Benton" is not.
![Benton](https://i.gyazo.com/069e274953b2a896855c478f8cb39b3d.png)

- Further development of the HTML beyond the constraints of this challenge could supplement a cleaner webpage. The "Filter Search" heading being a larger font than the rest of the text on the page, an aligned format for the filters ("Enter State" is longer than "Enter City" due to the amount of characters, leading to the input boxes creating a stairstep look), and the summary text for the page being located under the page header rather than to the right of it and above the dataset.

- Updating the filters to be able to search for keywords in the comments might be beneficial to someone using this data. I suspect that the limitations of the code enforcing case sensitivity in the filter search fields will prohibit being able to search the comments by one to a few words, but with some updates it could be a great improvement to the webpage.
