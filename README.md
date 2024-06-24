

# Evaluating content using LLMs

This process is guided by [Google's helpful content guidelines](https://developers.google.com/search/docs/fundamentals/creating-helpful-content), and uses an LLM to evaluate content.

Each article is sent to ChatGPT to check if this article satisfies a certain criterion:

* Does the content provide a substantial, complete, or comprehensive description of the topic?
* Does the content provide insightful analysis or interesting information that is beyond the obvious?
* etc..

## Bulk prompting
The process of [creating prompts in bulk](https://blog.adver.tools/posts/bulk-prompting/) was reduced as much as possible in this simple tutorial.

## Evaluating content in bulk

A concrete example of how to [evaluate content with LLMs in bulk](https://blog.adver.tools/posts/llm-content-evaluation/) was created.

## Include crawling and run concurrently

To make the process more comprehensive, we can use crawling to obtain the content we want very efficiently, and then make the requests.
We can run the requests concurrently to stramline the evaluation process.

[This notebook](bulk_content_eval_concurrent.ipynb) shows a full exmaple

## Content evaluation app

Using the above scripts I have an app to [evaluate content with LLMs](https://adver.tools/llm-content-evaluation/), and will be making changes and updating it functionality