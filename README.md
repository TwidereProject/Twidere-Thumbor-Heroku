# Twidere-Thumbor-Heroku
Default configuration for deploying Thumbor to heroku

----

##Deploy within one minute
###Heroku

You don't need any other tool except a browser to deploy this.

1. Fork this repo
2. Create an application in **Heroku Dashboard**, you will be redirected to **Settings** of your newly created application.
3. Find **Config Variables** in **Settings** segment, click **Reveal Config Vars**, then press **Edit**
4. Add a new variable, the **key** is ````BUILDPACK_URL````, and the **value** is ````https://github.com/heroku/heroku-buildpack-multi````, click **Save**.
5. Again, add a new variable, the **key** is ````THUMBOR_SECURITY_KEY````, and you should define your own key and put it into **value**. Please note a Thumbor running without security key is dangerous, you'd better to change it.
6. Find **Connect to Github** in **Deploy** segment, gives Heroku your Github access, then type **the repo name that you've forked**, click **Connect**.
7. Find **Manual deploy**, click **Deploy Branch**.
8. Done!

##Support my work

**Donation methods**

* Me: mariotaku.lee[AT]gmail.com

PayPal & Alipay accepted.

Bitcoin: 1FHAVAzge7cj1LfCTMfnLL49DgA3mVUCuW
