## Error for 4_Default_NeuralNetwork

underflow encountered in multiply
Traceback (most recent call last):
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 1078, in _fit
    trained = self.train_model(params)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 365, in train_model
    mf.train(results_path, model_subpath)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/model_framework.py", line 233, in train
    learner.fit(
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/algorithms/nn.py", line 49, in fit
    self.model.fit(X, y)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 673, in fit
    return self._fit(X, y, incremental=False)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 399, in _fit
    self._fit_stochastic(X, y, activations, deltas, coef_grads,
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 573, in _fit_stochastic
    self._optimizer.update_params(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 43, in update_params
    updates = self._get_updates(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 268, in _get_updates
    updates = [-self.learning_rate * m / (np.sqrt(v) + self.epsilon)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 268, in <listcomp>
    updates = [-self.learning_rate * m / (np.sqrt(v) + self.epsilon)
FloatingPointError: underflow encountered in multiply


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 21_NeuralNetwork

underflow encountered in multiply
Traceback (most recent call last):
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 1078, in _fit
    trained = self.train_model(params)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 365, in train_model
    mf.train(results_path, model_subpath)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/model_framework.py", line 233, in train
    learner.fit(
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/algorithms/nn.py", line 49, in fit
    self.model.fit(X, y)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 673, in fit
    return self._fit(X, y, incremental=False)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 399, in _fit
    self._fit_stochastic(X, y, activations, deltas, coef_grads,
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 573, in _fit_stochastic
    self._optimizer.update_params(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 43, in update_params
    updates = self._get_updates(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 263, in _get_updates
    self.vs = [self.beta_2 * v + (1 - self.beta_2) * (grad ** 2)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 263, in <listcomp>
    self.vs = [self.beta_2 * v + (1 - self.beta_2) * (grad ** 2)
FloatingPointError: underflow encountered in multiply


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 22_NeuralNetwork

underflow encountered in multiply
Traceback (most recent call last):
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 1078, in _fit
    trained = self.train_model(params)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 365, in train_model
    mf.train(results_path, model_subpath)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/model_framework.py", line 233, in train
    learner.fit(
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/algorithms/nn.py", line 49, in fit
    self.model.fit(X, y)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 673, in fit
    return self._fit(X, y, incremental=False)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 399, in _fit
    self._fit_stochastic(X, y, activations, deltas, coef_grads,
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 573, in _fit_stochastic
    self._optimizer.update_params(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 43, in update_params
    updates = self._get_updates(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 268, in _get_updates
    updates = [-self.learning_rate * m / (np.sqrt(v) + self.epsilon)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 268, in <listcomp>
    updates = [-self.learning_rate * m / (np.sqrt(v) + self.epsilon)
FloatingPointError: underflow encountered in multiply


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 23_NeuralNetwork

underflow encountered in square
Traceback (most recent call last):
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 1078, in _fit
    trained = self.train_model(params)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 365, in train_model
    mf.train(results_path, model_subpath)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/model_framework.py", line 233, in train
    learner.fit(
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/algorithms/nn.py", line 49, in fit
    self.model.fit(X, y)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 673, in fit
    return self._fit(X, y, incremental=False)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 399, in _fit
    self._fit_stochastic(X, y, activations, deltas, coef_grads,
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 573, in _fit_stochastic
    self._optimizer.update_params(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 43, in update_params
    updates = self._get_updates(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 263, in _get_updates
    self.vs = [self.beta_2 * v + (1 - self.beta_2) * (grad ** 2)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 263, in <listcomp>
    self.vs = [self.beta_2 * v + (1 - self.beta_2) * (grad ** 2)
FloatingPointError: underflow encountered in square


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 24_NeuralNetwork

underflow encountered in multiply
Traceback (most recent call last):
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 1078, in _fit
    trained = self.train_model(params)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/base_automl.py", line 365, in train_model
    mf.train(results_path, model_subpath)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/model_framework.py", line 233, in train
    learner.fit(
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/supervised/algorithms/nn.py", line 49, in fit
    self.model.fit(X, y)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 673, in fit
    return self._fit(X, y, incremental=False)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 399, in _fit
    self._fit_stochastic(X, y, activations, deltas, coef_grads,
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_multilayer_perceptron.py", line 573, in _fit_stochastic
    self._optimizer.update_params(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 43, in update_params
    updates = self._get_updates(grads)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 263, in _get_updates
    self.vs = [self.beta_2 * v + (1 - self.beta_2) * (grad ** 2)
  File "/home/chierighini/Code/compiladores/lib/python3.8/site-packages/sklearn/neural_network/_stochastic_optimizers.py", line 263, in <listcomp>
    self.vs = [self.beta_2 * v + (1 - self.beta_2) * (grad ** 2)
FloatingPointError: underflow encountered in multiply


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

