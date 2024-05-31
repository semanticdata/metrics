# 📒 Markdown Template Source Example

<%- await include(`partials/rss.ejs`) %>

## 🎈 Embedding SVG metrics on-the-fly

<%- await embed(`example-starred-topics`, {topics:true, topics_details:"percentage, bytes-size", config_display:"large"}) %>
