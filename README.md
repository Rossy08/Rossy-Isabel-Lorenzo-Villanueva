# Rossy-Isabel-Lorenzo-Villanueva
[build]
  publish = "public"
 
[[plugins]]
  package = "netlify-plugin-submit-sitemap"
 
    [plugins.inputs]
 
    # The base url of your site (optional, default = main URL set in Netlify)
    baseUrl = "https://rossy-lorenzo-c3ab65.netlify.app/"
 
    # Path to the sitemap URL (optional, default = /sitemap.xml)
    sitemapPath = "/sitemap.xml"
 
    # Enabled providers to submit sitemap to (optional, default = 'google', 'bing', 'yandex'). Possible providers are currently only 'google', 'bing', 'yandex'.
    providers = [
        "google",
        "bing",
        "yandex"
]
