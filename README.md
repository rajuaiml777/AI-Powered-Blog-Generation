# Blogify: AI-Powered Blog Generation using LLama2

Blogify is an application that harnesses the power of artificial intelligence, specifically the LLama2 model, to automatically generate blog posts. Users can input a topic, specify the desired number of words, and choose a job profile to generate a blog post tailored to their preferences.

## Features

- **AI Blog Generation**: Utilizes the LLama2 model, a cutting-edge language model, to generate high-quality blog posts.
- **Customization**: Allows users to input their desired topic and specify the number of words for the generated blog post.
- **Job Profile Selection**: Provides options to generate blogs tailored to various job profiles, including Machine Learning Engineers, AI Enthusiasts, Business Analysts, Software Developers, Statisticians, Digital Marketers, Technology Entrepreneurs, Researchers, Data Scientists, and Common People.
- **Streamlit Interface**: Offers a user-friendly interface powered by Streamlit, making it easy for users to interact with the application.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/Blogify.git
    ```

2. Install the required dependencies:

    ```bash
    cd Blogify
    pip install -r requirements.txt
    ```

3. Download the LLama2 model:

    The LLama2 model used for AI blog generation can be downloaded from Hugging Face. You can download it using the following command:

    ```bash
    wget https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/resolve/main/llama-2-7b-chat.ggmlv3.q8_0.bin
    ```

    Alternatively, you can visit the [Hugging Face model page](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML) to manually download the model file.

4. Run the application:

    ```bash
    streamlit run app.py
    ```

## Usage

1. Launch the application by running the command mentioned above.
2. Enter the desired blog topic in the input field.
3. Specify the number of words for the blog post.
4. Choose the job profile for which you want to generate the blog post from the dropdown menu.
5. Click on the "Generate" button to generate the blog post.
6. View the generated blog post displayed on the screen.
   
![Screenshot](https://github.com/rajuaiml777/AI-Powered-Blog-Generation/blob/main/models/Picture1.png))

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project utilizes the LLama2 model for AI-powered blog generation.
- The user interface is built using the Streamlit framework.

