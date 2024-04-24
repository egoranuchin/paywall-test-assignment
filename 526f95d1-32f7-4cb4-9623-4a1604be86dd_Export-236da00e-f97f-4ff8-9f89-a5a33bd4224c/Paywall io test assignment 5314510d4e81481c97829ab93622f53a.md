# Paywall.io test assignment

# Remote config localization

> ⚠️ This feature is available with subscription plans [starting with Pro](https://Paywall.io/pricing/).

To scale your app globally, you can localize your no-code paywall with the Remote config localization feature.

This feature allows you to adjust your paywall solution to a more pleasurable experience for users worldwide. It creates versions of the paywall content for various user locales. The altered paywall content includes such as titles, images, fonts, colors, HTML, paywall type — soft or hard, and more.

Having access to the paywall’s contents localization via the Paywall’s web interface allows for easier delivery for the Localization team bypassing the Development team and saving their efforts.

Furthermore, just as with the [Remote config feature](https://docs.Paywall.io/docs/paywalls#paywall-remote-config), it doesn’t require you to release a new app version and pushes changes into live apps instead.

## Add a new locale

1. From the **Paywalls & Products** section of your Paywall **Home** page, open the **Paywalls** tab, and select the one you’d like to add the localization to.
    
    ![image.png](Paywall%20io%20test%20assignment%205314510d4e81481c97829ab93622f53a/image.png)
    
2. On the **Paywall** page, navigate to the **Remote config** tab and select the preferred config display mode: Table or JSON. To add the localization to your paywall’s contents, click the **Add locale** button.
    
    ![image (1).png](Paywall%20io%20test%20assignment%205314510d4e81481c97829ab93622f53a/image_(1).png)
    
3. In the pop-up form, select the preferred localization languages from the expandable list. You can choose more than one language at a time. Once you’re done choosing, click **Add localizations**.
    
    ![image (2).png](Paywall%20io%20test%20assignment%205314510d4e81481c97829ab93622f53a/image_(2).png)
    
4. New locales were added as new columns. You can edit the values of the localized versions of the data in their respective cells. The table view is especially useful when dealing with multiple localizations at once. You can easily push values from your default locale to all the other ones and check for unexpected missing values (treated as `null` in JSON form). Use the three-dotted button to sync values from the default locale.
    
    ![image (3).png](Paywall%20io%20test%20assignment%205314510d4e81481c97829ab93622f53a/image_(3).png)
    
5. Once finished, press the **Save & Publish** button at the bottom of the screen. Alternatively, to reset all changes, press **Discard**.

## Delete a locale

1. From the **Paywalls & Products** section of your Paywall **Home** page, open the **Paywalls** tab, and select the one you’d like to add the localization to.
2. On the **Paywall** page, navigate to the **Remote config** tab and select the preferred config display mode: Table or JSON.
3. Click the **Trashbin icon** next to the locale’s name. In the pop-up form, manually type the name of the locale to exclude the false deletion scenario. Once you’ve finished, click **Delete forever** to delete the locale. The deleted locale will be replaced with the default localization of your paywall.
    
    ![delete.png](Paywall%20io%20test%20assignment%205314510d4e81481c97829ab93622f53a/delete.png)
