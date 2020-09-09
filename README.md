# magento-2 plugin
1. upload app/code/Gateway (all files and folder) at you server end
2. Run below command:
	1. php bin/magento module:enable Gateway_Tap
	2. php bin/magento setup:upgrade
	3. php bin/magento setup:static-content:deploy
Configuration:
1. goto Admin->Store->Configuration->Sales->Payment Method->Tap, and fill the details here and save them
	* Enabled - Yes
    * Title - Tap
	* Test Public Key - pk_test_Vlk842B1EA7tDN5QbrfGjYzh
	* Test Secret Key - sk_test_kovrMB0mupFJXfNZWx6Etg5y
	* Staging Mode - Yes
	
goto Admin->System->Cache Management and Clear all Cache
Now you can collect payment via Tap
Screenshots:
 1.Knet Configuration Page  https://www.screencast.com/t/ZfqtEBd4e
 2.Tap Configuration Page   https://www.screencast.com/t/7wMv6zmT



