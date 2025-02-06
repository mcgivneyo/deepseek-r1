# Running DeepSeek R1 with Chainlit

https://github.com/user-attachments/assets/9fe6d64a-f472-4a0c-99c0-fa8615e24dfc

how to use DeepSeek R1 while exposing the reasoning to the user using the Chainlit `Step` class.

* requires the `DEEP_SEEK_API_KEY` env variable, with a balance

## 🚀 Getting Started

To run a demo, follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/mcgivneyo/deepseek-r1.git
   ```
2. Navigate to the desired demo folder:
   ```
   cd deepseek-r1
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
4. update the `.env` file  
   Modify the `.env` file as needed to include any necessary API keys or configuration settings.
5. Run the Chainlit app in watch mode:
   ```
   chainlit run deepseek_api.py -w
   ```

