# Adversarial-Machine-Learning

## Adversarial Attacks

Adversarial attacks are a way to fool machine learning models by adding small perturbations to the input data. These perturbations are usually imperceptible to humans but can cause the model to misclassify the input data. There are many different types of adversarial attacks, each with its own strengths and weaknesses. Some common types of adversarial attacks include:

- **Fast Gradient Sign Method (FGSM)**: This attack works by computing the gradient of the loss function with respect to the input data and then adding a small perturbation in the direction that maximizes the loss. This attack is fast and effective, but it is also easy to defend against.

- **Projected Gradient Descent (PGD)**: This attack is similar to FGSM, but it iteratively applies small perturbations to the input data until the model misclassifies it. This attack is more powerful than FGSM but also more computationally expensive.

## List of attacks implemented

- [FGSM on MNISt dataset](./FGSM%20on%20MNIST/src.ipynb): This attack is implemented on a simple fully connected neural network trained on the MNIST dataset. The attack is able to fool the model into misclassifying the input data with high confidence. The implementation and idea is taken from this article: [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572).

- [PGD on MNISt dataset](./PGD%20on%20MNIST/src.ipynb): This attack is implemented on the same model as the FGSM attack but uses a more powerful iterative approach. The attack is able to fool the model with even higher confidence than the FGSM attack. The implementation and idea is taken from this article: [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572).

## Contributors

- [Matin Bazrafshan](https://github.com/FabulousMatin)
- [Shahriar Attar](https://github.com/Shahriar-0)
