# campaigns_postman_tests

To set up:
> npm install -g newman

To run tests:
> newman run "Campaigns Service.postman_collection.json" -e TEST.postman_environment.json

Replace TEST with PROD, SANDBOX or PLAYPEN depending on which environment you want to test

You could probably write a script to do that better.
