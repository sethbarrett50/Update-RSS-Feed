# update_RSS_Feed

This python script uses the `BeautifulSoup4` library (bs4) to parse a HTML document and update the contents of a div with the class "blog" as a new item in an RSS feed.

## Prerequisites

- Python 3
- BeautifulSoup4 (bs4)

## Installation

1. Clone the repository:
git clone https://github.com/[YOUR_USERNAME]/update_RSS_Feed.git
2. Navigate to the repository directory:
cd update_RSS_Feed
3. Install the required libraries:
pip install -r requirements.txt


## Usage

1. Modify the `document_name` and `rss_feed_url` variables in the script to match the desired HTML document and RSS feed.
2. Run the script:
python update_rss_feed.py


## License

This project is released under the Unlicense. See the [LICENSE](LICENSE) file for more information.
