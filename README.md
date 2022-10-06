![Streamlit](https://res.cloudinary.com/dyd911kmh/image/upload/v1640050215/image27_frqkzv.png)

Table of Contents:

-   [What is Streamlit?](https://www.datacamp.com/tutorial/streamlit#1-what-is-streamlit-)
-   [Why should data scientists use Streamlit?](https://www.datacamp.com/tutorial/streamlit#2-why-should-data-scientists-use-streamlit-)
-   [How to use Streamlit](https://www.datacamp.com/tutorial/streamlit#3-how-to-use-streamlit)
    -   [Install Streamlit](https://www.datacamp.com/tutorial/streamlit#install-streamlit)
        -   [On Windows:](https://www.datacamp.com/tutorial/streamlit#on-windows-)
        -   [On macOS:](https://www.datacamp.com/tutorial/streamlit#on-macos-)
        -   [On Linux:](https://www.datacamp.com/tutorial/streamlit#on-linux-)
    -   [How to run your Streamlit code](https://www.datacamp.com/tutorial/streamlit#how-to-run-your-streamlit-code)
    -   [Display texts with Streamlit](https://www.datacamp.com/tutorial/streamlit#display-texts-with-streamlit)
    -   [Display an image, video or audio file with Streamlit](https://www.datacamp.com/tutorial/streamlit#display-an-image-video-or-audio-file-with-streamlit)
    -   [Input widgets](https://www.datacamp.com/tutorial/streamlit#input-widgets)
    -   [Display progress and status with Streamlit](https://www.datacamp.com/tutorial/streamlit#display-progress-and-status-with-streamlit)
    -   [Sidebar and container](https://www.datacamp.com/tutorial/streamlit#sidebar-and-container)
        -   [Sidebar](https://www.datacamp.com/tutorial/streamlit#sidebar)
        -   [Container](https://www.datacamp.com/tutorial/streamlit#container)
    -   [Display graphs with Streamlit](https://www.datacamp.com/tutorial/streamlit#display-graphs-with-streamlit-)
        -   [Why do we need visualization?](https://www.datacamp.com/tutorial/streamlit#why-do-we-need-visualization-)
    -   [Display maps with Streamlit](https://www.datacamp.com/tutorial/streamlit#display-maps-with-streamlit)
    -   [Themes](https://www.datacamp.com/tutorial/streamlit#themes)
-   [Build a machine learning application](https://www.datacamp.com/tutorial/streamlit#4-build-a-machine-learning-application)
-   [How to deploy a Streamlit app](https://www.datacamp.com/tutorial/streamlit#5-how-to-deploy-a-streamlit-app)

## What is Streamlit?

Streamlit is a free and open-source framework to rapidly build and share beautiful machine learning and data science web apps. It is a Python-based library specifically designed for machine learning engineers. Data scientists or machine learning engineers are not web developers and they're not interested in spending weeks learning to use these frameworks to build web apps. Instead, they want a tool that is easier to learn and to use, as long as it can display data and collect needed parameters for modeling. Streamlit allows you to create a stunning-looking application with only a few lines of code.

## Why should data scientists use Streamlit?

The best thing about Streamlit is that you don't even need to know the basics of web development to get started or to create your first web application. So if you're somebody who's into data science and you want to deploy your models easily, quickly, and with only a few lines of code, Streamlit is a good fit.

One of the important aspects of making an application successful is to deliver it with an effective and intuitive user interface. Many of the modern data-heavy apps face the challenge of building an effective user interface quickly, without taking complicated steps. Streamlit is a promising open-source Python library, which enables developers to build attractive user interfaces in no time.

Streamlit is the easiest way especially for people with no front-end knowledge to put their code into a web application:

-   No front-end (html, js, css) experience or knowledge is required.
-   You don't need to spend days or months to create a web app, you can create a really beautiful machine learning or data science app in only a few hours or even minutes.
-   It is compatible with the majority of Python libraries (e.g. pandas, matplotlib, seaborn, plotly, Keras, PyTorch, SymPy(latex)).
-   Less code is needed to create amazing web apps.
-   Data caching simplifies and speeds up computation pipelines.

## How to use Streamlit

### Install Streamlit

#### On Windows:

1.  Install Anaconda and create your environment
2.  Open the terminal

![Install Streamlit 1](https://res.cloudinary.com/dyd911kmh/image/upload/v1640050214/image14_dff6up.png)

1.  Type this command in the terminal to install Streamlit:

```
pip install streamlit

```

1.  Test if the installation worked:

```
streamlit hello

```

![Install Streamlit 2](https://res.cloudinary.com/dyd911kmh/image/upload/v1640050213/image10_drtcnj.png)

When you type this command in the terminal, the page below should open automatically:

![Install Streamlit 3](https://res.cloudinary.com/dyd911kmh/image/upload/v1640050215/image30_fmmdck.png)

#### On macOS:

1.  Install pip:
    
    ```
    sudo easy_install pip
    
    ```
    
2.  Install pipenv:
    
    ```
    pip3 install pipenv
    
    ```
    
3.  Create your environment. Open your project folder:
    
    ```
    cd project_folder_name
    
    ```
    

Create a pipenv environment:

```
pipenv shell

```

1.  Type this command to install Streamlit:
    
    ```
    pip install streamlit
    
    ```
    

Test if the installation worked:

```
streamlit hello

```

#### On Linux:

1.  Install pip:
    
    ```
    sudo apt-get install python3-pip
    
    ```
    
2.  Install pipenv:
    
    ```
    pip3 install pipenv
    
    ```
    
3.  Create your environment. Open your project folder:
    
    ```
    cd project_folder_name
    
    ```
    

Create a pipenv environment:

```
pipenv shell

```

1.  Type this command to install Streamlit
    
    ```
    pip install streamlit
    
    ```
    
2.  Test if the installation worked:
    
    ```
    streamlit hello
    
    ```
    

### How to run your Streamlit code

```
streamlit run image_editor.py

```

![How to run your Streamlit code](https://res.cloudinary.com/dyd911kmh/image/upload/v1640050214/image16_yxbgob.png)

Streamlit commands are easy to write and understand. With just a simple command, you are able to display texts, media, widgets, graphs, etc.


