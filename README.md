# WebsiteScraper

The New York Times Mongo News Scraper gathers articles based on a custom cheerio scraper of the New York Times homepage. The scraped articles are saved into a mongo database. The scraped articles can either be saved or commented on. The comment feature is a separate model that communicates with a comment collection in the mongo database. The comments are then linked with their appropriate article.
