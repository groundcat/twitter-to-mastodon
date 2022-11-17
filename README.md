# twitter-to-mastodon

 Cross-post from Twitter to Mastodon

- Parse tweets with any [Nitter](https://nitter.net/about) instance RSS feed
- Automatically cross post tweets from a Twitter account to a Mastodon account.
- Translates to a different language with DeepL API (optional).

## Usage

Configure the `.env` file with your Twitter, Mastodon, and DeepL (optional) credentials.

Run the script with

    main.py <rss_feed_url> <mode>
    # Mode: 'title' - Use title, 'description' - Use description

Set up a cron job to run the script periodically.
