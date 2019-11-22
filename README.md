# MNIST

## Prerequisites

Install necessary python packages

`pip install -r requirements.txt`

## Train the model 

Run `python -m model.model` from the **root** directory.

After training the model, the trained weights and the optimizers are saved in 

```bash
├── model
|    ├── results
|           ├── model.pth
|           ├── optimizer.pth
```

## Running the Flask Application 

Run the **app.py** file from the **root** directory. 

`python app.py` 

Go to **localhost:5000** to access the application from the browser of your choice.



