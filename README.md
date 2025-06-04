# My Portfolio

This repository contains a static portfolio website that showcases my skills, experience, and contact information. The website is designed to be hosted on AWS S3.

## Project Structure

```
my-portfolio
├── assets
│   └── cv.pdf          # My CV in PDF format
├── css
│   └── styles.css      # Styles for the website
├── index.html          # Main entry point of the portfolio
├── about.html          # Additional information about me
├── contact.html        # Contact information and form
└── README.md           # Project documentation
```

## Getting Started

To set up and deploy this portfolio website on AWS S3, follow these steps:

1. **Clone the Repository**
   ```
   git clone <repository-url>
   cd my-portfolio
   ```

2. **Install Dependencies**
   If you have any dependencies (e.g., CSS frameworks), install them as needed.

3. **Build the Project**
   If you are using a build tool, run the build command to prepare the files for deployment.

4. **Deploy to AWS S3**
   - Log in to your AWS Management Console.
   - Navigate to S3 and create a new bucket.
   - Upload the contents of the `my-portfolio` directory to the S3 bucket.
   - Configure the bucket for static website hosting.
   - Set the appropriate permissions to allow public access to the files.

5. **Access Your Portfolio**
   Once deployed, you can access your portfolio using the S3 bucket URL.

## License

This project is licensed under the MIT License - see the LICENSE file for details.