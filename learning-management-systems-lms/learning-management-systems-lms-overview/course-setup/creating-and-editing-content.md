# Creating and Editing Content

## Readings and Videos

{% hint style="info" %}
All content should be indented 2 levels so that it resides "inside" a topic. \(except Module Assessments!\)
{% endhint %}

For each reading and video, create a "Page". Edit the page, click "Edit HTML," and use the iframe code below.

```markup
<iframe 
    style="width: 100%; 
    height: 1024px;" 
    src="<KURRICULUM_LINK_HERE>" 
    width="100%" 
    height="1024px" 
    allowfullscreen="allowfullscreen" 
    webkitallowfullscreen="webkitallowfullscreen" 
    mozallowfullscreen="mozallowfullscreen">
</iframe>
```

Replace `<KURRICULUM_LINK_HERE>` with the URL of the module overview page.   
This can be derived from the development server by replacing the root of the URL from the development server \(`https://quizzical-brahmagupta-52e67a.netlify.app/`\) with the main curriculum server \(`https://kurriculum.kenzie.studio/`\)  
  
Ex: `src="https://kurriculum.kenzie.studio/modules/Hello_Kenzie/Module_Overview/index.html"`

## Quizzes \(Checkpoints\)

Quizzes in our current format are usually used as "Checkpoints" - practice quizzes which gauge progress but do not effect a learner's grade.  

1. For each checkpoint create a "Quiz".
2. Edit the HTML to add the following code:

   ```markup
   <h1>Check your understanding!</h1>
   <p>Complete the following checkpoint to continue.</p>
   <p><strong>Get something wrong?</strong><br />Return to the reading(s) and video(s) to refresh your memory!</p>
   <p><strong>Still stuck?</strong><br />Refer to your Engineering Skills to identify some strategies that might help you. Don't forget to take advantage of resources such as Slack, office hours, and your peers.</p>
   ```

3. Edit the quiz options so that they match the following:
   * Do not set any **Quiz Restrictions**
   * Assign to **Everyone**
   * Be sure to leave **Due**, **Available from**, and **Until** blank.
   * For each question, you will have to manually input the question, answers, and feedback. Use the "edit" options to ensure code samples render legibly.`<pre></pre>`creates code blocks and `<code></code>` creates in-line code samples.
   * Double-check the questions and answers and make sure they align with the feedback.

## Activities

1. Create an Assignment \(Assignment Group: "Activities", Display Grade as Points\).
2. Edit HTML and use the iframe code above but swap out the URL for the activity's URL, as described.
3. Update the submission type to match what students should turn in \(Usually: Online -&gt;  Website URL or Text Entry\)

{% hint style="warning" %}
Selecting multiple assignments has been known to introduce submission bugs, or cause submissions to be overlooked. As a best practice, use only one submission type for each assignment. If a URL and text is needed, solutions include `README.md` files and the Canvas's assignment comments.
{% endhint %}

## **Assessments**

1. Create Assignment \(Assignment Group: "Assessments"\).
2. Edit HTML and use the iframe code above but swap out the URL for the assessment's URL as described.
3. Update the submission type to match what students should turn in \(Usually: Online -&gt; Website URL\).

## Due Dates

As a best practice, due dates will be transposed when a course is copied for a new term, or added when the LMS Administrator implements new content as part of the [Curriculum Development Process](../../../curriculum-development/curriculum-development-process-overview/). They should be checked for accuracy on a weekly basis, as situations may arise that require deviation from the schedule \(such as Holiday Breaks\).

