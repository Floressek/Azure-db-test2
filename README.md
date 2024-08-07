# Azure DB Test 2

This repository contains code for testing Azure database functionalities and integrating with various APIs. Each folder with code requires an `.env` file containing the necessary API keys.

## Repository Structure

- `connection-upload/` - Code related to uploading connections.
- `json_embeddings/` - Code for handling JSON embeddings.
- `queries/` - Code for executing and managing queries.
- `rag-like-capabilities/` - Code for RAG-like capabilities.

## Environment Variables

Each folder with code requires an `.env` file with the appropriate API keys. Below is an example of what the `.env` file should look like:

```plaintext
# Example .env file content
API_KEY=your_api_key_here
ANOTHER_KEY=your_another_key_here
```
Make sure to replace your_api_key_here and your_another_key_here with your actual API keys.

## Getting Started

To get started with this repository, follow the steps below:

1. Clone the repository:

```bash
git clone https://github.com/Floressek/Azure-db-test2.git
cd Azure-db-test2
```

2. Set up the environment:

Create an .env file in each folder where the code requires API keys. Use the example above as a guide.

3. Install dependencies:

Navigate to the respective folder and install the necessary dependencies. For example, if using Python and pip, you might run:

```bash
cd connection-upload
pip install -r requirements.txt
```

4. Run the code:

Navigate to the respective folder and execute the code as required. For example:

```bash
python main.py
```

## Contributing
If you would like to contribute to this repository, please fork the project and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
