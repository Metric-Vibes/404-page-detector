# 404-page-detector

This GTM (Google Tag Manager) custom template enables you to detect 404 error pages on your website and push an event to the `dataLayer` when such pages are encountered. By using this template, you can track when users land on pages that do not exist (broken links, removed content, or mistyped URLs) and take appropriate actions to improve your site’s performance and user experience.

![image](https://github.com/user-attachments/assets/57dd2a59-7ecc-455a-a838-3363f323bf0a)


## Features
- **Automatic 404 Error Detection**: Detects if a user lands on a 404 error page by using a fetch API.
- **DataLayer Event Push**: Pushes a custom event (`errorPage`) to the GTM `dataLayer` when a 404 page is detected, allowing you to trigger other tags or send data to analytics tools.
- **Fully Customizable**: You can modify the detection criteria or the event structure as needed.

## How to Use

1. **Add Template to GTM**: Download or copy the sandboxed JavaScript code from this repository and create a new Custom HTML Tag in GTM.
   
2. **Trigger on All Pages**: Set up a trigger to fire the 404 detection tag on all page views or specific pages as per your needs.

3. **Configure Your Analytics Tool**: Use the `errorPage` event in your analytics tool (such as Google Analytics 4) to track how many users encounter 404 errors and on which pages.

4. **Optional**: Set up custom actions based on the `errorPage` event. For instance, redirect users, display helpful suggestions, or automatically notify the team to fix broken links.

This error detection API can also be integrated directly into your browser without the need for GTM. For assistance, feel free to contact us.

## Use Cases

### 1. **Identify Broken Links on Your Website**
- By detecting 404 error pages, you can quickly identify broken internal and external links that are leading users to non-existent pages.
- Use this information to prioritize fixing these links, improving your site's SEO and user experience.

### 2. **Analyze User Behavior on Error Pages**
- Track user behavior when they land on a 404 page. Understand how users got there (referrals, mistyped URLs, old links) and how they behave afterward (e.g., do they leave the site or continue browsing?).
- This can help in reducing user drop-off and improving page navigation.

### 3. **Monitor Pages Causing User Friction**
- Use the data to identify patterns of friction. If many users are encountering a 404 page from a certain referral or page, it may indicate a systemic problem with your site navigation or external sources linking to your site.
- You can then focus on enhancing your website’s UX to minimize such friction.

### 4. **Enhance Conversion Optimization**
- For e-commerce and other goal-based sites, reduce the impact of broken links that lead to 404 errors and affect conversions. Identify critical conversion paths and ensure smooth navigation by addressing these errors.

### 5. **Automate 404 Error Notifications**
- Set up automated alerts or workflows when 404 errors are detected. This can help your development or content management team quickly address and fix broken links before they cause further user frustration.

## Customization Options
- Modify the detection logic to suit different scenarios, such as checking for specific URL patterns or adding more keywords that might signify a 404 error page on your website.
- Change the `dataLayer` event name from `errorPage` to something that aligns with your existing GTM naming conventions.

## License
This project is licensed under the Apache 2.0 License.

---

## Contributing
If you’d like to contribute, feel free to fork the repository and submit a pull request. Any feedback or suggestions are welcome.

## Contact
For questions, issues, or suggestions, please contact us via sales@metricvibes.com.

---

With this GTM template, you can seamlessly track and analyze 404 error pages, helping you maintain a better-performing and more user-friendly website.

---

Feel free to adjust any details like contact information, repository links, or additional customization steps to fit the specifics of your repo.
