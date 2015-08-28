# Welcome to the Worldwide Restaurant Guide!

This is the final project for the course ["Git From Zero"](https://www.udemy.com/essential-git/) in Udemy.

## How it works

The idea is to have folders for each country, state/province and city. 

The country should be the country code as per the [ISO 3166-1 alpha-2](http://en.wikipedia.org/wiki/ISO_3166-1) two letter country code. For example, "Venezuela" should be listed as "VE".

Then inside you add the state/province full name (if you don't see it already) and then add the full name of the city, but here's an important rule: use underscores instead of spaces (i.e. New_York and not New York).

At that point you can either add or edit the "restaurants.md" markdown file, where you can add your favorite restaurant as follows:

```
[Restaurant Name] - [Type of cuisine]
[Brief description of why you liked it]
[Full address in one line]
[Phone number]
[Website (optional)]
```

And then leave an empty line to add another one.

You can take a look at any [restaurants.md](Restaurants/US/New_York/New_York/restaurants.md) file to see a sample.

## Git procedure

You need to fork the repo first, then clone in your environment. Then you need to add or edit the appropriate restaurants.md file, commit and then submit a pull request.

Once I check your pull request and see that it's okay, I will add it to the main repository and will follow your username.

Remember: if you're going to update a listing afterwards, always do a "git pull" before changing anything! That way you'll have the latest changes locally.

If you have any questions, please post it on the Udemy course forum or email me [jorge@fromzero.io](mailto:jorge@fromzero.io)

Happy coding!
