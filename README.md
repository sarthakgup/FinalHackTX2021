# FinalHackTX2021

# Inspiration
We aspired to develop a new form of social media for the gaming community. What resulted was a way for gaming fans to connect with aspiring collegiate gamers as well as professional esports athletes around the world. As the esports industry expands every year, we see Huka growing significantly as a platform in the months to come.

# What it does
After registering for or logging into an account, users are taken to the home screen where they can see gaming clips tailored to their interests. They can also see the top 10 trending gaming clips everyday and search for games, popular content creators, or friends in the app. Additionally, users build a following by creating their own gaming content. This is an ideal feature for young gamers aspiring to earn scholarships for college gaming, or collegiate athletes hoping to get recruited by professional esports teams such as NRG or SEN.

# How we built it
Used HTML, JavaScript, and CSS for site frontend, PHP and MySQL to manage dynamic content and databases, Google Cloud for backend video storage, and Microsoft Azure for cloud deployment.

# Challenges we ran into
We struggled with deploying our web app to Azure but after hours of debugging and analysis of our implementation, we diagnosed the issue to be with the compression of the videos we were uploading. Our free cloud subscription to deploy the app had a storage limit which we were hitting due to poor compression of some of our files. We fixed this issue by performing a line-by-line analysis of our HTML code and after running tests with different videos and analyzing the deployment report in GitHub, we realized the video compression issue.

# Accomplishments that we're proud of
We are very proud of our UI that we feel is user-friendly and has many design features that are aesthetically pleasing. We are also very proud of hosting our videos in the cloud. Cloud has great potential in the future with regards to innovation so getting our feet wet in this field with a successful cloud-backend project was a prideful feat.

# What we learned
We learned a lot about implementing Google Cloud and Microsoft Azure as well as developing a website that incorporates the two to store videos in the cloud connected to a mySQL database with a crisp user-friendly UI. Interfacing all these components was a challenge but after hours of debugging, the satisfaction of our working website was worth it.

# What's next for Huka
In the immediate future, we strive to get the word out about Huka. We would also like to develop an efficient video compression algorithm to cut costs for our site as it won't remain sustainable on a student subscription for too much longer. Soon after, we hope to integrate machine learning and AI to better understand our users and tailor the app experience to their gaming interests. As our website gains popularity, we plan to use Google Analytics to make the site more user-targeted. Additionally, we see ourselves developing a mobile app for IOS/Android using React to get Huka in the palms of gamers worldwide.
