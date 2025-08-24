## Course Revenue Optimization & Engagement Analysis
---
Leveraging Excel Analytics to Drive Strategic Course Monetization for WhiteHat academy as an EdTech Platform

### PROJECT DESCRIPTION
---
WhiteHat Academy is a rapidly growing EdTech company founded in 2019 with a mission to democratize high-quality online learning for professionals, students, and lifelong learners worldwide. With a course catalog exceeding 6,000+ digital offerings, the platform provides accessible, affordable education across subjects like Web Development, Business Finance, Graphic Design, and Musical Instruments. WhiteHat Academy employs a hybrid pricing strategy. While certain beginner-level courses are offered for free to attract new users and encourage platform sign-ups, other beginner courses — especially those in high-demand topics — are monetized at competitive entry-level prices. Intermediate and advanced courses are more consistently monetized via subscriptions and one-time purchase tiers. WhiteHat Academy's core revenue channels include paid enrollments, certification purchases, and B2B licensing to enterprise teams ( Buisiness-to-Business ).

As competition in the digital learning space increases, WhiteHat Academy is under strategic pressure to:

- Optimize pricing and packaging for different course levels

- Boost learner engagement and retention

- Prioritize investment in top-performing subjects

- Convert free users into paying customers
  
To support these goals, WhiteHat Academy relies on data analysts to unlock insights from learner behavior, course performance, and market trends — ensuring the platform stays competitive while delivering meaningful learning outcomes

**Insights and recommendations are provided on the following key areas**:

- Expand beginner-focused funnels.
 
- Invest in intermediate-to-advanced content in popular subjects.
  
- Better align pricing strategies with content length and learner expectations.


### PROJECT QUESTIONS
---
1. Which course subjects generate the highest engagement (by subscriber count)?

2. How do average price, content duration, and enrollment vary across subjects?

3. What is the distribution of free vs paid courses by subjects area and levels?

4. What are the average price points for web development courses by difficulty level?
   
5. Does course duration have a measurable effect on course pricing?
 
6. How are subscribers distributed across course levels?

7. What are the free vs. paid patterns across different levels?

8.  Which 20 courses are the most popular? What are their shared characteristics like course title, level, course type, free beginner, and content duration?

### DATA STRUCTURE
---
| Data Structure        | Description |
|-----------------------|-------------|
| course_id             | Unique course identifier |
| course_title          | Name/title of the course |
| url                   | Web link to the course |
| price                 | Enrollment fee |
| num_subscribers       | Total student enrollments |
| num_reviews           | Number of reviews received |
| num_lectures          | Count of video modules |
| level                 | Course difficulty (Beginner, All Levels, etc.) |
| rating                | User rating (0 to 1 scale) |
| content_duration      | Total hours of video content |
| published_timestamp   | Date course was published |
| subject               | Content category |


### EXECUTIVE SUMMARY
---
##### OVERVIEW FINDINGS

This analysis uncovered critical patterns in learner behavior, content consumption, and pricing sensitivity across various subjects. Web Development and Business Finance emerged as top-performing categories, while beginner-level content dominates in terms of reach and engagement.

While most successful courses are either free or priced below $100, a substantial share of revenue potential lies in optimizing course length, packaging, and progression paths. Below is the overview page from the Tableau Dashboard and more examples are included throughout the report

DASHBOARD 1
---
<img width="1499" height="1199" alt="Image" src="https://github.com/user-attachments/assets/6ede124c-7aea-4117-87f1-159234f17507" />

DASHBOARD
---
<img width="1499" height="1199" alt="Image" src="https://github.com/user-attachments/assets/3d16ea45-9c87-411e-9cac-84bca07b4664" />

Meanwhile, insights and recommendations are provided on the following key area as the findings suggest a clear opportunity for the business to;

### 1. Expand beginner-focused funnels: 
There is a strong demand for introductory contents (Beginner courses) and 80% of top 20 most popular courses are beginner-level. So, creating more high-quality beginner courses and bundle them into learning paths to convert learners into long-term customers can help the WhiteHat Acadeny as an EdTech company attract large enrollment. Also, the dataset shows that Beginner-level courses make up a large portion of:

- Free courses (used as a lead generators in EdTech companiies).

- High-subscriber counts

- Shorter content durations

By optimizing and expanding beginner-level offerings ( especially in popular subjects like Web Development and Business Finance ), WhiteHat Academy can grow its user base ( build brand trust ), improve course completion rates, and upsell to premium paths.

This is a table comprising the top 20 courses

| course_title	| level	| course_type	| free_beginner	| content_durationn | num_subscribers
|---------------|-------|---------------|-----------------------|-------------------|----------------
|Learn HTML5 Programming From Scratch	|Beginner Level	|free	|free beginner 	|10.5	|268923
|Coding for Entrepreneurs Basic	|Expert Level	|free|		|3.5	|161029
|The Web Developer Bootcamp	|Beginner Level|	paid|		|43	|121584
|Build Your First Website in 1 Week with HTML5 and CSS3|	All Levels	|free|		|3	|120291
|The Complete Web Developer Course 2.0	|Beginner Level	|paid|		|30.5	|114512
|Free Beginner Electric Guitar Lessons	|All Levels	|free|		|4.5	|101154
|Web Design for Web Developers: Build Beautiful Websites!	|All Levels	|free|		|3	|98867
|Learn Javascript & JQuery From Scratch	|All Levels	|paid|		|2	|84897
|Practical PHP: Master the Basics and Code Dynamic Websites	|Intermediate Level	|free|		|6.5	|83737
|JavaScript: Understanding the Weird Parts	|All Levels|	paid|		|11.5	|79612
|Pianoforall - Incredible New Way To Learn Piano & Keyboard	|Beginner Level	|paid|		|30	|75499
|Angular 4 (formerly Angular 2) - The Complete Guide	|Beginner Level	|paid|		|22	|73783
|Beginner Photoshop to HTML5 and CSS3	|All Levels	|free|		|2	|73110
|Web Development By Doing: HTML / CSS From Scratch	|All Levels	|free|		|1	|72932
|HTML and CSS for Beginners - Build a Website & Launch ONLINE	|All Levels	|free|		|6	|70773
|Become a Web Developer from Scratch	|All Levels	|paid|		|27.5	|69186
|Bitcoin or How I Learned to Stop Worrying and Love Crypto	|All Levels	|free|		|8	|65576
|Quickstart AngularJS	|Beginner Level	|free	|free beginner |1.5	|64128
|Learn Responsive Web Development from Scratch	|All Levels	|free|		|4.5	|59361
|Learn and Understand AngularJS	|Beginner Level|	paid|		|7	|59361


### 2. Invest in intermediate-to-advanced content in popular subjects:
From the dataset, it is observed that Intermediate and Expert courses are often paid. Subjects like Web Development and Graphic Design show high enrollment and engagement. However, there's an imbalance — not enough advanced content in high-demand areas know fully well that these courses offer higher perceived value. Users who complete beginner courses often look for more advanced content and Intermediate/expert learners are more likely to pay for upskilling. 

Filling gaps in higher-level content within in-demand subjects allows WhiteHat Academy to capture a broader learner journey, increase lifetime value, and boost premium course sales.

It also enables pathway building, where users can follow a structured learning plan from beginner to expert — an attractive feature for corporate learning and certifications.


 ### 3. Better align pricing strategies with content length and learner expectations:
Analysis of this dataset shows that price does not always correlate logically with content duration or difficulty (Level). Some long or intermediate-level courses are underpriced or even free whereas others are short, beginner-level courses are overpriced for their value. Pricing should reflect not just duration, but value, subject matter, and level. Consider tiered pricing based on content length and depth.


### Why It’s Highlighted: 
- Inconsistent pricing damages user trust and conversion.

- Perceived course value is tied closely to length, level, and subject.

- Platforms like Coursera, Udemy, and LinkedIn Learning use tiered pricing based on these very factors.

By standardizing pricing tiers — e.g., based on duration and level — WhiteHat Academy can optimize perceived value, reduce drop-offs, and increase conversions.

Example:

Beginner (free or low-cost)

Intermediate (mid-range pricing)

Expert (premium pricing, maybe with certification)

This would also benefit B2B (Business-to-Business) pricing models, where companies want to pay based on content depth and duration.



### STEP 5. SHARE (INSIGHTS AND RECOMMENDATIONS)

Suggest strategies and actions based on insights to guide stakeholders which includes the following;

##### INSIGHTS

 1. **Subscriber Distribution by Subject**: The Web Development has the most number of subscribers. Almost 67% if you calculate that. Followed by Business Finance. The number of subscribers for the other two subjects is significantly lower compared to Web Development. These subjects have high demand — ideal for launching new courses or premium content

 2. **Average Price, Duration & Student Count by Subject**: Web Development may command higher prices and longer durations. Use this to benchmark pricing strategies per subject. Business Finance courses might be shorter but attract large enrollments due to accessibility as it comparably matches the Web Development returns. Consider offering micro-courses in low-duration categories that still yield high value.

 3. **Does Course Duration Impact Price?**
There may be a moderate positive correlation: longer courses may charge higher prices, but not always. Pricing should reflect not just duration, but value, subject matter, and level. Consider tiered pricing based on content length and depth.
    
##### RECOMMENDATIONS

 - Increasing advanced-level content in top-performing subjects.

- Bundling free beginner courses with paid follow-ups.

- Pricing optimization based on course length and subject category.

- Promoting shorter-duration, highly-rated beginner content to boost enrollments.













