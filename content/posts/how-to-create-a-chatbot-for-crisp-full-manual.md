# How to Create and Set Up a Chatbot for Crisp

In today's digital landscape, having a chatbot on your website can significantly enhance user experience and streamline customer support. [Crisp]((https://crisp.chat) is an all-in-one business messaging platform that allows you to integrate a chatbot seamlessly. This article will guide you through the process of creating and setting up a chatbot for Crisp, ensuring that you can provide instant assistance to your users.

## Step 1: Understanding Crisp

Before diving into the setup process, it's essential to understand what Crisp is and how it can benefit your business. Crisp is a messaging platform that consolidates team communication, customer interactions, and data management in one place. It offers various cool features, including live chat, email and other channel integration, segments, CRM, and many other things allowing businesses to engage with customers effectively. 

Here is the typical message box installed on a website:

![image](https://github.com/user-attachments/assets/6edf9e33-bc96-4311-b8b7-ba385ff63f79)

And here is it how it looks like with using the Enum chatbot:

![image](https://github.com/user-attachments/assets/06311bc2-4b37-462e-af6e-a8550e32ea63)


### Benefits of Using a Chatbot (specifically an Enum Chatbot)

Here are the benefits of using a chatbot for a business:

1. **24/7 Availability**: Chatbots can provide round-the-clock support, ensuring that customers can get assistance at any time, even outside of regular business hours.

2. **Instant Response**: Chatbots can respond to customer inquiries immediately, reducing wait times and improving customer satisfaction.

3. **Cost Efficiency**: By automating responses to common questions, businesses can reduce the need for a large customer support team, leading to cost savings.

4. **Scalability**: Chatbots can handle multiple conversations simultaneously, allowing businesses to scale their customer support without a proportional increase in resources.

5. **Consistency in Responses**: Chatbots provide consistent answers to customer inquiries, ensuring that all users receive the same information and reducing the risk of human error.

6. **Data Collection and Insights**: Chatbots can gather valuable data from customer interactions, helping businesses understand customer preferences, behaviors, and pain points.

7. **Lead Generation**: Chatbots can engage visitors on a website, qualify leads, and collect contact information, helping businesses build their customer base.

8. **Enhanced User Experience**: By providing quick and accurate responses, chatbots improve the overall user experience, leading to higher customer satisfaction and loyalty.

9. **Multilingual Support**: Many chatbots can communicate in multiple languages, allowing businesses to cater to a diverse customer base - by default, the Enum chatbot responds in the language of a question - unless you told it to act differently.

10. **Integration with Other Tools**: Chatbots can be integrated with various business tools and platforms, such as CRM systems, email marketing, and social media, streamlining operations. The Enum chatbot supports all the integration provided by the Crisp (see the [full list of supported integrations here](https://www.enumhq.com/docs/why-enum#integration-with-other-channels-that-are-integrated-into-crips)).

11. **Personalization**: Chatbots can use customer data to provide personalized recommendations and responses, enhancing the customer experience.

12. **Handling High Volumes of Inquiries**: During peak times or promotional events, chatbots can manage a high volume of inquiries without compromising service quality.

13. **Feedback Collection**: Chatbots can easily collect feedback from customers, helping businesses improve their products and services.

14. **Reduced Human Workload**: By handling routine inquiries, chatbots free up human agents to focus on more complex issues that require personal attention.

15. **Improved Response Time**: Chatbots can quickly retrieve information and provide answers, significantly improving response times compared to traditional customer service methods.

16. **Proactive Engagement**: Chatbots can initiate conversations with users, offering assistance or information based on user behavior, which can lead to increased engagement and conversions.

17. **Training and Support**: Chatbots can assist in training new employees by providing them with information and resources, as well as answering their questions.

18. **Brand Image Enhancement**: Implementing a chatbot can enhance a business's image as a tech-savvy and customer-focused organization. The Enum chatbot can read the images uploaded by the user, as well as recognize the voice recording (see [the full list of supported files here](https://www.enumhq.com/docs/why-enum#can-read-and-understand-media-files)).

By leveraging these benefits, businesses can improve their customer service, increase efficiency, and ultimately drive growth. 


## Step 2: Registering for Crisp

To get started, you need to create an account on Crisp. Follow these steps:

1. **Visit the Crisp Website**: Go to [Crisp's official website](https://crisp.chat).
2. **Sign Up**: Click on the "Sign Up" button and fill in the required information, including your email address and password.
3. **Verify Your Email**: Check your email for a verification link and click on it to activate your account.
4. **Set Up Your Workspace**: After verification, you will be prompted to create a workspace for your business. Enter your business name and website URL.
5. **Create A Website** Then, you need to add your website to install the chatbox, [read the official manual here](https://help.crisp.chat/en/article/how-do-i-add-a-live-chat-to-my-website-10wcj3l/)).

## Step 3: Installing an Enum Chatbot Plugin

Once your Crisp account is set up, you can add the Enum chatbot. Here’s how:

1. **Access the Dashboard**: Log in to your Crisp account and navigate to the dashboard.
2. **Go to Plugins section**: Install the "Support AI Chatbot" plugin by clicking "Install".
3. **Create an Enum Account**: Right after that you will be redirected to the Enum registration page. Your data (a special token by Crisp) will be passed along to provide a secure installation and smooth experience. Confirm your email and log in to the Enum dashboard.
4. **Add A New Datasource**: For a new account, we always create a project that already has the Crisp chatbot installed. You can change your project's title and description. Now, you need to create a data to be indexed and passed to the chatbot. Navigate to your project, select a data sources from a menu and create a corresponding data source.
5. **Crawl Your Website** Say, you want to use your own website as a data source. It needs to be crawled by our spider to find all the links and extract the data.
6. **Index Your Data** Now, select the pages you want to be indexed, and click the *Start Indexing* button. As soon as it's done, your chatbot is almost ready!

## Step 4: Configuring Your Chatbot

After creating your chatbot, you need to configure its settings to ensure it meets your requirements. Here are the key settings to consider:

### 1. **Customizing the Chatbot's Appearance**

- **Chatbot Icon**: Choose an icon for your chatbot. You can select from default options or upload your own image.
- **Chatbot Name**: Set a name for your chatbot that will be displayed to users.

### 2. **Setting Up Responses**

- **Default Responses**: Create default responses for common questions. This can include greetings, FAQs, and information about your products or services.
- **Custom Behavior**: Define how your chatbot should behave in different scenarios. For example, you can set it to ask for user information before providing assistance.

### 3. **Adding Buttons and Quick Replies**

Enhance user interaction by adding buttons and quick replies. This allows users to navigate through options easily. You can create buttons for:

- **Feedback**: Collect user feedback on their experience.
- **Request Human Assistance**: Allow users to connect with a human agent if needed.
- **Custom Links**: Redirect users to specific pages on your website.

### 4. **Integrating Data Sources**

To make your chatbot more effective, integrate data sources that it can reference when answering questions. You can upload documents, scrape your website, or enter URLs manually.

## Step 5: Testing Your Chatbot

Before launching your chatbot, it’s crucial to test its functionality. Here’s how to do it:

1. **Use the Live Test Feature**: Crisp provides a live test feature that allows you to interact with your chatbot as if it were live on your website.
2. **Simulate User Interactions**: Ask various questions to see how the chatbot responds. Check if it provides accurate information and follows the defined logic.
3. **Make Adjustments**: Based on your testing, make any necessary adjustments to improve the chatbot's performance.

## Step 6: Launching Your Chatbot

Once you are satisfied with your chatbot's performance, it’s time to launch it on your website:

1. **Install the Crisp Chatbox**: Follow the Crisp documentation to install the chatbox on your website. This typically involves adding a code snippet to your website's HTML.
2. **Activate Your Chatbot**: In the Crisp dashboard, ensure that your chatbot is activated and ready to respond to user inquiries.

## Step 7: Monitoring and Improving Your Chatbot

After launching your chatbot, it’s essential to monitor its performance and make improvements over time:

- **Analytics**: Use Crisp's analytics tools to track user interactions, response times, and satisfaction rates.
- **User Feedback**: Collect feedback from users to identify areas for improvement.
- **Regular Updates**: Continuously update your chatbot's responses and features based on user needs and business changes.

## Step 8: Integration with the Crisp chatbot

Crisp has its own chatbot but it doesn't allow to use of voluntary data sources as us and has its restrictions. Nevertheless, we have many cases of successful integration of the Crisp chatbot with our chatbot. The features implemented in the Enum chatbot allow it to complement the Crisp chatbot, not compete with it.

## Conclusion

Creating and setting up a chatbot for Crisp is a straightforward process that can significantly enhance your customer support capabilities. By following the steps outlined in this article, you can create a chatbot that provides instant assistance, collects valuable data, and improves overall user experience. Remember to monitor its performance regularly and make adjustments as needed to ensure it remains effective and relevant to your users' needs. 

## Useful resources

- [The official Crisp manual on installing and using the Enum chatbot](https://help.crisp.chat/en/article/how-can-i-create-an-ai-chatbot-using-chatgpt-s8b0q8/)
