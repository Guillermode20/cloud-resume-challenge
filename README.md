# My CV Website

This repository contains the source code for my personal CV website.

## Project Structure

### Frontend

The frontend of the website is built using raw HTML, CSS, and JavaScript.

#### `index.html`

The main HTML file that structures the content of the website. It includes sections for my contact information, social media links, and a visit counter.

#### `style.css`

The CSS file that styles the website. It includes styles for the body, container, navbar, and various other elements.

### Backend

The backend of the website is hosted on AWS and includes the following components:

- **AWS S3**: Hosts the static files (HTML, CSS).
- **AWS CloudFront**: Provides HTTPS security.
- **AWS Route 53**: Manages the domain name.
- **AWS Lambda**: Runs a Python function to fetch the visit count.
- **AWS API Gateway**: Connects the frontend to the Lambda function.
- **AWS DynamoDB**: Stores the visit count.

## How to Run
You know how to open a HTML file.

## Contact
- **Phone**: +44 07846 720207
- **Email**: william_hick@hotmail.co.uk
- **LinkedIn**: [Will Hick](https://www.linkedin.com/in/will-hick-809813303/)

## License

This project is licensed under the MIT License.
