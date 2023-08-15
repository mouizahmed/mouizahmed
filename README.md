### Hi there, I'm Mouiz 👋

```javascript
const aboutMe = {
    name: {
        first: "Mouiz",
        last: "Ahmed", 
    },
    languages: ['Java', 'Python', 'HTML/CSS', 'JavaScript', 'SQL/NoSQL', 'C/C++', 'MATLAB', 'Golang'],
    frameworks: ['Git', 'React', 'NextJS', 'NodeJS', 'ExpressJS', 'React Native', 'Dart/Flutter', 'Swift', 'MongoDB', 'Firebase', 'AWS', 'Bash/zsh', 'Agile'],
    design: ['Figma', 'Photoshop', 'Illustrator'],
    experience: {
        currently: 'Software Developer Intern @ Chatbase',
        past: [
            'Academic Peer Support Assistant, Lassonde School of Engineering, September 2021 - December 2021'
        ],
        education: 'B.Eng Software Engineering Co-Op, York University, 2020 - Present'
    },
    socials: {
        linkedin: 'https://www.linkedin.com/in/mouizahmed',
        instagram: 'https://www.instagram.com/_mouiz/',
        github: 'https://www.github.com/mouizahmed',
        email: 'mouiza@my.yorku.ca',
        portfolio: 'mouizahmed.com'
    }
    
}

const projects = [
        catchgpt: {
            stack: ['Python', 'Flask', 'Hugging Face API', 'PyTorch', 'NumPy', 'HTML/CSS', 'jQuery'],
            description: 'A web tool that allows educators to determine if a piece of text was AI generated with 90% accuracy. Calculates the perplexity per sentence, and burstiness via Hugging Face’s pre-trained GPT2 model. Based on these parameters, it determines if the text was, partially, or entirely AI generated. Provides text metrics and graphs for a holistic approach to plagiarism detection.';
        },
        flashstudy: {
            stack: ['Java', 'Maven', 'JDBC', 'MySQL', 'OpenAI API', 'CircleCI'],
            description: 'Collaborated with a team to create study system to help users learn and retain information efficiently. Integrates AI using OpenAI’s gpt-3.5-turbo model for definition autocompletion, fact check, and quiz question generation. Utilizes CircleCI to automate its build, test, and deployment processes (CI/CD). Followed Agile throughout its development lifecycle which led to an improved workflow and delivery. Extensive JUnit testing and documentation that follow best practices and industry standards.'
        },
        course-reviews: {
            stack: ['HTML/CSS', 'NodeJS', 'ExpressJS', 'ReactJS', 'MySQL'],
            description:
        },
        ponderful: {
            stack: ['HTML/CSS', 'NodeJS', 'ExpressJS', 'ReactJS', 'MongoDB'],
            description: 'Users can create an account to view and delete their posted reviews, via JSON Web Token Authentication. Each review is categorized by its school, faculty, course and professor stored within a MySQL database. Designed a MySQL Schema and EER Diagram based on the application’s requirements.'
        },
        useinsights: {
            stack: ['NextJS', 'HTML/CSS', 'Supabase', 'Langchain'],
            description: "Data analytics made simple -- work in progress"
        },
        fitshare: {
            stack: ['Flutter', 'Firebase'],
            description: "Social media gym app for friends encouraging accountability -- work in progress"
        }
    ]
