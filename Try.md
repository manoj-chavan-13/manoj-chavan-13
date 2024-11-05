client/
├── public/                     # Static files
│   └── index.html              # HTML entry point
├── src/                 # Main React files
│   ├── components/  # Reusabl components
│   │   ├── Navbar.js           # Navbar component for navigation
│   │   ├── JobList.js          # Component to display list of jobs
│   │   ├── JobCard.js          # Component for a single job card
│   │   ├── ApplicationStatus.js # Component to track application progress
│   │   └── Profile.js          # User or company profile component
│   ├── pages/                  # Full page components
│   │   ├── HomePage.js         # Landing page with job categories
│   │   ├── JobPage.js          # Detailed view of a single job posting
│   │   ├── Dashboard.js        # User dashboard for job applications
│   │   ├── CompanyDashboard.js # Company dashboard to manage job listings
│   │   └── Auth.js             # Login page with Google/LinkedIn options
│   ├── services/               # API services for handling backend requests
│   │   ├── authService.js      # Auth-related API calls
│   │   ├── jobService.js       # Job-related API calls
│   │   └── applicationService.js # Application-related API calls
│   ├── App.js                  # Main React component
│   ├── index.js                # ReactDOM render
│   └── App.css                 # Global styles
└── package.json                # Frontend dependencies
