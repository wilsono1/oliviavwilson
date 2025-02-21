---
title: Rutgers University Genetics Center Heuristic Analysis
emoji: 😃
date: 2025-02-21T23:27:25.874Z
summary: A heuristic analysis case study of the ongoing Rutgers University
  Genetics Center’s Fight Against Breast Cancer study, conducted with the
  permission of Johnathon Ross, the Head of Product Management at the Regeneron
  Genetics Center (RGC).
metaDescription: A heuristic analysis case study of the ongoing Rutgers
  University Genetics Center’s Fight Against Breast Cancer study, conducted with
  the permission of Johnathon Ross, the Head of Product Management at the
  Regeneron Genetics Center (RGC).
tags:
  - August 2024  Heuristic Analysis  User Interface Principles
  - Web Accessibility Standards
---
### **Project Overview**

During my summer 2024 internship at Regeneron Pharmaceuticals, I had the opportunity to collaborate with Johnathan Ross to update the live Rutgers University Genetics Center’s Fight Against Breast Cancer study. The project focused on identifying pain points on the live website and proposing design solutions for an app to enhance the app’s functionality and appeal. For my heuristic evaluation, I followed Jakob Nielsen’s 10 general principles for interaction design and the latest W3C web accessibility guidelines, concentrating on the onboarding, enrolling, and survey flows. The redesign suggestions aimed to improve the app’s overall functionality, making it easier to achieve research objectives. This experience was invaluable in refining my skills and contributing to the Regeneron Genetic Center’s product design team and their efforts on the app’s redesign.

[Study Of The Genetics Of Breast Cancer](https://rugcc.rutgers.edu/breast_cancer/)

![Research Study of the Genetics of Breast Cancer Flyer](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/f11c7084-9295-4a96-9c1f-e75dc8c55df7/Regeneron_Breast_Flyer_20min_Page_1-scaled-e1726606348989.jpg)

### **The Jakob Nielsen's** **Heuristic Principles and Web Content Accessibility Guidelines WCAG 2.1**

The Jakob Nielsen's 10 general principles for interaction design is what I used to conduct the heuristic analysis of the site. These include:

1. Visibility of System Status
2. Match Between the System and the Real World
3. User Control and Freedom
4. Consistency and Standards
5. Error Prevention
6. Recognition Rather than Recall
7. Flexibility and Efficiency of Use
8. Aesthetic and Minimalist Design
9. Help Users Recognize, Diagnose, and Recover from Errors
10. Help and Documentation

Additionally, I ranked all the usability issues based on their severity using Jakob Nielsen’s scale. This approach helps prioritize which issues need immediate attention and which can be addressed later, ensuring a more efficient and effective improvement process.

**0** = I don't agree that this is a usability problem at all\
**1** = Cosmetic problem only: need not be fixed unless extra time is available on project\
**2** = Minor usability problem: fixing this should be given low priority\
**3** = Major usability problem: important to fix, so should be given high priority\
**4** = Usability catastrophe: imperative to fix this before product can be released

I used the Web Content Accessibility Guidelines (WCAG 2.1) to suggest accessibility improvements. For a healthcare-related app, it’s particularly important to design with accessibility in mind, as people with disabilities, older adults, and non-native speakers will be using the site. Ensuring the app is accessible to all these groups enhances its usability and effectiveness.

[Jakob Nielsen's 10 Usability Heuristics For User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/)

[Web Content Accessibility Guidelines (WCAG 2.1)](https://www.w3.org/TR/WCAG21/)

[Severity Ratings For Usability Problems](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)

### **Visibility of System Status**

The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time.

* Communicate clearly to users what the system’s state is — no action with consequences to users should be taken without informing them.
* Present feedback to the user as quickly as possible (ideally, immediately).
* Build trust through open and continuous communication.

![Visibility of System Status error, ancestry page.](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/1328a33b-68e1-4510-a580-f06f41dcff39/Screenshot+2024-10-06+at+7.13.02%E2%80%AFPM.png)

**Enrollment Flow, Ancestry**

**1)** To improve this process, it would be helpful to include a status indicator with icons and descriptions for each part of the saliva kit and sequencing process. This visual guide would help users understand each step they need to take and the overall process. Knowing the steps involved can educate users about a process they might be unfamiliar with, which is especially important since they are submitting personal data (saliva) to an online study. This transparency will help build trust, as users will know exactly what researchers are doing with their kits and information.

**Severity Rating = 3**

### **Match Between the System and the Real World**

The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order.

* Ensure that users can understand meaning without having to go look up a word’s definition.
* Never assume your understanding of words or concepts will match that of your users.
* User research will uncover your users' familiar terminology, as well as their mental models around important concepts.

![Enrollment. Breast Cancer Survey page](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/7725c7cf-0812-4558-a57f-71e7634ffa36/Screenshot+2024-10-06+at+7.25.58%E2%80%AFPM.png)

**Enrollment Flow, Survey**

**1)** Throughout the application, the icons do not effectively indicate their subjects, which is crucial for users who rely on visual cues for communication. I recommend creating icons that closely match the subject matter to enhance user recognition and familiarity. For instance, using a pink ribbon for breast cancer would be more identifiable and intuitive for users. This approach will improve the overall user experience by making the interface more accessible and easier to navigate.

**Severity Rating = 4**

### **User Control and Freedom**

Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process.

* Support *Undo* and *Redo*.
* Show a clear way to exit the current interaction, like a *Cancel* button.
* Make sure the exit is clearly labeled and discoverable.

![Survey question: respiratory health questionaire](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/2caccaa2-af5a-44c3-a16e-c0969fcbbccc/Screenshot+2024-10-06+at+8.16.47%E2%80%AFPM.png)

**Enrollment and Surveys**

**1)** Is there too much user control in the survey? I noticed that I can skip through the entire survey. When a skip option is available, I worry that people might choose to skip questions rather than read and answer them. While the skip button provides the flexibility to disregard questions, it prevents data from being recorded which is counterproductive. I suggest removing the skip button and replacing it with a “Next” button and a “Prefer not to say” option for user comfort.

**Severity Rating = 2**

### **Consistency and Standards**

Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions.

* Improve learnability by maintaining both types of consistency: internal and external.
* Maintain consistency within a single product or a family of products (internal consistency).
* Follow established industry conventions (external consistency).

![2 pages with consistency errors. General consent quiz with different error visuals.](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/bf60cbf1-560b-4671-a8fa-367ae711d168/Screenshot+2024-10-06+at+7.48.48%E2%80%AFPM.png)

**Onboarding Flow**

**1)** There are currently different visual representations for incorrect answers. To ensure consistency, I recommend creating a universal visual representation for all incorrect answers.

**Severity Rating = 1**

### **Error Prevention**

Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action.

* Prioritize your effort: Prevent high-cost errors first, then little frustrations.
* Avoid slips by providing helpful constraints and good defaults.
* Prevent mistakes by removing memory burdens, supporting undo, and warning your users.

![General consent part of the onboarding](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/089d8ad3-746f-4a39-a669-6977bc547916/Screenshot+2024-10-06+at+7.33.00%E2%80%AFPM.png)

**Onboarding Flow**

**1)** Throughout the onboarding flow, users can click the logo in the top left corner or leave the site without any prevention measures. When this happens, their progress is lost, and their consent is reset. To address this, users should receive a warning that their progress will not be saved before they leave. This warning informs them of the potential risks and gives them a chance to reconsider. The goal is to encourage users to stay on the page and continue the onboarding process. I recommend implementing a visual pop-up with the message, “Are you sure you want to leave the page? Your progress will not be saved.” To make it more engaging, the header could read, “You’re one step closer to fighting cancer.”

**Severity Rating = 3**

![Demographic survey page](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/adc0047f-4a61-4bd5-9a3c-1973ff181002/Screenshot+2024-10-06+at+8.10.22%E2%80%AFPM.png)

![Study of the genetics of breast cancer page](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/993dd718-0025-4322-b714-629cadb33a8b/Screenshot+2024-10-06+at+8.10.31%E2%80%AFPM.png)

![Main home page of the breast cancer study](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/f2204282-b117-4411-8c81-3fb68ec31c33/Screenshot+2024-10-06+at+8.10.37%E2%80%AFPM.png)

**Enrollment Flow**

1. When users are logged into the site and click on the footer navigation, they are directed to the Help, About Us, Privacy, or Terms and Conditions pages.
2. They still appear to be logged in, as indicated by the top right navigation.
3. However, when they press “Home,” they are logged out and returned to the main page.

This error logs the user out without their knowledge. If it’s possible to keep the user logged in, that would fix the issue. If not, there should be a pop-up notification informing the user that they will be logged out and redirected to an external page.

**Severity Rating = 3**

### **Recognition Rather than Recall**

Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed.

* Let people recognize information in the interface, rather than forcing them to remember (“recall”) it.
* Offer help in context, instead of giving users a long tutorial to memorize.
* Reduce the information that users have to remember.

![Dashboard with referral widget. Error with the "x."](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/363b01f8-54de-4907-973d-a21c727bffd3/Screenshot+2024-10-06+at+8.49.09%E2%80%AFPM.png)

**Enrollment Flow, Dashboard**

When users arrive at the dashboard, either after logging in or completing enrollment, they see a referral tab that can be closed. However, once closed, the tab disappears permanently, requiring users to remember to share it with a friend. Keeping the referral tab visible helps users familiarize themselves with the interface. I recommend removing the “X” to prevent it from being closed.

**Severity Rating = 2**

### **Flexibility and Efficiency of Use**

Shortcuts — hidden from novice users — may speed up the interaction for the expert user so that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions.

* Provide accelerators like keyboard shortcuts and touch gestures.
* Provide personalization by tailoring content and functionality for individual users.
* Allow for customization, so users can make selections about how they want the product to work.

![Dashboard with referral widget. Error with the "x."](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/363b01f8-54de-4907-973d-a21c727bffd3/Screenshot+2024-10-06+at+8.49.09%E2%80%AFPM.png)

**Enrollment Flow, Dashboard**

To add flexibility and address the issue of the referral tab having an exit, I would suggest making the blocks movable widgets. This feature would allow experienced users to customize their dashboard by arranging the blocks as they prefer. If they don’t want the referral tab at the top of the dashboard, they can move it to another space.

**Severity Rating = 1**

### **Aesthetic and Minimalist Design**

Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility.

* Keep the content and visual design of UI focused on the essentials.
* Don't let unnecessary elements distract users from the information they really need.
* Prioritize the content and features to support primary goals.

![Onboarding Page with a vague illustration of man.](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/2c3df409-505b-46d8-adf5-9660c95d2f95/Screenshot+2024-10-06+at+8.59.15%E2%80%AFPM.png)

**Onboarding Flow**

The design is very vague. Adding contextual illustrations would enhance understanding and visual appeal.

**Severity Rating = 3**

![Enrollment flow. Surveys](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/032d87b1-292d-4f3d-8e78-7bd334307007/Screenshot+2024-10-06+at+8.59.26%E2%80%AFPM.png)

**Enrollment Flow, Surveys**

Removing completed surveys from the dashboard would create more space for new surveys.

**Severity Rating = 1**

### **Help Users Recognize, Diagnose, and Recover from Errors**

Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution.

* Use traditional error-message visuals, like bold, red text.
* Tell users what went wrong in language they will understand — avoid technical jargon.
* Offer users a solution, like a shortcut that can solve the error immediately.

![General consent quiz with error.](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/18b732d9-cd7b-4e32-a621-95438af9a984/Screenshot+2024-10-06+at+8.33.42%E2%80%AFPM.png)

**Onboarding Flow**

**1)** Adding an icon to the error message would make it more impactful. This visual aid could be particularly beneficial for individuals with visual impairments or those who are non-native speakers.

**Severity Rating = 1**

![Error on the survey page](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/bed9ebf7-3f68-4ee0-981c-90a66bbca107/Screenshot+2024-10-06+at+8.36.36%E2%80%AFPM.png)

**Survey Flow**

**1)** Adding an icon into the error message would be impactful. Additionally, using bold, red text would make it stand out. Currently, there are two exit options: support or “X.” I suggest adding a “Home” button to allow users to return to the dashboard easily.

**Severity Rating = 2**

### **Help and Documentation**

It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks.

* Ensure that the help documentation is easy to search.
* Whenever possible, present the documentation in context right at the moment that the user requires it.
* List concrete steps to be carried out.

![Platform usage policies page in Onboarding flow](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/0fcdc38d-0ac8-4f20-a43c-8ea17edb57bf/Screenshot+2024-10-06+at+9.10.55%E2%80%AFPM.png)

**Onboarding Flow**

The onboarding flow lacks a help button. I recommend adding one on the right side of the white box, where readers are likely to look for help after reading the text.

**Severity Rating = 2**

![Support page](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/868ed1a8-c400-46ce-b820-6cc9b4517504/Screenshot+2024-10-06+at+9.14.26%E2%80%AFPM.png)

**Support page**

The support page is lacking information. Adding more information and visuals would be effective. To prevent the user from going to an external page and link, maybe a AI help bot can be added to the application?

**Severity Rating = 2**

### **Web Accessibility**

By adhering to web accessibility standards, such as the Web Content Accessibility Guidelines (WCAG), designers and developers can create inclusive digital experiences that benefit everyone.

![Verify email page](https://images.squarespace-cdn.com/content/v1/66fead220925210eab5a87d7/7e426dfb-4b53-4b22-bebb-d346526f800d/Screenshot+2024-10-06+at+9.27.30%E2%80%AFPM.png)

**Onboarding Flow**

1. The status indicator is hard to see due to low contrast. Increasing the contrast will help people with vision impairments.
2. Adding a language setting will benefit non-native speakers.
3. The text is also too small; increasing the size will improve readability.

**Severity Rating = 2**

### **Final Takaway**

This project was incredible. Working under a product manager gave me a deeper understanding of app development and standards. I had never done a heuristic analysis in school, so learning this skill with talented professionals was an amazing experience that I hope to build on in future opportunities. It was exciting to take this analysis and develop solutions for the team. Contributing to their design library and workflows made me want to work with a large company because of their organization and specialization in app development. Additionally, this project fueled my passion for web accessibility, and I am eager to enhance my skills in this area for future projects. I have decided to enroll in the Trusted Tester Web Accessibility course to deepen my knowledge. Throughout this process, I learned a lot about user flows, potential errors, and interactions, and I am excited to continue learning more.