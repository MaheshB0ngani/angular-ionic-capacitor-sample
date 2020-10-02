"# angular-ionic-capacitor-sample" 

Install all the dependencies.
`npm i`   

Run this to test your application working fine on browser.
`ionic serve`
    

All good!!
Run the following.

`ionic integrations enable capacitor`


`ionic build`

www/ folder must exist before running this.
`ionic capacitor add android`

Now you can run `npx cap open android` to launch Android Studio
Or you can run the below command 
`ionic capacitor run android`

For live reload run the following
`ionic capacitor run android -l --host=192.168.43.73`

Ref: 

[deploying-to-mobile android/ios](https://ionicframework.com/docs/angular/your-first-app/6-deploying-mobile)
[live-reload](https://ionicframework.com/docs/angular/your-first-app/7-live-reload)
