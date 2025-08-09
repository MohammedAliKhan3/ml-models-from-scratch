# Machine Learning: Data-Driven Parameter Estimation

The **machine learning** aspect here isn’t about whether you’re *“hard-coding”* the normal equation — it’s about **using data to determine** **β** instead of manually setting it.

## Key Idea

- If you **manually** pick **β** because it *“looks right,”* that’s **not** ML — that’s *you guessing*.  
- If you **provide the algorithm** with **X** and **y**, and it computes **β automatically** using the normal equation, that **is** machine learning — because the **parameters are derived entirely from data**.  

## Normal Equation vs. Gradient Descent

The **normal equation** is one algorithm for **training** a linear regression model.  
The *ML-ness* comes from the fact that you’re **letting the data determine the model parameters**, rather than **pre-programming** them yourself.  

### Differences Between Approaches  

| Method          | Type               | Steps               | Solution Accuracy  |
|-----------------|--------------------|---------------------|--------------------|
| **Normal Equation** | Closed-form math   | One step            | Exact              |
| **Gradient Descent** | Iterative optimization | Many steps      | Approximate        |

The **prediction** phase remains the same — the model **learns β from the data** and applies it to **new inputs**.