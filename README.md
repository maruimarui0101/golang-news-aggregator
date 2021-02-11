# Golang News Aggregator

An application of a day's worth learning of Golang from scratch; a news aggregator that is able to scrape off the Washington Post' stories via the xmlsitemap. A single page resource displaying a table of the story URL and the keywords associated to each story

## Pre requisites

- Golang (application written in version 1.15.8)

## Running the application

The application can be run assuming that the above pre-requisites have been met via:

`go run NewsAgg.go`

A notification appear requesting permissions for the applications to have network access, approve it and navigate to `https://localhost:8080/agg/` in order to access the aggregation page 