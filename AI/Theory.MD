# There are three common ML approaches used to develop AI tools

- **Supervised** learning is used to train tools from a massive dataset that has been labeled by humans. This technique is often used when there is a specific, known output in mind. For example, an image generator is trained on millions of labeled pictures, like ones explicitly labeled "cat." ML enables the tool to recognize the features, patterns, and characteristics of cats so that it can create custom, new images.

- **Unsupervised** learning is used to train tools from a dataset that has not been labeled by humans. This technique is used to identify patterns and structures in data when there isn't a specific, known output in mind. For example, an image generator analyzes a large dataset of animal photos. ML enables the tool to identify patterns on its own, clustering images with similar features like whiskers and pointy ears. This allows it to learn what a "cat" looks like without any human-provided labels.

- **Reinforcement** learning is used to train tools through a process of trial-and-error that is guided by feedback. This technique is used to continuously refine and improve a tool's performance on a specific task. For example, after an image generator creates a picture of a cat, it receives feedback from a human evaluator. If the feedback is positive, this signals that the output was successful. This feedback is collected and used by developers to help improve future versions of the AI tool.

## AI tools and AI models

AI tools and AI models are different things, even though they sound similar and are closely related. An AI tool is AI-powered software that can automate or assist users with a variety of tasks. An AI model is a computer program trained on sets of data to recognize patterns and perform specific tasks. All AI tools are built on top of AI models, which are necessary for AI tools to work.

To better understand  the relationship between an AI tool and an AI model, think about a car and its engine.

## The process of training AI models

AI designers develop AI models through a process called training. Here’s an example of the typical steps a designer might take in this process, in this case for building a model that predicts rainfall:

1. **Define the problem** to be solved. AI designers want to predict rain to help people stay dry when commuting to and from work. They consider the AI tool’s features and limitations before identifying an AI solution.

2. **Collect relevant data** to train the model. AI designers gather historical data of days when it rained and days when it didn't rain over the past 50 years.

3. **Prepare the data** for training. AI designers prepare the data by labeling important features, like outdoor temperature, humidity, and air pressure, and then noting whether it rained. It's also common to separate the data into two distinct sets: a training set to use during the training step and a validation set to test after training is complete.

4. **Train the model**. AI designers apply machine learning (ML) programs to the prepared training data. As the ML programs analyze the data, they begin learning how to recognize patterns that indicate the likelihood of rainfall, like the combination of high temperatures, low air pressure, and high humidity.

5. **Evaluate the model**. AI designers use the validation set they prepared earlier to assess their model's ability to predict rainfall accurately and reliably. Analyzing a model's performance can uncover potential issues impacting the model, like insufficient or biased training data. If any issues exist, the AI designers can revisit an earlier step in the process and try a different approach. Once the model performs well with its validation set, the process continues to the next step.

6. **Deploy the model.** When the AI designers are satisfied with their model's performance, they deploy it in an AI tool—helping people in their city stay dry on their way to work.

Model training is an iterative process. AI designers and engineers can repeat each step as many times as necessary and make adjustments until they create the best model possible.

But the process doesn't stop at deployment. Once users interact with a model in practical situations, the model might be exposed to new challenges. AI designers should continuously monitor and collect feedback on their models, ensuring that they continue to perform reliably and to identify areas for improvement. This iterative process of continual refinement makes AI models precise and versatile, resulting in effective, reliable AI tools.

## A practical approach to getting started

1. **Identify bottlenecks**: Pinpoint the most time-consuming or repetitive tasks in your day. Is it writing first drafts? Summarizing meeting notes? Finding bugs in code?

2. **Start small**: Choose one bottleneck and find a single AI tool that addresses it. Focus on mastering that tool for that specific task.

3. **Build a habit**: Make a conscious effort to use your chosen tool whenever you perform that task. The goal is to make it a natural reflex.

4. **Evaluate and expand**: After a week or two, assess the impact. Are you saving time? Is the quality of your work improving? If the integration is successful, look for the next bottleneck and explore how AI can help you there.

## Prompts for different purposes

### Content creation

AI tools can generate a wide range of content, no matter your industry or role. You can use AI tools to help you create content like images, videos, documentation, and code. When prompted effectively, AI tools can help you spark creative ideas while saving time.

Here's a sample prompt that incorporates prompting best practices by including a specific task, context, and references:

*Act like you are a creative advertising professional who can apply innovative thinking to develop original taglines that highlight the positive qualities of a product. Create a concise tagline for a washing machine that gets clothes extra clean, has 25 settings, and fits in a small space. The tagline should use an active voice, and be no more than 6 words. Refer to these examples of successful taglines in this industry, which emphasize efficiency and convenience.

- Reference #1: "Less soap. More clean."

- Reference #2: "Transform laundry into pure magic."*

This prompt clearly states that the task is to create an original and concise tagline. It also provides necessary context by specifying the tone, style, and format of the tagline. The references include examples to help guide the AI tool's output.

Pro tip: Learn more about how you can [use Gemini as a creative partner](youtube.com/watch?si=AljYxG8O5lqT4vko&v=aiNGHMrFW-0&feature=youtu.be).

### Summarization

AI tools can quickly process and condense large amounts of text while preserving key pieces of information—making them ideal for distilling complex information into clear, concise highlights.

Here's a sample prompt that incorporates task specifics, context, and format preferences:

*Summarize the following email from a software vendor. Create a concise, professional overview that includes a bulleted list of each paid subscription tier with its benefits to clients. The summary should be easy for a sales representative to quickly review before following up with the potential client.

[Email content would follow here]*

This prompt demonstrates how specifying your style, tone, and format preferences can help generate summaries tailored to a specific audience's needs—ensuring the output is useful and relevant.

Pro tip: Learn more about how you can [use Gemini to summarize meetings](youtube.com/watch?si=zrjNKIDats3bbusd&v=h2JKmrBb-40&feature=youtu.be).

### Classification

AI tools can help you analyze and categorize content like service emails and customer reviews based on specific criteria. This feature can help you sort through information and organize it into meaningful and actionable insights.

Here's a sample prompt that specifies a task, provides clear classification criteria, and includes references:

*Analyze these customer reviews and tell me whether the sentiment of the reviews is positive, negative, or neutral. For each review, provide a one-sentence explanation for the classification based on these criteria:

- Positive: Consistently favorable comments or mostly positive with minor criticisms

- Neutral: Mixed or balanced positive and negative comments

- Negative: Consistently unfavorable comments or mostly negative with minor positive elements

- Review #1: I don't know where to begin. We had reservations for 7:00 but they seated us at 7:45. Then, no one came to our table for at least 30 minutes. Our appetizer and main course were mediocre. I did love the dessert, but that wasn't enough to change our experience.

- Review #2: I love this restaurant. The food is delicious and the service is excellent.*

This prompt begins by clearly stating that the task is to analyze the sentiment of a customer review and then specifies the options: positive, negative, or neutral. By clearly defining each category, the AI tool can make more accurate assessments and generate more consistent results.

### Extraction

AI tools can save you time by quickly gathering exactly the information you need from large, complex documents. This could be numbers from financial reports, product details from catalogs, or key points from meeting notes. To achieve more precise results, you can use the verb "extract" in your prompt, along with clear instructions about the type of information you need and how you want it formatted.

Here's a sample prompt that incorporates task specifics, relevant context, and format preferences:

*I'm planning our department's clothing budget and need to track pricing trends. Extract all of the references to items of clothing I can buy and how much each item costs from the blog post below. Create a spreadsheet of just these items. Format the output with two columns labeled "Item" and "Price." Capitalize list items and organize them by price from high to low.

[Blog post content would follow here]*

This prompt begins by clearly stating that the task is to extract all the items of clothing mentioned in the blog with their corresponding prices. It also specifies that the data should be organized in a spreadsheet, with clear formatting instructions—preparing the data for quicker analysis.

### Translation

AI tools can help facilitate communication by translating content for global audiences, making it easier to communicate with international colleagues and create multilingual content.

Here's a sample prompt that incorporates task specifics, context, and style preferences:

*We're a boutique bike shop that sells cycling and outdoor adventure gear. Translate our product descriptions from English to Dutch. Maintain the same structure and casual tone that is used in the English version in the Dutch translation. Consider cultural context and ensure the expressions maintain their marketing appeal in Dutch.

- Reference #1: Whether you’re exploring city streets or forest paths, our sleek and durable bicycle has it all.

- Reference #2: Roll into summer in style with our smooth and stylish rollerblades.*

This prompt begins by clearly stating that the task is to translate product descriptions from English to Dutch. It also specifies that the Dutch translations should maintain a similar structure and tone as the English originals, ensuring the tool generates output that resonates with the target audience while staying true to the original content's intent.

### Editing

AI tools can help refine and improve existing text to ensure clear communication. Using specific editing instructions helps AI tools make appropriate adjustments while preserving the original message.

Here's a sample prompt that incorporates task specifics, context, and audience needs:

*As the communications manager for a manufacturing company, I need to explain our site selection process to local community stakeholders. Rewrite this text for a non-technical audience. Simplify the language while keeping all the main ideas intact.

[Text content would follow here]*

This prompt demonstrates how specifying your task and the target audience can lead to more useful revisions when editing text. By clearly stating what needs to be simplified, the AI tool can make appropriate changes while maintaining the core message.

### Problem-solving

AI tools can also help you break down complex challenges and quickly come up with potential solutions. When using AI for these kinds of tasks, breaking your request into manageable steps can help to produce better results.

Here's a sample prompt that demonstrates how to structure a complex problem:

*We are running a community program to teach children gardening skills. The program runs from June 1 to August 15. We want the children to be able to grow plants that will be ready for harvest by the time the program ends. First, identify a list of 10 plants that can be planted and grown in that time period. Include sources that support the time to harvest for each plant.

Next, choose three plants from the list that will provide the children with the most variety. We want the children to grow three plants that are as different from each other as possible.*

This prompt begins with useful context about the program, such as its main purpose and timeline. It also breaks down what would otherwise be a complex task into manageable steps. As with any other use case, applying effective prompting techniques and adjusting them to fit your specific needs is the key to getting reliable and useful results from AI tools.

The examples in this reading demonstrate how your prompting approach should be adapted for different workplace tasks. While each use case can require specific techniques, the core principles remain the same—**Task, Context, References, Evaluate, Iterate**. With practice, you can become more skilled at crafting prompts for any situation and get the exact output you need.
