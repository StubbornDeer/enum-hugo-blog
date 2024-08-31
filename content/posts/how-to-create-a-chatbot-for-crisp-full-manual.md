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

![image](https://github.com/StubbornDeer/enum-docs-nextra/assets/91156314/4a38e6cc-1079-482e-b18e-e984215edcdc)

![image](https://github.com/StubbornDeer/enum-docs-nextra/assets/91156314/ab96ce58-abb2-4752-9994-f6607410cf23)

3. **Create an Enum Account**: Right after that you will be redirected to the Enum registration page. Your data (a special token by Crisp) will be passed along to provide a secure installation and smooth experience. Confirm your email and log in to the Enum dashboard.
4. **Add A New Datasource**: For a new account, we always create a project that already has the Crisp chatbot installed. You can change your project's title and description. Now, you need to create a data to be indexed and passed to the chatbot. Navigate to your project, select *Data sources* from a menu and create a corresponding data source.

![image](https://github.com/StubbornDeer/enum-docs-nextra/assets/91156314/5407348c-fac1-4a47-b9a3-b15b9a90267a)

Find all the details [here](https://www.enumhq.com/docs/guide/data-sources).

5. **Crawl Your Website** Say, you want to use your own website as a data source. It needs to be crawled by our spider to find all the links and extract the data.

![image](https://github.com/StubbornDeer/enum-docs-nextra/assets/91156314/104bc6ad-7e2d-457b-bfbf-f4ccc2865b0b)

6. **Index Your Data** Now, select the pages you want to be indexed, and click the *Start Indexing* button. As soon as it's done, your chatbot is almost ready!

The full instructions on installing the Enum plugin can be found [on the documentation](https://www.enumhq.com/docs/chat-plugins/crisp/crisp-installation).

## Step 4: Configuring Your Chatbot

After creating your chatbot, you need to configure its settings to ensure it meets your requirements. Here are the key settings to consider:

### 1: Configure Link Display Settings

Navigate to the *Widget settings* tab of the chatbot's properties

1. **Show Source Links in Response**:
   - Locate the option labeled **Show source links in response**.
   - Check this box if you want the chatbot to include relevant links in its responses.
   - If you want to hide the links, ensure this box is unchecked.

2. **Number of Links to Show**:
   - Find the setting that allows you to specify how many links to display in the chatbot's responses.
   - You can set the maximum number of links to show (e.g., 1 main link and up to 3 additional links).
   - Adjust this number according to your preference.

### 2. **Customizing the Chatbot's Appearance**

1. **Chatbot Name**:
   - Locate the field for the chatbot's name.
   - Enter your desired name for the chatbot, which will be displayed alongside the chatbot icon.

2. **Chatbot Icon**:
   - You have three options for the chatbot icon:
     - **Default Crisp Userpic**: Use the standard userpic provided by Crisp.
     - **Cute Enum Robot Userpic**: Select the predefined cute robot icon.
     - **Custom URL**: Upload your own image by providing a URL. Ensure the image is in a supported format (PNG, JPG, JPEG, BMP) and hosted on a reliable server.

### 3. **Set up Custom behaviour and Automation settings**

Here are the settings available in the Custom Behaviour & Automation section for the Enum chatbot, along with short instructions for each:

1. **Chatbot in Session**:
   - **Wait to Reply**: Check this option if you want the chatbot to respond only after the user provides their phone number or email. Use this if you require contact information before engaging.
   - **Pass the User Name to the Chatbot**: Enable this setting to allow the chatbot to use the user's name if it is known (extracted from their email).
   - **Send This Message When a Conversation Starts**: Enter a greeting message that the chatbot will send when a user initiates a conversation.
   - **Do not show buttons on the greeting message**: With this setting set ON, the chatbot will not show the buttons on the greeting message.
   - **Pause the Chatbot When Agent Joins the Conversation**: Check this box to make the chatbot quiet whenever a human agent joins the chat.
   - **Re-run chatbot when conversation is resolved**: This indicates to re-run the chatbot when you click the "Mark this conversation as resolved" in the Crisp dashboard.
   - **Send this message when re-running chatbot**: You may let your user know that the chatbot is running again.
   - **Set Crisp conversation segment when a session starts**: You can assing one or more Crisp segments when the conversation starts. It may be very useful for a statistical analysis later, for instance, to distinguish conversations with chatbot from others.

2. **User Requests Human Assistance**:
   - **Send This Message When User Requests Human**: Specify a message that the chatbot will send when a user asks to speak with a human.
   - **Pause the Chatbot When User Requests Human Assistance**: Enable this option to stop the chatbot from responding when a user requests human help.
   - **Notify Me When User Requests Assistance**: Set up email notifications to alert you when a user is waiting for human assistance.

3. **Add Standard Action Buttons to the Messages**:
   - **Feedback Buttons**: Create buttons that allow users to provide feedback (good or bad) on the chatbot's performance.
   - **Mark Resolved Button**: Add a button that users can click to mark the conversation as resolved.
   - **Request a Human Operator**: Include a button that users can click to request assistance from a human operator.

4. **Custom Buttons**:
   - **Add Custom Buttons Based on User Query Class**: Define buttons that will appear based on the mood or type of user query (e.g., greeting, question, frustration). You can specify the button's label, icon, value, and URL to redirect users when clicked.

6. **Automation Based on a Schedule**:
   - **Open Schedule Calendar**: Create time slots for when the chatbot should be active or paused. You can set specific times for the chatbot to respond or remain silent.

5. **Coordinate the Chatbot with Crisp Triggers**:
   - **Wait for Crisp Trigger Response**: Check this option to make the chatbot wait for a response from a Crisp trigger before replying.
   - **Wait Time (in seconds) for Crisp Trigger Response**: Specify the duration (in seconds) the chatbot should wait for a trigger response.


**Paused Sessions**:
   - **View Data on Paused Sessions**: Access information about chat sessions where the AI has been deactivated due to an agent joining the conversation.

## Step 5: Testing Your Chatbot

Before launching your chatbot, it’s crucial to test its functionality. Here’s how to do it:

**Use the Live Test Feature**: The Enum dashboard provides a live test feature that allows you to interact with your chatbot as if it were live on your website.

  - **1**: Click the "Show Crisp chatbox" button in the Enum dashboard.
  - **2**: Interact with the chatbot as if it were live on your website. Test various scenarios to ensure it responds correctly.
  - **3**: If you want to run the chatbot in a test environment, specify this in the settings before testing.


## Step 7: Monitoring and Improving Your Chatbot

After launching your chatbot, it’s essential to monitor its performance and make improvements over time:

- **Analytics**: Use Crisp's analytics tools to track user interactions, response times, and satisfaction rates.
- **Enum chatbot stats**: the statistics of pressed buttons can be found on the Stats tab of the *Settings, logs, stats* menu for a project.
- **User Feedback**: Collect feedback from users to identify areas for improvement.
- **Regular Updates**: Continuously update your chatbot's responses and features based on user needs and business changes.

## Conclusion

Creating and setting up a chatbot for Crisp is a straightforward process that can significantly enhance your customer support capabilities. By following the steps outlined in this article, you can create a chatbot that provides instant assistance, collects valuable data, and improves overall user experience. Remember to monitor its performance regularly and make adjustments as needed to ensure it remains effective and relevant to your users' needs. 

## Useful resources

- [The official Crisp manual on installing and using the Enum chatbot](https://help.crisp.chat/en/article/how-can-i-create-an-ai-chatbot-using-chatgpt-s8b0q8/)
- [How to create a great prompt](https://www.enumhq.com/blog/posts/art-of-creating-great-prompts/)
