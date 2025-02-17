<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DKc000001UElS',
				'GitHubPagesWebEmbeddedServiceDeployment',
				'https://ci1737333738963.my.site.com/ESWGitHubPagesWebEmbedded1739766140357',
				{
					scrt2URL: 'https://ci1737333738963.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ci1737333738963.my.site.com/ESWGitHubPagesWebEmbedded1739766140357/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
