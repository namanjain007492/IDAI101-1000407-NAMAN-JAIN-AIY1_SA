# IDAI101-1000407-NAMAN-JAIN-AIY1_SA
AI-Based Smart Solutions: Designing Chatbots for Real-World Challenges - Smart Campus Assistant: Navigating Life on Campus with AI
Link for the bot:   https://namanjain007492.github.io/IDAI101-1000407-NAMAN-JAIN-AIY1_SA/
CampusBot – Dialogflow Documentation
1. Project Overview
   
CampusBot is a virtual assistant designed for Jain Vidyalaya to provide instant information about admissions, courses, fees, facilities, and campus life. It is built using Dialogflow ES, a natural language understanding platform that allows creation of conversational interfaces. 

The goal of CampusBot is to make information easily accessible to students, parents, and staff, reducing the need for manual queries and improving communication efficiency within the institution.

3. Bot Summary
   
CampusBot responds to user questions about campus-related topics such as admissions, events, fees, and facilities. It uses intents and entities to understand user input and deliver accurate responses. All responses are static (no webhook or API integration). The agent operates under the Asia/Colombo timezone with English as the default language.

5. Intents (Detailed View)
   
Admissions Info

• Training Phrases: How can I apply?, Tell me about the admission process, What are the requirements for joining?, How do I register?

• Response: You can apply online through our admission portal. Visit the Admissions page for more details.

• Entities Used: None
Contact Info

• Training Phrases: Contact details, College phone number, Email address, How to reach campus?

• Response: You can contact Jain Vidyalaya at +94 11 234 5678 or email info@jainvidyalaya.lk.

• Entities Used: None

Courses Offered

• Training Phrases: List of available courses, Courses offered in Science department, What programs are available?

• Response: We offer courses in Computer Science, Commerce, Science, and Arts.

• Entities Used: department

Events And Clubs


• Training Phrases: Upcoming events, What clubs are there?, Tell me about the cultural fest

• Response: Our campus hosts events like Sports Day, Cultural Fest, and Tech Expo, with clubs in each department.

• Entities Used: event_name, facility_type

Facilities Info

• Training Phrases: Tell me about facilities, What facilities are in campus?, Gym and library info

• Response: Facilities include a library, hostel, canteen, gym, and labs accessible during working hours.

• Entities Used: facility_type

Fees Details

• Training Phrases: Fee details, Tuition fee, Hostel fee for 1st year Commerce

• Response: Fees vary by department and year. Hostel charges are separate and available on the Fees page.

• Entities Used: department, year

General FAQs

• Training Phrases: College timings, Holiday list, Office hours, Exam schedule

• Response: College hours: 8 AM to 4 PM (Mon–Fri). Holidays are listed on the official website.

• Entities Used: None

Hostel Info

• Training Phrases: Hostel details, Is hostel available?, Hostel rules, Hostel timings

• Response: Hostel accommodation is available for all students. Timings and rules are provided during admission.

• Entities Used: facility_type

Library Info

• Training Phrases: Library info, Library timings, Book borrowing rules

• Response: Library hours are 9 AM to 6 PM, Monday to Saturday. Books can be borrowed with a student ID.

• Entities Used: facility_type

Placement Info

• Training Phrases: Placement opportunities, Companies visiting campus, Internships available

• Response: Our Placement Cell organizes recruitment drives and guides students for internships and jobs.

• Entities Used: None

7. Entities (Detailed View)
   
department

Reference Values and Synonyms: Computer Science, Commerce, Science, Arts

Usage: Helps CampusBot identify user queries related to this category.

year

Reference Values and Synonyms: 1st Year, 2nd Year, 3rd Year, 4th Year

Usage: Helps CampusBot identify user queries related to this category.

faculty_name

Reference Values and Synonyms: Dr. Sharma, Ms. Mehta, Mr. Kumar

Usage: Helps CampusBot identify user queries related to this category.

event_name

Reference Values and Synonyms: Sports Day, Cultural Fest, Tech Expo, Orientation

Usage: Helps CampusBot identify user queries related to this category.

facility_type

Reference Values and Synonyms: Library, Canteen, Hostel, Gym, Club

Usage: Helps CampusBot identify user queries related to this category.

9. Agent Configuration
    
• Platform: Dialogflow ES

• Language: English (en)

• Time Zone: Asia/Colombo

• ML Confidence: 0.3

• Default Welcome Intent: Disabled

• Webhook: Not used (static responses)

11. Workflow Summary
    
When a user sends a message, Dialogflow matches it with the most relevant intent using trained phrases. Entities help extract specific details such as department names or facilities. CampusBot then replies with predefined static responses that guide the user to the appropriate information.

13. Conclusion
CampusBot helps Jain Vidyalaya improve communication by answering common student queries about admissions, fees, facilities, and events instantly. In future versions, webhook integrations and live data fetching can be added for more dynamic interactions.
