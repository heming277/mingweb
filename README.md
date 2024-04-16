#Personal Website Template

This is my open-source personal website template that can showcase one's portfolio, blog, and skills online. 

Built with HTML, JavaScript, CSS, and powered by TailwindCSS for styling. 

This project uses Parcel as a build tool and ready to be deployed on platforms like Vercel.

## Features

- **Responsive Design**: Built with TailwindCSS for a mobile-first approach.
- **Dynamic Content**: Easily manage your blog posts through Contentful.
- **Dark Mode**: A toggle for dark mode to enhance user experience.
- **Contact Form**: Integrated with Nodemailer for easy contact form setup.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js
- npm

### Installation

1. Clone the repository:

git clone https://github.com/your-github-username/mingweb.git

2. Navigate to the project directory:

cd mingweb

3. Install dependencies:

npm install

### Environment Variables

Create a `.env` file in the root directory and add the following variables with your own values:

CONTENTFUL_SPACE=your_contentful_space_id
CONTENTFUL_ACCESS_TOKEN=your_contentful_access_token
GMAIL_APP_PASSWORD=your_gmail_app_password


## Development

To start the development server, run:

npm start 


## Building for Production

To create a production build, run:

npm run build


## Deployment

I deployed on Vercel. Follow Vercel's documentation to deploy your site.

## License

MingWeb is open-sourced software licensed with MIT license.

## Acknowledgments

- Contentful for CMS
- TailwindCSS for styling
- Parcel for bundling

Enjoy building your own personal website with my template!