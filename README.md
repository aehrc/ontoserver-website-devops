# ontoserver-website-devops


https://make.wordpress.org/cli/handbook/guides/running-commands-remotely/

https://docs.simplystatic.com/article/51-working-with-wp-cli

https://www.html-tidy.org/

https://github.com/htacg/tidy-html5

https://github.com/validator/validator


```
Enter your Webhook URL here and Simply Static will send a POST request after all files are commited to GitHub.
```

http://www.btellez.com/posts/triggering-github-actions-with-webhooks.html


```
curl -X POST https://api.github.com/repos/:owner/:repo/dispatches \
-H 'Accept: application/vnd.github.everest-preview+json' \
-H 'Authorization: token $TOKEN' \
--data '{"event_type": "$CUSTOM_ACTION_NAME"}'
```

Use latin for encoding

       -latin1
              use ISO-8859-1 for both input and output

```
[2024-08-12 02:51:36] [class-ss-url-fetcher.php:119] http_status_code: 301 | content_type: text/html; charset=iso-8859-1
```