# google-pagerank

Node module for fetching Google Pagerank.

This module implements the Jenkins hash in Javascript and uses the Google Toolbar endpoint to grab pagerank for any url.

## As a node module

    var pagerank = require('google-pagerank');
    pagerank('http://ianww.com', function(err, rank) {
      console.log('Got pagerank', rank);
    });
    
    ==> Got pagerank 3

## Command Line Usage

    node index.js "http://ianww.com"
    ==> 3
