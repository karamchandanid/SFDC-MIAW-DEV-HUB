<html lang="en">
<head>
	<title>MIAW</title>
	<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
</head>
<body >
	Hello
	<script type='text/javascript'>
		function initEmbeddedMessaging() {
			console.log('initEmbeddedMessaging');
			try {
				console.log('initEmbeddedMessaging', 'embeddedservice_bootstrap');
				embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
				
				console.log('initEmbeddedMessaging','embeddedservice_bootstrap','init');
				embeddedservice_bootstrap.init(
					'00D0o0000016oQo',
					'Github',
					'https://devhubdk-dev-ed.my.site.com/ESWGithub1717475956316',
					{
						scrt2URL: 'https://devhubdk-dev-ed.my.salesforce-scrt.com'
					}
				);
				console.log('initEmbeddedMessaging','embeddedservice_bootstrap','done');
			} catch (err) {
				console.error('Error loading Embedded Messaging: ', err);
			}
		};
	</script>
	<script type='text/javascript' src='https://devhubdk-dev-ed.my.site.com/ESWGithub1717475956316/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
