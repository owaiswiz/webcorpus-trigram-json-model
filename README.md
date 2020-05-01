A Trigram Model in JSON, created from scraping human written articles and blog post, consisting of over 330 million words (over 2 gigabytes in size).

The file itself is 60MB because statistically insignificant terms with frequency &lt; 5 were filtered out.

The JSON file has a object with simple key value pair entries, where the key is the trigram (each word is joined by a single space) and the value is the frequency of its occurrence in the corpus scraped.

A usecase: [Detecting Spun Content using n-gram analysis](https://owaiskhan.me/post/detecting-spun-content-programmatically)
