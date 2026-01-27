# CANDOR

## Transcript Exclusions
`765f6cde-5291-4047-89c1-d71b1e3a413d` excluded due to lack of conversation content (N = 1655 transcripts)

`experiment1` contains [empirica](https://empirica.ly/) code for annotation

## Pre-Reqs
Ensure you have empirica and the npm packages installed  
Have a Google Cloud service account key that has access to the Candor dataset. Some modifications to the code might be needed due to naming conventions and different file paths  
Put the key file in the server folder

## Serving the experiment
```sh
empirica bundle
empirica serve [myexperiment].tar.zst
```

served on port 3000 of the server
