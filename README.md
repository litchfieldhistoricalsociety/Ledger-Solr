Litchfield Ledger Solr
=========

This is the installation of solr that is configured to work with the Litchfield Ledger.

 This must be running as a service before starting the Ledger app.

 When running locally, you may use the convenience rake task in the ledger:

 rake solr:start

 When running on a server, you should create a service in /etc/init.d so that solr will restart automatically if the server is rebooted.
