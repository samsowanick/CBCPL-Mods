This project creates a web page that retrieves and displays a random result from Koha.

Create two sql reports in koha; one to get 250 items from a collection, the other to get the item information for that specific biblionumber. Both reports are passed a variable via the URL. One for what collection to query, the other is a random result from the 250 retrieved items. When calling the api, it does not give a completely new result on each call, instead it caches the result (unless the parameter changes in the url). This is why two reports are required.

In order for the call to not be blocked by CORS, you will need to disable CORS. If you are host by a support company, this is something they will need to do.

The sql reports locations and the JSON api URLs need updated to a new instance. CSS and HTML tweeking to match your specific instance. For Title cover images, they are pulled from our discovery layer AspendDiscovery. Will need adjusted as well. Potentailly possible to pull cover images from amazon, but this way our LoT images show too.

Inspiration: [icpl.org/book-cover/surprise-me](https://www.icpl.org/books-more/surprise-me)
