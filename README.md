# Uni Variate Linear Regression:
Let's Get This Prediction Thing Started! Notebook captures my intutions while learning the model and bringing them to implementation.

---
**Contents:**

- **Data Visualization:** Plots the training data (housing prices vs. size).
- **Model Definition:** Defines the linear model function `f_wb(x) = w*x + b`. It's the crux of our prediction!
- **Cost Function:** Implements the mean squared error cost function `J(w, b)`. This is how we measure how "off" our predictions are – the lower the cost, the better!
- **Gradient Descent:** Implements the gradient descent algorithm to find the *best* values for `w` and `b` that make that cost function hit rock bottom. Think of it as finding the lowest point in a valley!
- **Visualization of Cost and Gradient:** Shows how the cost function varies with `w` and `b`, and the direction of the gradient. It always points us towards the steepest descent!
- **Training and Prediction:** Runs gradient descent to train the model and makes a prediction using the learned parameters.
----

Staring with such facepalm :)

<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/37d6bcde-6cc1-484f-aebc-4b26de0124ee" />

---

Defining Target:

<img width="811" height="411" alt="image" src="https://github.com/user-attachments/assets/b71dde90-9033-4488-a7d4-abc5b57b42f8" />

---

Observing some intuitions:

<img width="980" height="381" alt="image" src="https://github.com/user-attachments/assets/6c27fe06-5ca3-4456-8e52-cd5d9f30e1c4" />
<img width="706" height="348" alt="image" src="https://github.com/user-attachments/assets/0863ff42-6c2c-4ea5-812e-af83de5f017c" />

---

Finally well formed prediction

<img width="560" height="443" alt="image" src="https://github.com/user-attachments/assets/8a7ca43b-4f3d-4cb2-a331-9433c460804a" />
