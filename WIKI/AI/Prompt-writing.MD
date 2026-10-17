# Prompting Best Practices

## Specify the task

The first step toward creating a great prompt is to clearly state the task, which is what you want an AI tool to do. Do you want it to draft an email or create an image? Be detailed, and avoid ambiguity, which might result in output that’s incorrect or irrelevant.

When you provide an AI tool with a task, also consider including information about:

- **Persona**: What expertise do you want the AI tool to draw from, and who is the audience? For example, you might ask the tool to complete the task with the expertise of an IT professional, or ask it to create an output geared towards a specific audience like your manager or team.

- **Format**: How do you want the output to be formatted? For example, you might ask the AI tool to create a bulleted list or a comparison table.

Those additional pieces of information can help the AI tool accomplish the task the way you want it done.

Here's an example of a prompt that includes a specific task, a persona, and a format:

**Task**: Create a social media post about an upcoming music festival that speaks to the local music community while attracting out-of-state festival-goers.

**Persona**: You're a concert promoter specializing in raising ticket sales in the alternative rock music industry.

**Format**: Limit the post to 125-characters. Include 5 relevant hashtags.

## Provide necessary context

Including detailed context in your prompts can narrow an AI tool's focus and tailor its output. Contextual information in your prompts might include:

- Reasons and objectives for performing the task

- Rules or guidelines that the output must follow

- Relevant background information the tool should consider

Those details can help an AI tool better understand your needs. Here's an example of a prompt that provides necessary **context**:

*You're a concert promoter specializing in raising ticket sales in the alternative rock music industry. Create a social media post about an upcoming music festival that speaks to the local music community while attracting out-of-state festival-goers. Limit the post to 125-characters. Include 5 relevant hashtags. **The local audience is primarily college students and young professionals (age 21-35) who follow indie rock. The festival features 12 bands over 2 days, with camping options and local food vendors**.*

That prompt is more likely to generate a more engaging and effective output that's tailored to a specific audience—without requiring additional time spent iterating on the initial prompt.

## Include references as examples

References are examples or resources that illustrate what you want an AI tool to produce. They specify details about your desired output, such as the style, tone, and format. Depending on the AI tool, you can include text, images, audio, or even video as references.

When including references in your prompts, consider these suggestions:

- Briefly explain how the references relate to the task.

- Use 2-5 high-quality examples that closely align with your needs.

- Include your own work or open-source examples if relevant.

Here's an example of a prompt that includes references:

*You're a concert promoter specializing in raising ticket sales in the alternative rock music industry. Create a social media post about an upcoming music festival that speaks to the local music community while attracting out-of-state festival-goers. Limit the post to 125-characters. Include 5 relevant hashtags. The local audience is primarily college students and young professionals (age 21-35) who follow indie rock. The festival features 12 bands over 2 days, with camping options and local food vendors. **Here are examples of successful posts from similar events:**

- **Example 1: Where mountains meet music: Indie Rocks Festival returns! Your favorite local bands + national acts. Good eats & Sleep under the stars! #Indie Rocks #SupportLocalMusic**

- **Example 2: Join Indie Fest under the desert skies! 2 nights of raw sound 2 move you + camping vibes #RoadTrip #CampLife #RockOn***

**Note**: Later in the course, you'll learn more about prompting techniques which leverage references.

## Evaluate your output

AI tools vary in their training and capabilities. Each tool has unique strengths and limitations, which can influence the quality of their output. After receiving a response from an AI tool, it's essential to carefully evaluate the quality and effectiveness of the AI-generated content before using it or sharing the output with others.

When evaluating the output, focus on factors such as:

- Accuracy

- Bias

- Relevancy

- Consistency

AI-generated content should serve as a starting point, not a final product. Sometimes while assessing and validating an AI output, you might determine that it's unacceptable or not useful. When that's the case, you should continue on to the next step of the prompting framework.

## Iterate for better results

Even well-crafted prompts might not produce ideal results on the first try. This is where iteration comes in—the process of refining your prompt based on the AI's output. Think of iteration like having a back-and-forth conversation with an AI tool. The process typically goes like this:

- You provide an initial prompt.

- The AI tool responds with an output.

- You evaluate the effectiveness of the AI-generated response.

- You refine your request based on what worked and what didn't.

- The process repeats until the AI tool produces the desired results.

Effective prompting is not about getting a perfect result on the first try, but about being willing to continuously improve your approach. Be patient, provide clear feedback, and keep prompting until you reach the desired outcome.

**Pro Tip**: When you've arrived at an effective prompt for a particular task, save it! You can use your most effective prompts as templates for different use cases and needs. This can help you replicate successful AI-output consistently—without starting from scratch every time.

### Prompts for different purposes

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

## Techniques for mastering complex tasks with AI

### Chain-of-thought prompting

**Chain-of-thought prompting** is a prompting technique that involves requesting an LLM to explain its reasoning process step-by-step, from input to final output. This technique essentially asks the AI to "show its work," making its response more transparent and structured.

To use chain-of-thought prompting, simply include key phrases in your prompt, like:

“Explain your reasoning”

“Go step by step”

These additions indicate that the AI needs to trace its thought process, which often leads to more informative and accurate output.

Let’s go through an example when this technique can be useful:

Consider an HR manager who is developing onboarding materials for a specific department. Here’s how chain-of-thought prompting could be used to identify actionable steps to handle the task:

**Prompt:**

*Create a bulleted list outlining the major duties and responsibilities of a new entry-level design hire at an ad agency. Explain your reasoning step by step.*

Notice the additional instructions “explain your reasoning step by step”? You can try using this prompt with and without this phrase to see the difference in AI’s response.

By asking the AI to break down the logic and reasoning behind the duties it suggests, the information you get from the output will also have a rationale for why it was suggested. In this case, it may help the HR manager understand each identify potential gaps and make informed decisions about how to improve their current onboarding process.

### Prompt chaining

While chain-of-thought prompting focuses on the reasoning within a single prompt, prompt chaining helps you tackle large projects by breaking them into a series of smaller, connected steps that are all in the same chat. It works like a factory assembly line: the output from one prompt is used as the input for the next, linking all your tasks together like a chain.

This technique involves three key steps:

1. **Task analysis**: Start by breaking down your complex task into a series of smaller, logical steps.

2. **Initial prompting**: Craft a focused prompt that asks the AI to complete just the first step.

3. **Input/output flow**: Use the output from the first prompt as the context for the second prompt. Continue this iterative flow until you complete the task.

Let’s take a look at an example of a prompt chain:

Consider that you are planning a short vacation to Paris. You want to make sure you create an itinerary of the things you love most in a vacation, while maximizing logistics to be as efficient as possible with your time:

**Prompt 1**: *I'm going to [city name] for 3 days. I like art, historical sites, and parks. Suggest a few well-known places I could visit on my trip.*

**Prompt 2 (chained from Prompt 1)**: *Using those locations, create a logical, day-by-day itinerary that minimizes travel time.*

**Prompt 3 (chained from Prompt 2)**: *For each day of the itinerary, suggest a few restaurants located near each of the suggested locations.*

By breaking the task into logical, digestible steps and using the output of one prompt as the specific input for the next, you transform the AI from a simple answer-generator into a structured collaborator.

### Combining prompt chaining with chain-of-thought

You can combine prompt chaining with chain-of-thought prompting to enhance the quality and accuracy of the problem-solving process *at any stage.*

Let's take a look at an example where we combine chain-of-thought prompting and prompt chaining:

Imagine you are hosting your next book club meeting and you want suggestions for what book to recommend. You would like to recommend a fantasy novel, but fantasy is not a genre your book club typically reads. The fantasy book you select needs to be engaging without being overwhelming or too complex.

**Prompt 1**: *I am hosting a book club and would like fantasy book recommendations for people that are new to reading this genre. Suggest a few books that we could use.*

**Prompt 2 (using prompt chaining and chain-of-thought prompting):** *From that list, can you suggest which book you would recommend if we are looking for a fast-paced read? Explain your reasoning.*

This iterative process continues until a final book is selected and vetted. By breaking down the complex task with prompt chaining and incorporating chain-of-thought, you can address more difficult problems while ensuring more accurate results.

### Limitations and best practices

While prompt chaining can be a useful technique, it's important to be aware of potential challenges that can occur—particularly with longer chains.

AI tools can struggle to remember context from earlier parts of the conversation as the prompt chain grows longer. This can lead to:

- Inconsistent responses

- Overlooking important details from earlier prompts

- Difficulty maintaining the overall objective of the task

To overcome these challenges and ensure effective prompt chaining, consider the following strategies:

- **Use checkpoints**: Periodically ask the AI to provide a brief summary of the overall goal.

- **Work on sub-tasks**: Divide very complex tasks into even smaller sub-tasks so that you can treat each as its own shorter chain before moving on to the next.

- **Recap and redirect**: If you notice an AI tool is deviating from the original goal, provide a recap of the essential information and redirect it back to the main objective.

By employing these strategies, you can generate more accurate and relevant output from an AI tool. As with any other prompting technique, prompt chaining relies on finding the right balance between providing necessary context and avoiding information overload.

## Bias, drift, and knowledge cutoff

### Understanding data bias

Data bias can be a foundational challenge for many AI tools. It occurs when the data used to train an AI model is skewed, incomplete, or reflects historical or societal biases. Because the tool's output is a direct reflection of its training data, it can learn and even amplify these biases in its responses.

As a responsible user, your role is to guide the tool toward a fair and impartial output. Here are a few ways you can mitigate bias when using AI tools:

- Be specific about the output you want from your prompt.

- Include important context about your intended audience and their needs.

- Provide fair and balanced references for the tool to follow.

- Use follow-up prompts to correct any output that seems biased or inaccurate.

### The constraint of knowledge cutoff

**Knowledge cutoff** is the concept that an AI model is trained at a specific point in time. AI models have a knowledge cutoff because their core knowledge is based on the data they were trained on.

You might notice that some AI tools can provide information about very recent events. Some may do this by performing a live web search to find current information and supplement their answer. It's helpful to think of this as the difference between what the model knows from its training versus what it can *look up* in the moment. The model's core knowledge isn't being updated, which is why the concept of a knowledge cutoff remains a critical limitation to be aware of.

Responsible AI use requires you to verify time-sensitive information. Always use a search engine or other reliable sources to fact-check statistics, news, or any information about recent events.

**Pro Tip**: Some AI tools tell you their knowledge cutoff date if you ask them directly.

### Drift in an AI tool's output

**Drift** is the gradual decline in an AI tool's accuracy and relevance as the real world changes. You might observe drift in two ways:

- **Factual drift**: This is when the AI's becomes less accurate over time because of its knowledge cutoff. For example, an AI's advice on "current fashion trends" may become less useful the further you get from its training date.

- **Behavioral drift**: This refers to changes in an AI tool's behavior over time. As developers update models, you might notice that the tool's formatting, tone, or conversational style changes, even when you use the same prompts.

Here are a few ways to manage and mitigate both kinds of drift:

- **Provide accurate and up-to-date context in your prompts**, especially for topics that change quickly like market trends or technology.

- **Keep chats focused by starting a new conversation for each specific task**. This also helps to reset the context if a conversation becomes too long or the output starts to feel off-topic.

- **Be explicit** with clear and specific instructions in your prompts.

### Being the human-in-the-loop

Being the "human-in-the-loop" means you are always the final judge of an AI's output. This is especially important when using more automated AI assistants or agents. While these tools can handle tasks more independently, they are still subject to the same limitations of bias, knowledge cutoff, and drift. Understanding these limitations is critical for setting up and supervising automated tools responsibly to ensure they continue to operate in a safe and helpful way over time.
