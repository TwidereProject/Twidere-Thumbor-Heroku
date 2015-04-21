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
5. Find **Connect to Github** in **Deploy** segment, gives Heroku your Github access, then type **the repo name that you've forked**, click **Connect**.
6. Find **Manual deploy**, click **Deploy Branch**.
7. Done!
8. Please note a Thumbor running without security key is dangerous, you'd better to change it. It's located in thumbor.conf. uncomment and set ````SECURITY_KEY```` to your key if you can.

##Support my work

**Donation methods**

* Me: mariotaku.lee[AT]gmail.com

* Our designer: pay[AT]uucky.me

PayPal & Alipay accepted.

Bitcoin: 1FHAVAzge7cj1LfCTMfnLL49DgA3mVUCuW