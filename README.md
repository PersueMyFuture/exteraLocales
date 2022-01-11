## exteraLocales
Would you like to help us with translation? Then you are at the right place!
Here we will briefly explain how you can help us!

## Translation
We have just one file, which is responsible for the settings: `extera.xml`
You will need to create a folder named "values-**%countrycode%**". **%countrycode%** must be replaced with your country code.
> You can find the country codes [here](https://github.com/championswimmer/android-locales).

## How to use a Git?
It's so easy! First you need to install Git (i recommend **cli**) to your PC/device.

Now you need to clone the repository using command:
```
git clone https://github.com/exteraSquad/exteraLocales/
```
Add your changes, save them and create a commit with those changes:
```
git add *
git commit -a -m "Translations for values-**%countrycode%**"
git push origin main
```
