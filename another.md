<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
  </head>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'ja'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DGC000005sQNw',
				'TestEmbeddedServiceDeployment',
				'https://circlace131-dev-ed.develop.my.site.com/ESWTestEmbeddedServiceDep1739843002083',
				{
					scrt2URL: 'https://circlace131-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://circlace131-dev-ed.develop.my.site.com/ESWTestEmbeddedServiceDep1739843002083/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
