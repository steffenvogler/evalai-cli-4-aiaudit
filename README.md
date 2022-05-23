# EvalAI-CLI

<b> Modified Command Line utility of EvalAI CLI </b>

EvalAI-CLI is designed to extend the functionality of the EvalAI web application to command line to make the platform more accessible and terminal-friendly to its users.

------------------------------------------------------------------------------------------

## Contributing Guidelines

If you are interested in contributing to EvalAI-CLI, follow our [contribution guidelines](https://github.com/Cloud-CV/evalai-cli/blob/master/.github/CONTRIBUTING.md).

## Development Setup

0. Overview How-To is here [AI4H Github page](https://fg-ai4h.github.io/health-aiaudit-platform/#/)

1. Setup the development environment for EvalAI and make sure that it is running perfectly.

2. Clone the evalai-cli repository to your machine via git

    ```bash
    git clone https://github.com/steffenvogler/evalai-cli-4-aiaudit.git evalai-cli
    ```

3. Create a virtual environment

    ```bash
    cd evalai-cli
    virtualenv -p python3 venv
    source venv/bin/activate
    ```

4. Install the package locally

    ```bash
    pip install -e .
    ```
 
5. Change the evalai-cli host to make request to local EvalAI server running on `http://localhost:8000` by running:
   
   ```bash
   evalai host -sh http://localhost:8000
   ```


6. Login to cli using the command ``` evalai login```
Two users will be created by default which are listed below -

    ```bash
    Host User - username: host, password: password
    Participant User - username: participant, password: password
    ```
