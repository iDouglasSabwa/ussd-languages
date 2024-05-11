# ussd-languages
Simple USSD to display computer language frameworks

This code processes USSD requests received as POST parameters and generates appropriate responses. It starts by extracting relevant information such as session ID, phone number, service code, and user input from the request.

If the user input is empty, it means it's the start of a new session, so the code presents a menu of options. If the user provides input, it processes the input and generates a response accordingly. The response is sent back with appropriate headers.
