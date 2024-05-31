# 📒 Markdown Template Source Example

<%- await embed(`example-rss-feed`, {rss:true, rss_source:"https://news.ycombinator.com/rss"}) %>

<%- await embed(`example-rss-feed`, {rss:true, rss_source:"https://news.ycombinator.com/rss", config_display:"large"}) %>

## 🎈 Embedding SVG metrics on-the-fly

<%- await embed(`example-starred-topics`, {topics:true, topics_mode:"icons"}) %>

<%- await embed(`example-starred-topics`, {topics:true, topics_mode:"icons", config_display:"large"}) %>
