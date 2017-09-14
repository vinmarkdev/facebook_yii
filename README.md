# facebook_yii
test component to use Facebook Account SDK

## Instalation:

### 1) use composer to add dependency

composer require vinmarkdev/facebook_yii

### 2) add in yii config file

'components' => [
	...

	'facebook' => [
	    'class' => 'vinmarkdev\facebook_yii\SdkFacebook',
	    'app_id' => '{app_id}',
	    'app_secret' => '{app_secret}'
	],

	...
]