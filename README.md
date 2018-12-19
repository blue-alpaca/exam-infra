# Eksamen i PGR301

## Oppgaver løst:
* Basis pipeline
* Overvåkning, varsling og Metrics
    * Jeg deaktiverte noen typer metrics for å ikke overskride grensen på 10.
* Applikasjonslogger 
    * Av en eller annen grunn fungerte logger.info bare i welcome-metoden.
    Jeg brukte derfor logger.warn i de andre, fordi meldingene da dukker opp.
    * Det ser ut til at loggingen kun fungerer fra appen deployet til Heroku.

## Instruksjoner for endring av filer:
* Gi filen credentials_example.yml navnet credentials.yml og sett inn egne verdier.
* Sett inn egne verdier i provider_heroku.tf, pipeline.yml, statuscake.tf, og variables.tf.

