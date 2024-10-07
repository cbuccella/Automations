# Blog and LinkedIn Post Automation Guide

## Prerequisites
* Make.com JSON template (provided in this folder)
* API Keys:
   * Perplexity
   * Claude
   * OpenAI
* Google connection to Make.com

## Setup Instructions

Download the template to get started on Make.com here: 

Connecting Google Sheet to Start the Automation

1. Add Make.com Extension
   * Go to the Extensions tab in your Google Sheet
   * Select Add-ons and search for Make.com
   * Install and activate the Make.com add-on

2. Create a Unique Webhook
   * In Make.com, create a new automation template
   * Generate a unique webhook URL as part of your scenario
   * Copy the webhook URL

3. Connect Webhook to Google Sheet
   * Open the Make.com extension pane on the right side of your Google Sheet
   * Paste the webhook URL into the appropriate field

4. Map Headers
   * Ensure headers are correctly mapped to sync data between the sheet and the Make.com scenario

Google Sheets Overview
* Sheet 1: Blog Outputs – For storing blog-related data and outputs
* Sheet 2: LinkedIn Route Outputs – For LinkedIn post data and related outputs

Image Prompts
* Image prompts generated within this process can be used in AI image generators like Midjourney, Runway, or Dall-E to create visuals

## How It Works
1. The webhook monitors changes in Column A (Filters)
2. Populate the title(s) of your blog posts into Column B (Blog Titles)
3. The automation is triggered when the filter in Column A is set to 'Ready'
4. The automation will run for a few minutes, then input the corresponding information into the appropriate row on the Sheet

## Additional Information
* The included Make.com template has notes attached to each node for more information and context

## Prompts Used in This Automation
* The prompts used throughout this Make.com automation can be found in the "[SAMPLES_Blog_Prompt_Outlines](https://drive.google.com/drive/folders/152GJHO09GDiYktjpvVdrmBxogkja7Ry_?usp=sharing)" folder. 


