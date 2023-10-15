## Overview

This project serves as a prototype to demonstrate the potential use of AI in the permitting process. Specifically, we are utilizing generative AI to summarize permitting applications and organize their content by the criteria of permit reviewers to reduce administrative burden and enhance productivity.

## Motivating Problem

Permitting applications can be lengthy –– they can often be many pages and include a large amoung of information which may not be directly applicable to the reviewing agency. This requires application reviewers to manually parse through large amounts of infomration to find key items which they need to review.

## Proposal

We hypothesize that application reviewers can be assisted by AI which summarizes key points of permitting applications, and specifically key point which are related to their agency's equities. These summaries can 1) reduce the amount of time it takes for application reviewers to process applications, and 2) ensure greater completeness in review by ensuring that key points of applications are highlighted from reviewers.

## Data & Methodology

Permitting applications were downloaded from [link], provided by [source]. ... more information about inventory.

[link] was used as a set of criteria used to inform the content and organization of the summary of the permitting applications.

A LLM model (ChatGPT: gpt-4) was used to summarize each response based on the prompt:
