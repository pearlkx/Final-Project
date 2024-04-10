# CommunityConnect
### CS50- Pearl Koswara and Tam Jing Xuan
### Final Project


#### Video Demo:  [https://drive.google.com/file/d/1B6ebUoVoswQs4NP0_K8WbDipJdrb_DTk/view?usp=sharing]

#### Description: CommunityConnect is a comprehensive platform designed for Non-Governmental Organisations (NGOs) seeking assistance, both financial and non-financial, from socially conscious companies interested in making a meaningful impact. The platform that help to build a sustained and effective communication between the NG)s and the corporate entities.

**Introduction**

Despite the flourishing ecosystem, identifying the right organisation to support can be a challenging endeavor. Traditionally, the path to partnership is strewn with obstacles, from exhaustive due diligence to the inherent limitations in an NGO's outreach capabilities. Recognizing this, CommunityConnect offers an intuitive, data-driven interface that transcends these barriers, enabling seamless identification, communication, and alignment of missions between NGOs and corporate entities.

**Features**

Our platform aims to bridge the information gap and streamline the matchmaking process between companies and NGOs. We achieve this by providing both parties with an intuitive interface for effortless organization discovery. This functionality enables users to:

1. Create an account and log in. Implementing Route Guards from the beginning of the user’s interaction with the application helps facilitate the enforcement of user roles and permissions. Authentication is provided by Firebase.
2. View postings by different NGOs and companies. The "Posting Page" is the heart of our platform, empowering NGOs to voice their needs and seek assistance. The data is then processed by Django and a HTTP POST request is sent to firebase.
3. Search and filter postings based on various factors like location, financing, SDGs, industry, etc.
4. Save and communicate with organisations that align with their corporate mission.
5. Submit post requests to allow us to champion their causes to a larger audience, effectively finding the right partners.

**Tech Stack**

**Backend Development:** Built using Python and the Django web framework, the backend of CommunityConnect ensures robustness, scalability, and performance.

**Database Management:** Leveraging a relational database such as PostgreSQL, CommunityConnect efficiently stores and manages data, ensuring reliability and data integrity.

**Frontend Development:** The frontend of CommunityConnect is developed using Vue.js, a progressive JavaScript framework known for its versatility and responsiveness. Chakra UI is employed for styling, enhancing the visual appeal and usability of the platform. We also used html to improve the formatting of the website.

**Authentication and Security:** User authentication is handled securely using Firebase authentication, implementing best practices to safeguard user data and privacy.

**Deployment:** While the application is currently hosted locally, we have plans to deploy it on a cloud platform such as Heroku, ensuring accessibility and scalability for users worldwide.

**Files**

**node_modules:** The node_modules folder contains libraries downloaded from npm. For our CommunityConnect project, we used npm to install callsites
**firebase.json:** Contains the code used to authenticate the user login based on the database in node_modules
**firepit-log.txt:** Firepit is a standalone, portable version of the Firebase command-line interface
**index.html:** Contains the code used to format the homepage of CommunityConnect
**package-lock.json:** Automatically generated for any operations where npm modifies either the node_modules tree, or package.json. It describes the exact tree that was generated, such that subsequent installs are able to generate identical trees, regardless of intermediate dependency updates
**package.json:** Contains information about the Vue.js interface, such as its name, version, dependencies, and scripts
**vite.config.js:** Vite is a frontend build tool to configure a development environment for Vue

**Considerations**

1. Although we learnt Flask as part of our Week 9 CS50x Topic, we struggled in creating a website from scratch due to its simpler tools. We then searched for more accessible tools for web development and we found Django. Unlike Flask which has a lightweight micro-framework and has a “build from scratch” approach, Django is equipped with many built-in tools for rapid development, which provided us with a lot of convenience for our project.
2. While we were more familiar with SQLite from our Week 7 CS50x Topic, we found SQLite to have very limited scalability, which would limit our database and website workload. Hence, we chose the alternative PostgreSQL, which is suitable for complex workloads and applications that require complex queries and data types. 
3. While working through the project, we chanced upon Vue.js, which builds on top of standard HTML, CSS, and JavaScript and provides a declarative, component-based programming model that helps to develop user interfaces more efficaciously. We then decided to use Vue.js as it can better integrate HTML, CSS, and JavaScript for our project.

In summary, CommunityConnect represents a paradigm shift in the realm of corporate social responsibility, offering a holistic solution to foster collaboration and drive positive change. We hope that by leveraging technology to bridge the gap between NGOs and socially conscious companies, CommunityConnect empowers organizations to make a tangible impact on the world, one partnership at a time. We would like to thank the CS50x for this arduous, yet fulfilling journey. 


