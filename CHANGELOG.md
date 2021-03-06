Changelog
=========

|Release Version|Date|Description|Ticket|
|---------------|----|-----------|------|
|1.7.1|2014/04/23|MCollective service plugin not working with puppet 3.5.x|MCOP-23|
|1.7.0|2014/02/20|Fully-qualify uses of Process to avoid clashes with process agent|#13|
|1.7.0|2014/02/20|Fix --no-noop and --no-splay under MCollective 2.3.x and 2.4.x|MCOP-5|
|1.7.0|2014/01/10|Change method of running puppet agent to double-fork a foreground run|MCO-31|
|1.6.2|2013/12/04|Change noop to no-op for front-end text|MCO-28|
|1.6.1|2013/10/15|Made --force option correctly imply --no-splay|22860|
|1.6.0|2013/05/08|Increase the DDL timeout to better handle slower servers where puppet startup is slow|20618 |
|1.6.0|2013/05/07|Support controlling Puppet on Windows|19541|
|1.5.1|2013/03/01|Add a --rerun option to the runall command that loops over the nodes forever|19541|
|1.5.0|2013/02/22|Improve error message when a resource does not pass validation|19384|
|1.5.0|2013/02/22|Correctly handle mixed case resource names when determining if a resource is managed|19384|
|1.5.0|2013/02/22|Add the _mco puppet resource_ command|12712|
|1.4.1|2013/02/16|Provide type distribution data in the last_run_summary action|19284|
|1.4.0|2013/02/08|Add support for --ignoreschedules|19106|
|1.4.0|2013/02/08|Add --tags as an alias to --tag|19137|
|1.3.0|2013/02/06|Support custom puppet config locations using plugin.puppet.config|19094
|1.2.1|2013/02/01|Prevent unneeded warning log messages each time status is requested|18956|
|1.2.0|2013/01/17|Add sparkline based summary stat graphs for the entire estate|18704|
|1.1.1|2013/01/16|Add the --runall command|18664|
|1.1.0|2013/01/09|Add the 'mco puppet' application|15472|
|1.1.0|2013/01/09|Report idling time and check if the agent is disabled before attempting to run|15472|
|1.0.0|2013/01/09|Initial release|15472|
