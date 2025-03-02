# TASK 1
- Deployed static resources for the web app using AWS Amplify Console.
- App URL: https://main.d3dji3skp0pdkc.amplifyapp.com

# TASK 2
- Created a serverless function using AWS Lambda.
- Function name: `func_nearsight`.
- Runtime: Node.js.
- Function code: exports.handler = async (event) => {
  const response = {
      statusCode: 200,
      body: JSON.stringify('Hello from Lambda!'),
  };
  return response;
};

# Task 3: Create Data Table

- Created a DynamoDB table named `table_nearsight`.
- Primary Key: `id` (String).
- Sample item: age.

# Task 4: Link Serverless Function to Web App

- Deployed the serverless function using API Gateway.
- API endpoint: arn:aws:apigateway:eu-north-1::/apis/9kac7ijprb/routes/20o1nwl
