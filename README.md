Team Members : 
Name : Amr Khaled           ID : 2205220
Name : Mariam Waleed        ID : 2205184
Name : Mohamed Ahmed Ali    ID : 2205249

# Length Extension Attack Demonstration

This project demonstrates a length extension attack on a vulnerable MAC (Message Authentication Code) implementation and shows how to mitigate it using HMAC.

## Files Description

- `server.py`: Vulnerable server implementation using MD5 with secret prefix
- `client.py`: Attack simulation against the vulnerable server
- `server_mitg.py`: Secure server implementation using HMAC-SHA256
- `client_mitg.py`: Attack simulation attempt against the secure server

## Requirements

- Python 3.x
- `hashpumpy` library (for attack simulation)

Install the required package:
```bash
pip install hashpumpy
