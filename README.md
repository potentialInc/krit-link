# krit-link

Redirect hop for defense-grant-watch Slack alerts. 국방기술진흥연구소 (krit.re.kr) post pages
refuse a request with no Referer, which is what a click from the Slack app sends. This page
forwards `?krit=<post number>` to that post with a referrer. It accepts digits only, so it
cannot redirect anywhere else.
