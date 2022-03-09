# Trigedaslator
An iOS app linked to the tv serie 'The 100'. 

In the TV show the protagonists spoke a new language called Trigedaslang, born from an evolution of English. 
Trigedaslator wanted to be a useful tool for all the show's lovers to directly translate from English to Trigedaslang and backwards. 

![1242x2208bb](https://user-images.githubusercontent.com/1354168/155236788-fc9f3121-1907-4fa1-8915-604baa259d01.png)
![1242x2208bb-1](https://user-images.githubusercontent.com/1354168/155236808-e863f548-a4d0-45b4-96e5-76c0d70d3df8.png)

The app was online on the App Store from April 2017 to June 2020 and was downloaded a total of 8K times on iOS devices.

The whole code was designed to work both offline and online, downloading eventual updates of the dictionary when the device was back online. 
Backend was structured on the Parse Server platform (by Facebook), now dismissed. 

This code includes: 

  - <img src="https://cdn-icons.flaticon.com/png/128/4033/premium/4033369.png?token=exp=1646818442~hmac=e76878edc1d3860a8f6615cd3d4f4826" width="15px"> Offline dictionary (updated on application launch with version checking on database);
  - <img src="https://cdn-icons.flaticon.com/png/128/586/premium/586293.png?token=exp=1646818456~hmac=dac1020298cf69ae961be4a469976481" width="15px"> Database access with Parse Platform (deployed on Heroku);
  - <img src="https://cdn-icons.flaticon.com/png/128/1683/premium/1683145.png?token=exp=1646818472~hmac=91f840cae61b98fc71d7b78c7c868901" width="15px"> Text-to-voice library; 
