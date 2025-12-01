![banner](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/banners/shopgoodwill.webp)

## What does Goodwill auction Scraper do?

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.5` |
| **Last Update** | Dec 1, 2025 |

---



Our auction Scraper will enable you to quickly get all auctions details from <https://www.shopgoodwill.com/>.

When you provide the URL of an item or a page from Goodwill or Goodwill Digital you will be able to extract such information about the auctions:

For a full list of fields extracted, please see the _Output_ tab.


## 💻 Integration Examples

This repository includes example code showing how to integrate the `shopgoodwill-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---


## How many results can you get with Goodwill auction Scraper?

Goodwill auction Scraper can return hundreds of results on average. However, you have to keep in mind that scraping goodwillauctions.com has many variables to it and may cause the results to fluctuate case by case.
There's no one-size-fits-all-use-cases number. The maximum number of results may vary depending on the complexity of the input, location, and other factors.

Some of the most frequent cases are:

- websites have an internal limit that no scraper can cross
- websites give a different number of results depending on the type/value of the input
- scraper has a limit that we are working on improving

While we regularly run Actor tests to keep the benchmarks in check, the results may also fluctuate without our knowing. The best way to know for sure for your particular use case is to do a test run yourself.

## How much does it cost to scrape auctions from Goodwill?

When it comes to scraping, it can be challenging to estimate the resources needed to extract data as use cases may vary significantly. That's why the best course of action is to run a test scrape with a small sample of input data and limited output. You’ll get your price per scrape, which you’ll then multiply by the number of scrapes you intend to do.

[Watch this video](https://www.youtube.com/watch?v=-wyz2iscZ30) for a few helpful tips. And don't forget that choosing a higher plan will save you money in the long run.

[![Watch the video](https://img.youtube.com/vi/-wyz2iscZ30/0.jpg)](https://www.youtube.com/watch?v=-wyz2iscZ30)

## How to scrape auction listings from Goodwill?

Follow the simple steps below to scrape auction details from Goodwill Digital:

1. [Create](https://console.apify.com/sign-up) a free Apify account using your email.
2. Open [Goodwill auction Scraper](https://apify.com/lexis-solutions/shopgoodwill-scraper)
3. Add a search query or item ID to scrape
4. Click "Start" and wait for the data to be extracted.
5. Download your data in JSON, XML, CSV, Excel, or HTML.

## Results preview

Here is an example of the output from scraping [Guitar](https://shopgoodwill.com/auctions/search?q=guitar) auctions from Goodwill:

```json
[
  {
    "itemId": 220930006,
    "title": "40\" Unbranded Handmade Electric Guitar w/ Gig Bag",
    "description": "<p><strong></strong></p>\n<p><strong>Dimensions (in inches):</strong> 50 x 20 x 8</p>\n<p><strong>Additional Info:...</strong></p>",
    "currentPrice": 18,
    "minimumBid": 19,
    "bidsCount": 5,
    "endsOn": "2025-01-26T18:25:00",
    "images": [
      "https://shopgoodwillimages.azureedge.net/production/339/Items/01-21-2025/5feecdf5-79fc-4ba6-a55a-1e7e7caf6ea3elle_01211.jpg"
    ]
  }
]
```

## Integrations and Goodwill auction Scraper

Last but not least, Goodwill auction Scraper can be connected with almost any cloud service or web app thanks to <a href="https://apify.com/integrations"  target="_blank"> integrations on the Apify platform</a>. You can integrate with Make, Zapier, Slack, Airbyte, GitHub, Google Sheets, Google Drive, <a  href="https://docs.apify.com/integrations"  target="_blank"> and more</a>.

Or you can use <a  href="https://docs.apify.com/integrations/webhooks"  target="_blank"> webhooks</a> to carry out an action whenever an event occurs, e.g., get a notification whenever Goodwill auction Scraper successfully finishes a run.

## Using Goodwill auction Scraper with the Apify API

The Apify API gives you programmatic access to the Apify platform. The API is organized around RESTful HTTP endpoints that enable you to manage, schedule, and run Apify Actors. The API also lets you access any datasets, monitor Actor performance, fetch results, create and update versions, and more.

To access the API using Node.js, use the `apify-client` NPM package. To access the API using Python, use the `apify-client PyPI` package.

Check out the <a  href="https://docs.apify.com/api/v2"  target="_blank"> Apify API reference</a> docs for full details or click on the <a  href="https://apify.com/tunchi/goodwill-auctions/api"  target="_blank"> API tab</a> for code examples.

## Is it legal to scrape Goodwill auctions?

Note that personal data is protected by GDPR in the European Union and by other regulations in different regions of the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. We also recommend that you read our blog post: [is web scraping legal?](https://blog.apify.com/is-web-scraping-legal/).

## Need to scrape more auction data?

👉 Scrape GoDaddy Auctions with [GoDaddy Auctions Scraper](https://apify.com/lexis-solutions/godaddy-auctions-scraper)

👉 Scrape SeLoger with [SeLoger Scraper](https://apify.com/lexis-solutions/seloger-scraper)

👉 Scrape HiBid Auction with [HiBid Auction Scraper](https://apify.com/lexis-solutions/hibid-com-scraper)

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: ShopGoodwill
