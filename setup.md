# SETUP

To set up the project, let's start with a virtual environment (optional).

1. In terminal, run `python3 -m venv venv`, this will create the files necessary to run a virtual environment, make sure to add the venv directory to your `.gitignore`!
2. To activate the virtual environment, run `source venv/bin/activate` in the terminal.
3. From there, just install pytorch (next step) and you are good to go!
> To deactivate the virtual environment, run `deactivate` in the terminal. Also ensure that your IDE isn't running on the virtual environment either.

## Install PyTorch

Now let's install pytorch. you can visit the [official website](https://pytorch.org/get-started/locally/) for instructions. As someone who is running on mac using pip, I'll post what I did. Or if you have access to my `requirements.txt`, you can just run `pip install -r requirements.txt` in the terminal.

`pip3 install torch torchvision torchaudio`